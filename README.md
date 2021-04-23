# RNA-folding
An RNA secondary structure prediction algorithm 


This algorithm finds all optimal secondary structures of the RNA sequence AAUACUCCGUUGCAGCAU with the following simplified Zuker minimization algorithm. The following initialisation is used:

    j + 5 > i => V(i, j) = W(i, j) = ∞


hairpin energy:  

        h(i, j) = 2 * (i - j + 5)

and stem energy:

        s(i, j) = -4, 0, 4 for Watson-Crick bonds, GU, and all other possible pairs respectively.

Multiloops and buldges are ignored to simplify V so that it only has the first two
cases.
  
  
In the `/output` folder you can find the filled-in tables W - V , an optimal fold, its bonds, and the corresponding backtrack path.

