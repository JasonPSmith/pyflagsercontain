# pyflagsercontain
A python wrapper for flagsercontain which computes the number of directed cliques each vertex of digraph belongs to

## Installation:
Download the repository and submodules with:
- git clone --recursive https://https://github.com/JasonPSmith/pyflagsercontain.git

Then, install with:
- pip install .

## Usage
In python load with:
- from pyflagsercontain import flagser_count

To get the clique counts of a graph call:
- cliquecontain = flagser_count(adj_matrix)

where adj_matrix is a numpy array of the adjacency matrix of the graph.

Then, cliquecontain[v][d] contains the number of simplices of dimension d which contain the vertex v.
