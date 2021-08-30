# DLSegBench
Benchmarking deep learning based cell segmentation 

## Project description
Image segmentation is a cornerstone of quantitative image analysis in biomedical applications. Recently, deep learning
has become the de-facto standard technology. While supervised deep learning yields the best accuracy for accurately labeled datasets, also unsupervised deep learning has a niche if labels are not available or inaccurate. 

Deep learning based image segmentation is implemented in numerous open source and commercial software package. In the context of microbial population biology, which is our research field, most available implementations are trained on Escherichia coli or Bacillus subtilis cells. For our model organism, Pseudomonas fluorescens strain SBW25, neither training datasets, nor pre-trained models are available. Therefore, we face the problem of comparing selected implementations and identify the implementation that works best for our data.

The following is a list of image segmentation codes that we whish to compare (maybe not all of them??)

1. SuperSegger
2. SchnitCell
3. Orbit
4. CellProfiler
5. QuPath

In a first step, we will curate a training dataset using recently obtained fluorescens microscopy timeseries of growing
bacteria cultures.

