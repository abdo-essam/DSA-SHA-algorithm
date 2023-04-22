# Elliptic-Curves

# Faculty Of Computer And Artificial Intelligence Cairo University `FCAI-CU`

## Cyber Security Assignment

# DSA-SHA-algorithm
The DSA-SHA algorithm is a cryptographic algorithm used for digital signatures, which is based on the SHA-1 hash function. The program includes methods to convert hexadecimal to binary and vice versa, generate message chunks, left rotate, and hash.


The hextoBin method converts a hexadecimal string input to binary. The binToHex method converts a binary string input to hexadecimal. The generate_chunk method takes a string input and returns an integer array that represents the message chunk used in the SHA-1 hash function. The leftrotate method takes an integer input x and shifts it to the left by shift bits. The hash method takes an integer array input x, extends it into eighty 32-bit words, and returns the SHA-1 hash of the input.

The program also includes some instance variables, such as h1, h2, h3, h4, and h5, which represent the initial values for the five hash variables used in the SHA-1 hash function. The variables k1, k2, k3, and k4 represent the constant values used in the SHA-1 hash function.

Overall, this program can be used to implement the DSA-SHA algorithm for digital signatures in Java.
