# Suite2p-Donuts

This neurofinder submission uses Donuts for series 00 and 03 (which, I believe, have been labelled based on anatomical factors only), and Suite2p for everything else. See the github pages and publications for the algorithms below. 

Suite2p has been run like before, while Donuts has been run with a generic 3-subspace model inferred from a dataset of GCaMP6 mean images (included by default with donuts). 

The number of cells in Donuts has been chosen to maximize the training set accuracies (300 for series 00 and 600 for series 03). 

Donuts, https://github.com/marius10p/donuts  
M Pachitariu, N Pettit, H Dagleish, A Packer, M Hausser & M Sahani (2013). Extracting regions of interest from biological images with convolutional sparse block coding. Advances in Neural Information Processing Systems (NIPS) 26.

Suite2p, https://github.com/cortex-lab/Suite2P  
M Pachitariu, C Stringer, S Schroder, M Dipoppa, LF Rossi, M Carandini & KD Harris (2016). Suite2p: beyond 10,000 neurons with standard two-photon microscopy. bioRxiv, doi:10.1101/061507.
