# XKCDColors-Dataset
A balanced dataset of color names and RGB values for training classifiers.
This data can be used to reproduce the results of our work in [Color inference from semantic labeling for person search in videos](https://arxiv.org/abs/1911.13114).

## Download
Dropbox [link](https://www.dropbox.com/s/pbkenpyreava3e3/XKCDcolors_balanced.zip?dl=0)

## Details
This dataset is built using the data gathered by Randall Muntroe through his [color survey](https://blog.xkcd.com/2010/05/03/color-survey-results/).

An additional processing is applied to obtain the dataset:
- Filtering outliers and labels with less than 2000 occurences
- Balancing the samples using SMOTE [1]


# References
[1] - Chawla, N. V. et al. “SMOTE: Synthetic Minority Over-Sampling Technique.” Journal of Artificial Intelligence Research 16 (2002): 321–357. Crossref. Web.

