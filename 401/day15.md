# Day 15 Notes

## Cryptography

### Encryption, Decryption & Hacking

• To encrypt a message, shift your alphabet. Start with shifting by 3 letters.

• Another term for the original unencrypted message is plaintext

> To decrypt messages there are three main techniques you could use: frequency analysis, known plaintext, and brute force.

• Frequency analysis, languages tend to use some letters more than others. For example, "E" is the most popular letter in the English language. We can analyze the frequency of the characters in the message and identify the most likely "E" and narrow down the possible shift amounts based on that

• Known plaintext tend to start with similar beginnings

• Brute Force, there are only 25 possible shifts

> Encryption: scrambling the data according to a secret key (in this case, the alphabet shift).
--------
> Decryption: recovering the original data from scrambled data by using the secret key.
--------
> Code cracking: uncovering the original data without knowing the secret, by using a variety of clever techniques.

### Ceasar Cipher

> The Ceasar Cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.

• The Caesar cipher can be easily broken even in a ciphertext-only scenario. Two situations can be considered:

• an attacker knows (or guesses) that some sort of simple substitution cipher has been used, but not specifically that it is a Caesar scheme;
an attacker knows that a Caesar cipher is in use, but does not know the shift value.

#### Things I want to know more about

This is actually very interesting and I want to decipher everything now! LOL

#### Sources

[Encryption, Decryption & Hacking](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

[Ceasar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

Click to return [Home!](../README.md)
