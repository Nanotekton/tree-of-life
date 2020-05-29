## example scripts which ilustrate how to works with tree-of-life data

getSmilesAndMass.py - the simplest example how to extract smiles and molecular weight

nxCycleSearch.py - load tree-of-life as graph using networkx library. The simples but not the most efficient way to work with graph.

gtCycleShortLenMultiproc.py - load tree-of-life as graph using graph_tool and search for cycles using multiprocesses. This is efficient was to search for cycles using all cores of your machine. 
Unfortunatelly installation of graph-tool can be more problematic (it cannot be done with pip) for details see https://git.skewed.de/count0/graph-tool/-/wikis/installation-instructions
