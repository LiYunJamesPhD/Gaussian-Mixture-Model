# Gaussian-Mixture-Model

This implemenation consists of two clustering algorithms: K-means and Gaussian Mixture Model (GMM).

# Usage
1. K-means
To compile the K-mean implementation, please use the following command: /
clang++ -std=c++11 -stdlib=libc++ main.cpp Kmeans.cpp (Please make sure that you have c++11 or later compiler in your computer)

To run the implementation, you can run:
./a.out training_kmeans 10 5 [0 | 1], where
The second argument is centroid numbers (K values) 
The third argument is repeated numbers (run the program multiple times)
The last argument is the mode of dealing with an empty cluster. 0 is to re-assign a new centroid with the maximum SSE. 1 is randomly to re-assign a new centroid.

2. GMM
To run the GMM implementation, please use the command
pythons main.py [kmean | gmm]
