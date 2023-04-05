# RSA-implementation-with-GUI
This program is an implementation of the RSA algorithm for encryption and decryption of messages. The user interface is created using the Tkinter module in Python.

# How it works
-- The program takes two prime numbers p and q as input and calculates the private and public keys. The user can select whether to encrypt or decrypt a message by selecting a mode. Enter "e" for encryption and "d" for decryption.

-- The encryption process involves converting the message into its corresponding ASCII values, then raising each value to the power of the public key and taking the modulo of the product with the value of n (which is p*q). The resulting values are then concatenated with a comma separator and returned as the encrypted message.

-- The decryption process involves splitting the encrypted message into a list of integers separated by commas. For each integer, the value is raised to the power of the private key and the modulo of the result with n is taken. The resulting values are converted back into ASCII characters and concatenated to form the original message.

-- The program includes functions for checking whether a number is prime, finding the greatest common divisor using Extended Euclidean Algorithm, finding the multiplicative inverse, and setting the mode. The program also includes functions for resetting the input fields and exiting the program.

# Features
1. Encryption and decryption of messages using RSA algorithm
2. User interface created using Tkinter module in Python
3. Input validation for prime number selection
4. Checking whether a number is prime
5. Finding the greatest common divisor using Extended Euclidean Algorithm
6. Finding the multiplicative inverse
7. Resetting input fields
8. Exiting the program
# How to use
1. Run the program in a Python environment
2. Enter two prime numbers (p and q) in the input fields
3. Enter the message you want to encrypt or decrypt in the "Enter the message" field
4. Select the mode (encrypt or decrypt) by entering "e" for encryption or "d" for decryption
Click on the "Result" button to perform the corresponding operation
# Encrypt
![Encrypt](https://user-images.githubusercontent.com/49710798/230009230-a86a9c94-1eeb-4dec-9830-103a144a4667.jpg)
# Decrypt
![Decrypt](https://user-images.githubusercontent.com/49710798/230009264-d3c71a66-74cd-4383-8d6b-e1babd7c24f8.jpg)


# Dependencies
This program requires the following dependencies:

1. Python 3.x
2. Tkinter module
# Acknowledgements
This program was created by Dejene Biniyam Gashaw as part of the Network Security course.




