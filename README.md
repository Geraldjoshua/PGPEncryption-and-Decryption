# PGPEncryption-and-Decryption
two Client Application that initially exchange and validate each other’s public keys, which have been issued by a Certification Authority which they both trust. They then transmit messages to each other, using the shared key, private key, hashing and compression functions, in the same manner which PGP would do. I used Bouncy Castle to implement in java

messages are sent via file from one client to another for now.
