# DNA-Alignment-
Sequence Alignment for DNA Comparison
Introduction
This project implements a dynamic programming/divide-and-conquer algorithm for computing the optimal alignment midpoint of two DNA sequences. The algorithm is particularly useful for comparing DNA sequences to identify differences between them. The assignment involves developing a computer program capable of efficiently computing the optimal alignment midpoint.

Project Structure
The project consists of the following class:

Alignment Class (Alignment.java):
Implements the dynamic programming/divide-and-conquer algorithm for computing the optimal alignment midpoint.
Computes the cost matrix in reverse order and produces the alignment using a forward order traceback.
Provides methods to retrieve information about the alignment, sequences, and matrix.
Usage
The primary usage of this project is to create an instance of the Alignment class, providing two DNA sequences and the alignment parameters. The example main method in Alignment.java demonstrates how to use the class for a small DNA sequence comparison.

Example Output
The example output showcases the alignment of two short DNA sequences, providing details such as match score, mismatch penalty, gap penalty, edit distance, number of differences, and the length of the alignment. Additionally, it displays the top, middle, and bottom rows of the alignment, the midpoint indices, and the minimum column-wise sum.

Running the Example
To run the example, execute the main method in the Alignment class. The provided output demonstrates the alignment process and showcases the results of the computation.

Conclusion
This project provides a comprehensive implementation of a sequence alignment algorithm for DNA comparison. The code is accompanied by detailed comments for better understanding. Feel free to explore and modify the code to suit your specific needs. If you have any questions or encounter issues, please refer to the comments and documentation or reach out for assistance.
