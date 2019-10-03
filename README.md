# jadeR for Python
## Blind source separation of real signals

jadeR implements JADE, an Independent Component Analysis (ICA) algorithm
developed by Jean-Francois Cardoso. More information about JADE can be
found among others in: Cardoso, J. (1999) High-order contrasts for
independent component analysis. Neural Computation, 11(1): 157-192. Or
look at the website: http://www.tsi.enst.fr/~cardoso/guidesepsou.html

More information about ICA can be found among others in Hyvarinen A.,
Karhunen J., Oja E. (2001). Independent Component Analysis, Wiley. Or at the
website http://www.cis.hut.fi/aapo/papers/IJCNN99_tutorialweb/

The Python code here was translated into NumPy from the original Matlab Version
1.8 (May 2005) by Gabriel Beckers, http://gbeckers.nl . In the 1.9 version, 
two corrections were made by David Rivest-Hénault to make the code become 
equivalent at machine precision to that of jadeR.m, after which I put the
code on Github.