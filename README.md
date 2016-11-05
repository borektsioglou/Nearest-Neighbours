# Nearest-Neighbours
This is a nearest neighbours implementation using Locality Sensitive Hashing (LSH). Given a query point, the algorithms finds a set of point in a certain radius.
## Compiling and running

To compile type `make`:

    $ make 

Input parameter and obstacle files are all specified on the command line of the `main` executable.

Usage:

    $ ./main -d <inputFile> -o <outputFile> -q <queryFile>
eg:

    $ ./main -d dataEuclidean.csv -o myOutputFile -q QueryEuclidean.csv
    
The metric space has to be the same in input and query file
