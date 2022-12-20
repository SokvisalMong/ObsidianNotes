# Password Attacks

## Online
Obtaining a digital copy of a password, E.g. password file leak

## Offline
Obtaining a physical copy of the password, E.g. printed document including password

## Brute-force
Testing each potential possible password

## Dictionary
Dictionary password attack uses a filter to shorten or filter the brute force list

## Bespoke
Uses personal information along with other methods to try and guess a personalized password

(Dictionary and Bespoke are more powerful)

## Proxy Intercept Tool
200 return code means success

## Defending against brute-force attacks
Passwords should be encrypted and stored on the database

### Hashing
When hashing a password, it goes through a hashing algorithm (MD5) and generates a hashed password that *should* be irreversible.
This generated hashed password is in the form of a string.

There's mutliple types of encryption:
- Single key encryption: Where only 1 key is used for encrypting and decrypting a password
- One-way encryption: Uses a key to encrypt a password with no way to decrypt. Authentication is done by comparing the old hashed password with the attempted login password (that is going through the hashing algorithm again) to see if they match. If the hashes match, then the passwords are the same.

## Rainbow table or precomputing hash
Attackers can attempt to decrypt a hashed password by already having a hashed password to compare with with the database's password (usually obtained from a data leak that contains the plaintext password)

This can be countered by having a 12 bit random number appended to each password (typically system wide + a per-password part). A.K.A Salt.

#### PAM Privilege Access Management Tool
CyberArk, Beyond Tool

### Password Strength
The strength of a password depends on lenght, complexity, and predictability

### Entropy
How to generate bit entropy?
