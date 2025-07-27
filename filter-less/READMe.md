# Filterless

A C program that applies image filters to BMP files. It supports multiple filters, including:

- Grayscale  
- Sepia  
- Reflect (horizontal flip)  
- Blur

This project focuses on manipulating pixel data without using external image libraries, reinforcing low-level memory handling and image processing fundamentals in C.

## How to Use

1. Compile the program using make.
2. Run the desired filter. Example:

   `bash
   ./filter -g input.bmp output.bmp    
Replace -g with:
-s for sepia
-r for reflect
-b for blur
