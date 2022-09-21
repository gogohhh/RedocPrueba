Message hash key authentication (HMAC) is a specific construct for calculating a message authentication code, which involves a cryptographic hash function in combination with a cryptographic secret key.

Like any MAC, it can be used to simultaneously verify data integrity and authentication of a message. The SHA-512 cryptographic hash function is used.

The hash function breaks a message into a block of a fixed size and iterates over them with a compression function. The cryptographic strength of HMAC depends on the cryptographic power of the underlying hash function, the size of its hash output and quality of the key.