A record can be locked when one person is on it so no conflicting updates can be pushed by someone else. 

Another way is when a user tries to save an update, if the read timestamp is not the same as it was when they started the transaction, the DBMS knows another user has accessed the same object. This is harder to implement.

Another way is to use commitment ordering, this is another serialisation technique to ensure that no transactions are lost if two clients are simultaneously trying to update a record. Transactions are ordered in terms of their dependencies on one another as well as the time they were initiated.