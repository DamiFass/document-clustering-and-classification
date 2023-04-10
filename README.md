# Document Clustering And Classification

This repo contains notebooks performing clustering and classification on documents from the [FUNSD dataset](https://guillaumejaume.github.io/FUNSD/dataset.zip)

The first notebook implements K-means and agglomerative clustering on the FUNSD dataset using visual and textual
features, as well as Principant Component Analysis on the tokenized content of the documents for clusters visualization purposes.

The second notebook implements supervised classification by performing transfer learning on the VGG architecture, using the
labels learned through clustering.

These notebooks make use of _Scikit-learn_ and _keras_ libraries. 
