# Awesome Dimensionality Reduction [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

*Last updated 19.02.2025.*

**WARNING: This list is still new and under construction! It still contains incomplete and potentially incorrect information. So use with caution.**

## Contents


## Surveys

| Year | Authors | Title | Venue | Methods Covered | Publication Link |
|---|---|---|---|---|---|
| 2002 | Fodor, Imola K. | A survey of dimension reduction techniques | Lawrence Livermore National Lab | 12 methods | [Link](https://computing.llnl.gov/sites/default/files/148494.pdf) |
| 2009 | Van Der Maaten, Laurens, Eric O. Postma, and H. Jaap Van Den Herik | Dimensionality reduction: A comparative review | Journal of machine learning research | 14 methods | [Link](https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf) |
| 2014 | Sorzano, Carlos Oscar Sánchez, Javier Vargas, and A. Pascual Montano | A survey of dimensionality reduction techniques | arXiv preprint | 19 methods | [Link](https://arxiv.org/pdf/1403.2877) |
| 2019 | Espadoto, Mateus, et al. | Toward a quantitative survey of dimension reduction techniques | IEEE transactions on visualization and computer graphics | 44 methods | [Link](https://cs.lnu.se/isovis/pubs/docs/espadoto-tvcg19-postprint.pdf) |
| 2020 | S Ayesha, MK Hanif, R Talib | Overview and comparative study of dimensionality reduction techniques for high dimensional data | Information Fusion | PCA, t-SNE, LDA, AE, UMAP | [Link](https://www.sciencedirect.com/science/article/pii/S156625351930377X?casa_token=Fg530QgbktwAAAAA:6YpIkG67tJh4-GN2RHWh2z35BJVS9tR-IXgRAgAGa7uim5guJ_-1yBl22e2XwoL3-x4fwK4TJx8) |


## Methods

| Year | Authors | Title | Venue | Method Abbreviation | Publication Link | Code Link |
|---|---|---|---|---|---|---|
| 1901 | Pearson, Karl | LIII. On lines and planes of closest fit to systems of points in space | The London, Edinburgh, and Dublin philosophical magazine and journal of science | PCA | [Link](https://zenodo.org/records/1430636) | [Code](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) |
| 1933 | Hotelling, Harold | Analysis of a complex of statistical variables into principal components | Journal of educational psychology | 
| 1978 | Kruskal, Joseph B., and Myron Wish | Multidimensional scaling | Sage | MDS | [Link](http://cda.psych.uiuc.edu/psychometrika_highly_cited_articles/kruskal_1964a.pdf) | [Code](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.MDS.html) | PCA | [Link](https://www.cis.rit.edu/~rlepci/Erho/Derek/Useful_References/Principal%20Components%20Analysis/Hotelling_PCA_part1.pdf) | [Code](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) |
| 1989 | Hastie, Trevor, and Werner Stuetzle | Principal curves | Journal of the American Statistical Association |  | [Link](https://www.jstor.org/stable/pdf/2289936.pdf?casa_token=6sFhtVSOR7MAAAAA:ktIEV6D1r2OzPGkbaqcgn1qQKN7s489dn6LiE8QtN1AjtGV5aIsVftXN7ByxTYKlXsqvupFxZ1xK1vtYI7GJ88jDeK8o1xtgtw_9_WBBRTEtSP8YffSd) | [Code](https://github.com/artusoma/prinPy) |
| 1997 | Schölkopf, Bernhard, Alexander Smola, and Klaus-Robert Müller | Kernel principal component analysis | International Conference on Artificial Neural Networks | KPCA | [Link](https://link.springer.com/chapter/10.1007/BFb0020217) | [Code](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.KernelPCA.html#sklearn.decomposition.KernelPCA) | 
| 1997 | Tenenbaum, Joshua | Mapping a manifold of perceptual observations | Advances in Neural Information Processing Systems |  | [Link](https://papers.nips.cc/paper_files/paper/1997/hash/28e209b61a52482a0ae1cb9f5959c792-Abstract.html) | |
| 1999 | Tipping, Michael E., and Christopher M. Bishop | Probabilistic principal component analysis | Journal of the Royal Statistical Society Series B: Statistical Methodology | PPCA | [Link](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/1467-9868.00196) | [Code](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) | 
| 2000 | Hyvärinen, Aapo, and Erkki Oja | Independent component analysis: algorithms and applications | Neural Networks | ICA | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0893608000000265) | [Code](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.FastICA.html#sklearn.decomposition.FastICA) |
| 2000 | Tipping, Michael | Sparse kernel principal component analysis | Advances in Neural Information Processing Systems | SKPCA | [Link](https://proceedings.neurips.cc/paper_files/paper/2000/file/bf201d5407a6509fa536afc4b380577e-Paper.pdf) | todo |
| 2000 | Tenenbaum, Joshua B., Vin de Silva, and John C. Langford | A global geometric framework for nonlinear dimensionality reduction | Science | Isomap | [Link](https://science.sciencemag.org/content/290/5500/2319) | todo |
| 2002 | Hinton, Geoffrey E., and Sam Roweis | Stochastic neighbor embedding | Advances in Neural Information Processing Systems | SNE | [Link](https://www.cs.toronto.edu/~fritz/absps/sne.pdf) | todo |
| 2003 | Zhang, Zhenyue, and Hongyuan Zha | Nonlinear dimension reduction via local tangent space alignment | International Conference on Intelligent Data Engineering and Automated Learning | LTSA | [Link](https://arxiv.org/abs/cs/0212008) | todo |
| 2006 | Sammon, John W. | A nonlinear mapping for data structure analysis | IEEE Transactions on Computers | Sammon Mapping | [Link](https://ieeexplore.ieee.org/document/1671271) | todo |
| 2006 | Yu, Shipeng, et al. | Supervised probabilistic principal component analysis | Proceedings of the 12th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining | SPPCA | [Link](https://is.mpg.de/fileadmin/user_upload/files/publications/sppca_kdd2006_4069[0].pdf) | todo |
| 2007 | Choi, Heeyoul, and Seungjin Choi | Robust kernel isomap | Pattern Recognition | RKI | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0031320306001804) | todo |
| 2007 | Hoffmann, Heiko | Kernel PCA for novelty detection | Pattern Recognition | KPCA | [Link](https://heikohoffmann.de/documents/hoffmann_kpca_preprint.pdf) | todo |
| 2008 | Van der Maaten, Laurens, and Geoffrey Hinton | Visualizing data using t-SNE | Journal of Machine Learning Research | t-SNE | [Link](https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf) | todo |
| 2009 | Van Der Maaten, Laurens | Learning a parametric embedding by preserving local structure | Artificial Intelligence and Statistics |  | [Link](http://proceedings.mlr.press/v5/maaten09a/maaten09a.pdf) | todo |
| 2010 | Venna, Jarkko, et al. | Information retrieval perspective to nonlinear dimensionality reduction for data visualization | Journal of Machine Learning Research |  | [Link](https://www.jmlr.org/papers/v11/venna10a.html) | todo |
| 2010 | Yang, Zhirong, Chiwei Wang, and Erkki Oja | Multiplicative updates for t-SNE | IEEE International Workshop on Machine Learning for Signal Processing | t-SNE | [Link](https://ieeexplore.ieee.org/document/5589527) | todo |
| 2012 | Van der Maaten, Laurens, and Geoffrey Hinton | Visualizing non-metric similarities in multiple maps | Machine Learning |  | [Link](https://link.springer.com/article/10.1007/s10994-011-5273-4) | todo |
| 2013 | Amir, El-ad David, et al. | viSNE enables visualization of high dimensional single-cell data and reveals phenotypic heterogeneity of leukemia | Nature Biotechnology | viSNE | [Link](https://www.nature.com/articles/nbt.2594) | todo |
| 2014 | Van Der Maaten, Laurens | Accelerating t-SNE using tree-based algorithms | The Journal of Machine Learning Research | t-SNE | [Link](https://jmlr.org/papers/v15/vandermaaten14a.html) | todo |
| 2016 | Wei, Chihang, Junghui Chen, and Zhihuan Song | Developments of two supervised maximum variance unfolding algorithms for process classification | Chemometrics and Intelligent Laboratory Systems | SMVU | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0169743916303409) | todo |
| 2018 | McInnes, Leland, John Healy, and James Melville | Umap: Uniform manifold approximation and projection for dimension reduction | arXiv preprint arXiv:1802.03426 | UMAP | [Link](https://arxiv.org/abs/1802.03426) | todo |
| 2019 | Amid, Ehsan, and Manfred K. Warmuth | TriMap: Large-scale dimensionality reduction using triplets | arXiv preprint arXiv:1910.00204 | TriMap | [Link](https://arxiv.org/abs/1910.00204) | todo |
| 2019 | Linderman, George C., et al. | Fast interpolation-based t-SNE for improved visualization of single-cell RNA-seq data | Nature Methods | t-SNE | [Link](https://pubmed.ncbi.nlm.nih.gov/30742040/) | todo |
| 2020 | Ghojogh, Benyamin, et al. | Multidimensional scaling, sammon mapping, and isomap: Tutorial and survey | arXiv preprint arXiv:2009.08136 | MDS, Sammon Mapping, Isomap | [Link](https://arxiv.org/abs/2009.08136) | todo |
| 2021 | Damrich, Sebastian, and Fred A. Hamprecht | On UMAP's true loss function | Advances in Neural Information Processing Systems | UMAP | [Link](https://proceedings.neurips.cc/paper/2021/hash/2de5d16682c3c35007e4e92982f1a2ba-Abstract.html) | todo |
| 2021 | Narayan, Ashwin, Bonnie Berger, and Hyunghoon Cho | Assessing single-cell transcriptomic variability through density-preserving data visualization | Nature Biotechnology |  | [Link](https://pubmed.ncbi.nlm.nih.gov/33462509/) | todo |
| 2021 | Sainburg, Tim, Leland McInnes, and Timothy Q. Gentner | Parametric UMAP embeddings for representation and semisupervised learning | Neural Computation | UMAP | [Link](https://direct.mit.edu/neco/article-pdf/33/11/2881/1966656/neco_a_01434.pdf) | todo |
| 2021 | Wang, Yingfan, et al. | Understanding how dimension reduction tools work: an empirical approach to deciphering t-SNE, UMAP, TriMAP, and PaCMAP for data visualization | Journal of Machine Learning Research | t-SNE, UMAP, TriMAP, PaCMAP | [Link](https://jmlr.org/papers/volume22/20-1061/20-1061.pdf) | todo |
| 2022 | Damrich, Sebastian, et al. | From $ t $-SNE to UMAP with contrastive learning | arXiv preprint arXiv:2206.01816 | t-SNE, UMAP | [Link](https://arxiv.org/abs/2206.01816) | todo |
| 2022 | M. Saquib Sarfraz, Marios Koulakis, Constantin Seibold, Rainer Stiefelhagen | Hierarchical Nearest Neighbor Graph Embedding for Efficient Dimensionality Reduction | CVF Conference on Computer Vision and Pattern Recognition | h-NNE | [Link](https://openaccess.thecvf.com/content/CVPR2022/papers/Sarfraz_Hierarchical_Nearest_Neighbor_Graph_Embedding_for_Efficient_Dimensionality_Reduction_CVPR_2022_paper.pdf) |  todo |
| 2023 | Van Assel, Hugues, et al. | Snekhorn: Dimension reduction with symmetric entropic affinities | Advances in Neural Information Processing Systems | Snekhorn | [Link](https://arxiv.org/abs/2305.13797) | todo |
| 2024 | Wang, Yingfan, et al. | Dimension Reduction with Locally Adjusted Graphs | arXiv preprint arXiv:2412.15426 |  | [Link](https://arxiv.org/abs/2412.15426) | todo |
| 2024 | Yang, Deliang, and Hou-Duo Qi | Supervised maximum variance unfolding | Machine Learning | SMVU | [Link](https://link.springer.com/article/10.1007/s10994-024-06553-8) | todo |


## Frameworks and code


## Datasets

