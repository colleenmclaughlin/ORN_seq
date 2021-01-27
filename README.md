# Single cell transcriptomes of developing and adult olfactory receptor neurons in Drosophila
Analysis of single-cell/nucleus transcriptomes of developing and adult olfactory receptor neurons from [McLaughlin et al., 2020](https://www.biorxiv.org/content/10.1101/2020.10.08.332130v1).

## Environment
This repository contains the Jupyter notebooks that were used to analyze to Drosophila olfactory receptor neurons (ORNs) at three different developmental stages. The analysis requires Python 3.7, [Scanpy](https://scanpy.readthedocs.io/en/stable/index.html), [anndata](https://anndata.readthedocs.io/en/latest/index.html), and [MARS](https://github.com/snap-stanford/mars).

## Data
Sequencing reads and pre-processed data are available in the NCBI Gene Expression Omnibus (GSE162121). Data used for analysis are also uploaded here. Data from all figures except Figure 2, have been pre-processed to keep only high-quality neurons that formed MARS clusters and the data were normalized via Log2(CPM+1) transformation. Projection neuron data [from Xie et al., 2020](https://www.biorxiv.org/content/10.1101/2020.09.24.312397v1) that was analyzed in Figure 2 can be found in GEO (GSE161228).
