# Data-Compression-using-Huffman-s-Coding


This project's purpose is to build a data compression method.That is, we want to convey the same information in a smaller amount of space given particular data. We'll be concentrating on compressing text files for this project.

One of the most important lossless data compression algorithms is called **Huffman coding.**

The algorithm uses a priority queue. First you need to calculate the frequency of each symbol in the input. It Make a leaf node for each symbol and store its frequency in the node. Repeatedly do the following, find the two trees with the smallest frequencies. Make them the left and right children of a new node whose frequency the sum of the two frequencies. 


# Programming Language
C++

# How to run
1. Update **src.txt** to text of your own.
2. Build and Run **DataCompression_.cpp**.


# Output:
The Output of Code will be : 

1. Frequency of every character, Binary Tree , Variable length codes , Compression Ratio
2. Frequency of every character, Optimal Huffman Tree , Variable length codes , Compression Ratio  
