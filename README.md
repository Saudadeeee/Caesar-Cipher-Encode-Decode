# Caesar Cipher Implementation in C++

This project is a simple implementation of the Caesar Cipher algorithm in C++. The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is shifted by a fixed number of positions down or up the alphabet. The program provides both encryption and decryption functionalities.

## Features

- **Encryption**: Encode a given text using a specified shift key.
- **Decryption**: Decode a given encrypted text using a specified shift key.
- **Caesar Cipher Table**: Displays the Caesar Cipher alphabet mapping for reference.
- **Character Transformation Table**: Shows the character-by-character transformation from plaintext to ciphertext (and vice versa).

## How It Works

### Encryption
Each letter in the plaintext is shifted by a specified number (`key`). For example, with a key of 3, `A` becomes `D`, `B` becomes `E`, and so on. The program handles both uppercase and lowercase letters, while non-alphabetic characters remain unchanged.

### Decryption
Decryption reverses the process of encryption by shifting each letter in the ciphertext back by the same number (`key`). This restores the original plaintext.

## Usage

1. Clone the repository to your local machine.
2. Compile the code using a C++ compiler (e.g., `g++`):
   ```bash
   g++ -o caesar_cipher caesar_cipher.cpp
Run the compiled program:
bash
Sao chép mã
./caesar_cipher
Follow the on-screen instructions to either encrypt or decrypt a text.
Code Explanation
encrypt(text, key): Encrypts the input text using the Caesar Cipher with the provided key.
decrypt(text, key): Decrypts the input text using the Caesar Cipher with the provided key.
printCaesarCipherTable(): Prints the Caesar Cipher alphabet mapping.
printTransformationTable(text, key, isEncrypt): Prints the transformation of each character in the text during encryption or decryption.
Example
Here is an example of how the program works:

mathematica
Sao chép mã
---MA HOA CAESAR---

Caesar Cipher Alphabet Mapping
Plain Text:  A B C D E F G H I J K L M N O P Q R S T U V W X Y Z 
Cipher Text: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z 

  1. Ma Hoa
  2. Giai Ma
  3. Exit
Nhap lua chon[1-3]: 1

___MA HOA___

Nhap text can ma hoa: HELLO WORLD
Shift[1-26]: 3

Key: 3
H:(7)  -->  K:(10)
E:(4)  -->  H:(7)
L:(11) -->  O:(14)
L:(11) -->  O:(14)
O:(14) -->  R:(17)
 :( )  -->   :( )
W:(22) -->  Z:(25)
O:(14) -->  R:(17)
R:(17) -->  U:(20)
L:(11) -->  O:(14)
D:(3)  -->  G:(6)

Cipher: KHOOR ZRUOG
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your improvements. Suggestions, bug reports, and feature requests are welcome!
