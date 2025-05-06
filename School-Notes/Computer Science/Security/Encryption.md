The act of encoding a plaintext message so that it cannot be deciphered unless you have a numerical key to decrypt it. If the message is intercepted it cannot be understood. If the key can be intercepted the encryption process is rendered useless.

# Symmetric Encryption
Symmetric encryption uses the same key to encrypt and then decrypt the data being transferred. The key has to be transferred between the communicating devices so that they both understand how to pass messages.

# Asymmetric Encryption
Uses two separate but related keys. Also known as private/public key encryption/ Used to initiate TLS connections. Slower than symmetric encryption so a secure communication session often uses hybrid encryption.

# Digital Signatures
In order to verify the integrity of a message the sender can add a digital signature to a message. The sender creates the digital signature by irreversibly reducing the encrypted message to produce a hash encrypting the hash using their private key. The send bundles the digital signature with the message and encrypts the bundle using the recipients key.

As a signature can only be decrypted by the senders public key the signature can be considered genuine and unaltered.

## Vernam Cipher
XOR with the one time pad.