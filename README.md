# RNA-folding
An RNA secondary structure prediction algorithm 


This algorithm finds all optimal secondary structures of the RNA sequence AAUACUCCGUUGCAGCAU with the following simplified Zuker minimization algorithm. The following initialisation is used:

![](https://cdn.mathpix.com/snip/images/QrRwm24e_uKi3866bQxc59Ybxh-NDgrNPXLqugmPi14.original.fullsize.png)

hairpin energy h(i; j) = 2(i 􀀀 j + 5), and stem energy s(i; j) = 􀀀4; 0; 4, for Watson-Crick bonds, GU, and all
other possible pairs respectively. Ignore multiloops and buldges to simplify V so that it only has the first two
cases.


Implement your algorithm in Matlab, R, Python or other convenient system; submit your code. Print the filled-in tables W; V . Draw (by hand) an optimal fold, show its bonds, and the corresponding backtrack path.
