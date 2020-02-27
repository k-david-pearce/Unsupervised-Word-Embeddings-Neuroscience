## Unsupervised-Word-Embeddings-Neuroscience-Abstracts
Word vector representations scraped from neuroscience abstracts using the text2vec package in R.

## Methods ##

1. I used Columbia CLIO to search for academic articles related to the human limbic system, quantum effects in the brain, and artificial intelligence. 
2. Rather than use 'big data' to analyze millions of abstracts, I chose to find word associations between five articles, listed below.
---
## References ##

1. Okihide Hikosaka; Susan R. Sesack; Lucas Lecourtier; and Paul D. Shepard (2008). Habenula: Crossroad between the Basal Ganglia and the Limbic System. Journal of Neuroscience 28(46), 11825-11829.

2. Rolls, E. (2015). Limbic systems for emotion and for memory, but no single limbic system. Cortex 62, 119-157.

3. M.W. Swift, M.P.A. Fisher and C.G. Van de Walle (2018). Posner Molecules: From atomic structure to nuclear spins”, Journal of Phys Chem Chem Phys, 20, 12373-12380.

4. C.P. Weingarten, P.M. Doraiswamy and M.P.A. Fisher (2016). A new spin on neural processing: Quantum cognition, , Frontiers in Human Neuroscience 10, 541. 

5. Brenden M. Lake, Tomer D. Ullman, Joshua B. Tenenbaum, Samuel J. Gershman (2017). Building machines that learn and think like people.
Behavioral and Brain Sciences, 40.

---

This project was inspired by the following paper: 

Tshitoyan, V., Dagdelen, J., Weston, L., Dunn, A., Rong, Z., Kononova, O., Persson, K., Ceder, G., Jain, A. (2019). Unsupervised word embeddings capture latent knowledge from materials science literature. 
Nature, 571, 95–98. DOI: 10.1038/s41586-019-1335-8

---
I used the 'Text2Vec' implementation of GloVe Word Embeddings by Dmitriy Selivanov.
https://cran.r-project.org/web/packages/text2vec/vignettes/glove.html
