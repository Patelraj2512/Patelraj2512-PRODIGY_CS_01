# Caesar Cipher

A simple implementation of the Caesar Cipher encryption and decryption algorithm in Python.

## Description

The Caesar Cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher where each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on.

This implementation allows users to:
- Encrypt messages using a specified shift value
- Decrypt messages using the same shift value

## Features

- **Encryption**: Convert plaintext to ciphertext using a specified shift value
- **Decryption**: Convert ciphertext back to plaintext using the same shift value
- **Character Preservation**: Non-alphabetic characters (numbers, symbols, spaces) remain unchanged
- **Case Preservation**: Maintains the original case of letters (uppercase/lowercase)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/caesar-cipher.git
   cd caesar-cipher
   ```

2. No additional dependencies are required as the implementation uses only Python standard libraries.

## Usage

Run the script using Python:

```
python task1.py
```

Follow the interactive prompts:

1. Choose whether to encrypt or decrypt a message
2. Enter the message
3. Enter the shift value (an integer)

### Example

#### Encryption
```
=== Caesar Cipher ===
Type 'encrypt' to encrypt or 'decrypt' to decrypt: encrypt
Enter your message: Raj
Enter shift value (e.g., 3): 3
Encrypted message: Udm
```

#### Decryption
```
=== Caesar Cipher ===
Type 'encrypt' to encrypt or 'decrypt' to decrypt: decrypt
Enter your message: Udm
Enter shift value (e.g., 3): 3
Decrypted message: Raj
```

## How It Works

The algorithm works by shifting each letter in the alphabet by a fixed number of positions:

1. For encryption: Each letter is shifted forward in the alphabet by the shift value.
2. For decryption: Each letter is shifted backward in the alphabet by the shift value.
3. The algorithm handles wrapping around the alphabet (e.g., shifting 'z' by 1 gives 'a').
4. Non-alphabetic characters remain unchanged.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Created as part of the Prodigy InfoTech internship program - Task 01.