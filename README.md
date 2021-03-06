# DeepFLEX

## About

DeepFLEX is a semi-automated, deep learning-based pipeline for unsupervised single-cell analysis of MELC (Multi-Epitope Ligand Cartography) imaging data. The pipeline integrates methods for image processing and segmentation, feature extraction, normalization and single-cell analysis that were recently published by our group [1], [2] and other experts in the field [3], [4], [5]. 

[*Daria Lazic, Florian Kromp, Filip Mivalt, Fikret Rifatbegovic, Florian Halbritter, Inge Ambros, Peter Ambros, Christian Ostalecki, Sabine Taschner-Mandl*  
**Unraveling the landscape of bone marrow metastases in pediatric cancer at single cell resolution**](https://arxiv.org/)

![Semantic description of image](/deepflex.jpg "Image Title")  
    
**Contact:** Daria Lazic ([daria.lazic@ccri.at](mailto:daria.lazic@ccri.at))

## Content

A detailed description and demonstration on how to run the pipeline is provided in [run_deepflex.py](/run_deepflex.py).

## Data availability

Download the MELC imaging data of our 8 samples [here](https://cloud.stanna.at/sharing/gDdiRiSxs).

## Installation

In order to use DeepFLEX, you have to install:  
- CIDRE: a retrospective illumination correction method (download [here](https://github.com/smithk/cidre))
- Cytosplore: an interactive tool for single-cell analysis (download [here](https://www.cytosplore.org/))

## References

<a id="1">[[1]](https://arxiv.org/abs/1907.12975)</a> 
Kromp, F. et al. (2019). 
Deep Learning architectures for generalized immunofluorescence based nuclear image segmentation. 
arXiv.  
<a id="1">[[2]](https://www.nature.com/articles/s41597-020-00608-w)</a> 
Florian, K. et al. (2020). 
An annotated fluorescence image dataset for training nuclear segmentation methods. 
Scientific Data, 7, 262.  
<a id="1">[[3]](https://www.nature.com/articles/nmeth.3323)</a> 
Smith, K. et al. (2015). 
CIDRE: An illumination-correction method for optical microscopy. 
Nat. Methods, 12, 404-406.  
<a id="1">[[4]](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.20426)</a> 
Chang, Y.H. et al. (2020). 
RESTORE: Robust intEnSiTy nORmalization mEthod for multiplexed imaging. 
Commun. Biol., 3, 1-9.  
<a id="1">[[5]](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.12893)</a> 
Höllt, T. et al. (2016). 
Cytosplore: Interactive Immune Cell Phenotyping for Large Single-Cell Datasets. 
Comput. Graph., 35, 171-180.  