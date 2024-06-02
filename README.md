# File Compression Project

## Introduction
This repository contains the code for a file compression project. The project includes implementations of various compression algorithms such as Huffman coding.

## Files
- `encode.cpp`: Contains the implementation of the encoding process.
- `decode.cpp`: Contains the implementation of the decoding process.
- `huffman.cpp`: Includes the Huffman coding algorithm.
- `huffman.hpp`: Header file for the Huffman coding implementation.
- `inputFile.txt`: Sample input file for testing compression.

## How to run this project?
To run this project you need to create an executable file. You can follow the steps given below:
### 1) For compressing:
These two commands for compressing: 

First use this command: 
### g++ encode.cpp huffman.cpp -o main 
And then use this second command:
### ./main inputFile.txt compressedFile.huf


### 2) For Decompressing:
These two commands for decompressing:

First use this command:
### g++ decode.cpp huffman.cpp -o main 
And then use this second command:
### ./main compressedFile.huf OutPutFile.txt

## For More Help:
[View Sample Folder](Samples)
