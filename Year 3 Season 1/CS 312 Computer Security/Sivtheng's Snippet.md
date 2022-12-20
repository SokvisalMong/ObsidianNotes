#### Hash
- Hashing algorithm is a complex mathimatical function that transform a string of data of random output string of fixed length.
- Hashing is a form of one way encryption. A hash cannot reversed back to the original data
- Great for storing password. If attacker gets access to database, they only the hash password which should be useless for them.
- Way to crack hash password. 
 + Attempt to decode the hash password by comparing it to the hash of other password in a big database. If the password is commonly used, it is very easily decoded. (Rainbow table)
 + Dictionary attack: Attempting to find the original plaintext by hashing common passwords and comparing them to the target hash.
 + Bruteforce attack: Trying every possible combination of characters against the hashed password, time taken increases exponentially as password length and keyspace increases.
- Hashing itself isn't enough so we use salt.
#### Salt
- Salt are sort random set of characters that are appended to the end of the password because it is hashed.
- Salt are added automatically after user enters their password.
- Salt is stored in plaintext along with the hash output so the website knows what salt to use when verifying the login
 + Bruteforce and dictionary will still be an issue.
#### Pepper
- Pepper is a very short random string or character appended to the end of a password.
- Peppers are random and different for each password.
- Pepper is added when user enters their password and they won't even know.
- Website cycles through all possible peppers.
- The pepper is not stored.
