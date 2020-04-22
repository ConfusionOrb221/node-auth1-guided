- data is protexted by something someone knows, something they have, 
or something they are

- passwords is the most common way (something they know)

- people are trying to always get other people's passwords
- if they are easy to guess, they are vunerable
- if they are stored in an insecure store or a single point of access store, they are vunerable
- password hashing is the answer ... store the hash, not the password
- we are going to be using bcryptjs to generate hashes (the javascript module for the bcrypt algorithm)
- whatever password guess is supplied in a login attempt is used to generate a hash, which is compared to the stored hash for the real password
- rainbow tables are hackers' answer - use a lot of computing power to generate hash's for every possible password
- 