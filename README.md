# AES Encryption & Login Validation

A piece of an original website, C#/.NET project demonstrating basic login validation, AES encryption/decryption, and object-oriented programming.

# Features

* Login and password validation
* Requires exactly 9 characters
* Rejects selected invalid characters
* AES-128 encryption and decryption
* Base64 encoded encrypted output
* Verification that decrypted data matches the original input
* Basic timer/event implementation
* Uses IDisposable* and *using statements for resource management

# How It Works

1. The user enters a login and password.
2. The input is validated.
3. Invalid input is requested again.
4. An AES key and IV are generated.
5. The login and password are encrypted.
6. The encrypted values are displayed as Base64.
7. The values are decrypted again.
8. The program checks that the decrypted values match the validated input.

Example result:

Ciphered login: encrypted value
Ciphered password: encrypted value
Decrypted login: login
Decrypted password: password
Encryption test successful.


# Technologies

* C#
* .NET
* System.Security.Cryptography
* AES
* CryptoStream
* OOP
* Events and timers


# Security Note

This is a learning project rather than a production authentication system.

For a real application, passwords should normally be stored using a suitable password-hashing approach rather than reversible encryption. Production encryption should also use authenticated encryption and appropriate key/nonce management.
