# Attention-based-Skin-Cancer-Classification

In clinical applications, neural networks must focus on and highlight the most important parts of an input image. Soft-Attention mechanism enables a neural network to achieve this goal. This paper investigates the effectiveness of Soft-Attention in deep neural architectures. The central aim of Soft-Attention is to boost the value of important features and suppress the noise-inducing features. We compare the performance of VGG, ResNet, Inception ResNetv2 and DenseNet architectures with and without the Soft-Attention mechanism, while classifying skin lesions. The original network when coupled with Soft-Attention outperforms the baseline by 4.7% while achieving a precision of 93.7% on HAM10000 dataset. Additionally, Soft-Attention coupling improves the sensitivity score by 3.8% compared to baseline and achieves 91.6% on ISIC-2017 dataset.

# Results
## Soft Attention maps of Skin lesion in Inception ResNet V2 on HAM10000 data
![alt text](https://github.com/skrantidatta/Attention-based-Skin-Cancer-Classification/blob/main/Images/QRESULT_HAM10000.jpg?raw=true)


# Datasets

**HAM10000  dataset**:

Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).Available: https://www.nature.com/articles/sdata2018161, https://arxiv.org/abs/1803.10417

**ISIC-2017 dataset**:

Codella N, Gutman D, Celebi ME, Helba B, Marchetti MA, Dusza S, Kalloo A, Liopyris K, Mishra N, Kittler H, Halpern A. "Skin Lesion Analysis Toward Melanoma Detection: A Challenge at the 2017 International Symposium on Biomedical Imaging (ISBI), Hosted by the International Skin Imaging Collaboration (ISIC)". arXiv: 1710.05006 [cs.CV] Available: https://arxiv.org/abs/1710.05006
