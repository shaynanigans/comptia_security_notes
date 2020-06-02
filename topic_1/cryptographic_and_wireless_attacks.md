# Cryptographic and Wireless Attacks

## Cryptographic Attacks
### Brute-force and Dictionary Attacks
- Repeated attempt to identify a user account and/or password in order to gain access to a system such as a server
- Rainbow tables are password dictionaries stored in a way that's optimised for hashes and passwords. optimising the storage space and providing excellent look-up speed
- Many tools use a hybrid of brute-force and dictionary attack

### Brute force Tools
- Read up on Cain and John the Ripper
- Look at Openwall 

### Birthday, Known Plaintext and Cipher Attacks
- Birthday: 23 people, 2 share same birthday is greater than 50%
- Known-plaintext Attack: Attacker has access to ciphertext of several messages, and knows something about the plaintext, aka meet-in-the-middle
- Ciphertext-only Attack: Not very successful today. Attacker has ciphertext of several messages
- Chosen-plaintext attack: Attacker chooses plaintext they wish to encrypt
- Chosen-ciphertext attack Attacker chooses different ciphertexts and has access to the decrypted/plaintext
-> These types of attack can be counter-measured with good security, access control policies and MFA

### Online vs. Offline Attacks
- Crackers prefer offline attacks as odds of being tracked/detected is lower
- Offline requires work, no communication with victim system
- MD5 hashes let them be more successful
- Parallel Hash Collision Search, facilitates MAC forgery
- Online attack requires more work from victim

### Collisions
- 

## Wireless Attacks

