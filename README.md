# QLDecN
 We propose a SAR Radio Frequency interference detection network (QLDecN) combined with statistical histogram characteristics to detect the distribution of unintentional interference in the quick-looks (i.e. preview images) of Sentinel-1 SLC products.
## Dataset
We selected 50 SLC product preview images from the Sentinel website, and used data augmentation methods such as cropping and flipping to cut into smaller slices and resize them to 256*256. The dataset contains 7580 images in each of two categories, which are divided into training and testing sets in a 4:1 ratio. This dataset can be used for training and validation of the QLDecN model.

This dataset can also be used to train other classification models to determine whether there is RF interference.

* The download link  
BaiduNetdisk： https://pan.baidu.com/s/1zFyh43VeFZtJXs6fc7CCNQ  Password: 6bj9

## Cite
If you want to use this dataset or use QLDecN as contrast model, please cite as follows:
>Shen J, Han B, Li Y, Pan Z, Yin D, Feng Y, Li G. A Radio Frequency Interference Screening Framework—From Quick-Look Detection Using Statistics-Assisted Network to Raw Echo Tracing. Remote Sensing. 2024; 16(22):4195. https://doi.org/10.3390/rs16224195.
