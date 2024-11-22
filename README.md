
File Compression Using Huffman Encoding
Overview
This project implements a file compression and decompression system using the Huffman Encoding algorithm. 
It reduces the size of text files by encoding characters based on their frequency, ensuring efficient data representation.

Features
Compression: Converts input text into a compressed binary format using Huffman codes.
Decompression: Reconstructs the original text from the compressed binary file.
Handles variable-length character encoding based on frequency.
Works efficiently with plain text files.
Outputs a compressed binary file and a decompressed text file.
Technologies Used
How It Works:
Character Frequency Analysis:
Reads a text file to calculate the frequency of each character.
Huffman Tree Construction:
Builds a binary tree where frequent characters are closer to the root.
Code Generation:
Assigns binary codes to characters based on tree traversal.
Compression:
Encodes the input text using Huffman codes and writes it to a binary file.
Decompression:
Reads the binary file, reconstructs the Huffman tree, and decodes the text.
