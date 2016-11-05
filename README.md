# Nearest-Neighbours
This is a nearest neighbours implementation using Locality Sensitive Hashing (LSH). Given a query point, the algorithms finds a set of point in a certain radius.
## Compiling and running

To compile type `make`. Editing the values for `CC` and `CFLAGS` in the Makefile can be used to enable different compiler options or use a different compiler. These can also be passed on the command line:

    $ make CFLAGS="-O3 -fopenmp -DDEBUG"

Input parameter and obstacle files are all specified on the command line of the `d2q9-bgk.exe` executable.

Usage:

    $ ./main -d <inputFile> -o <outputFile> -q <queryFile>
eg:

    $ ./main -d dataEuclidean.csv -o myOutputFile -q QueryEuclidean.csv
    
The metric space has to be the same in input and query file
