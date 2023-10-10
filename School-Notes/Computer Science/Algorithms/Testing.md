# Purpose
Testing is more of looking for errors and problems than making sure the application works.

# Stages
When a computer system is being developed, it goes through various testing stages:
- Module testing — make sure each subroutine works correctly.
- Program testing — make sure each program in the system works correctly.
- System testing — make sure the whole system works as expected, and does what the original specification required.

# Designing
Test data has to be carefully selected. It should include normal (typical) data, boundary data and erroneous data[^Erroneous]. Suppose you are testing a module which allows a user to set a password. The password must be at least 8 characters, must include both uppercase and lowercase letters, at least one numeric character and no spaces.

[^Erroneous]: Invalid data that isn't expected to be there.