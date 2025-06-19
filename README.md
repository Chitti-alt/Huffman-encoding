
# Huffman Encoding: Pinnacle of Text Compression

This project implements the **Huffman Coding** algorithm in C++ to demonstrate lossless text compression. Huffman Coding is a popular greedy algorithm used to minimize the average code length for a set of symbols, thereby achieving efficient data compression.

## 🔧 Features

- Computes character frequencies in input text
- Constructs a binary Huffman tree based on frequencies
- Generates optimal prefix Huffman codes
- Compresses the input text using the generated codes
- Saves the compressed data and codebook to files
- Decodes the compressed text back to original form

## 📂 File Structure

- `HuffmanEncoding.cpp`: Main source file implementing encoding and decoding
- `input.txt`: Sample input text file
- `encoded.txt`: Output file containing compressed binary string
- `decoded.txt`: Output file with the decompressed original text
- `codes.txt`: File listing Huffman codes for each character

## 🚀 How to Run

1. Compile the program:
   ```bash
   g++ HuffmanEncoding.cpp -o huffman
