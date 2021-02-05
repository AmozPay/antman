# antman
Basic file compression and decompression, using Huffman's algorithm

Quick start:
Run the `make` command in the root folder of the project, then `make clean` to remove temporary files.


Antman: Compress a file
Giantman: Decompress a file

The compiled programs are found respectively in the 'antman' and 'giantman' folders.


The algorithm works mainly on files containing text, such as html, but could work on other types as well.


Syntax: ./antman file compression
compression: a number between 1 and 3 (to indicate either an .html, .lyr or .ppm file). Since the algorithm works on any of these file types, the input number doesn't matter.

        ./giantman file decompression
Decompression number doesn't have to match compression's.