Execute example: python 759finalnew.py -l=10 -a=200 -g=rand DFG_s50_5.edgelist
Where l in the latency constraint, a is the memory constraint, g is the testbench file address (edgelist format)
** GLPK package should be installed before execution (recommended: anaconda installation)**

The program will return the min latency and min memory consumption based on solving MRLC and MLRC problem
