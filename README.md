# Learning-from-web-data
Leveraging the abundant number of web data is a promising strategy in addressing the problem of data lacking when training convolutional neural networks (CNNs). However, web images often contain incorrect tags, which may compromise the learned CNN model. On the other hand, different data distribution between web and well-labled dataset (called dataset bias or build-in gap) also influence the effectiveness of using web data. To address these problems, we propose two methods that focus on cleaning noisy web data and reducing dataset bias, respectively. Meanwhile, we collect 0.5 million web images covering all categories of four public image classification datasets (SD-198, Stanford Dogs, Food-101 and MIT Indoor67) to support the related research.

****
## Datasets
We crawl web images from Google Images, Flickr and Twitter, respectively. <br>

<div align="center">
<img src="https://github.com/sxzrt/Learning-from-web-data/blob/master/images/statistic.jpg"  width="495">  
</div>

In the downloading process, We first collect images by keyword search, where keywords correspond to the category labels in the public datasets. Then, we download images from the search results for the given class. To ensure fair comparisons, Web images are near duplicates of the images in the validation or the test sets



The dataset can be downloaded from the following links:<br>
[Baidu Disk](https://pan.baidu.com/s/1vJWXM-SN7p5QttZZ_nzqQA)


****
## Our Works
### (1) Recognition from Web Data: A Progressive Filtering Approach (TIP 2018)
In this paper, we present a novel progressive filtering method that effectively exploits web images for various image classification tasks. Moreover, a one-to-many label assignment strategy is employed for data correction based on the confidence values of labels and the tags of images. The method performs well in a variety of image classification tasks.

<div align="center">
<img src="https://github.com/sxzrt/Learning-from-web-data/blob/master/images/progressive-l.jpg">  
</div>




****
### (2) Learning from Web Data using Adversarial Discriminative Neural Networks for Fine-Grained Classification (AAAI 2019)
In this work, we firstly show that there exists a gap between the web and the standard datasets, which will inhibit the training of parameters in convolutional layers when both of them are utilized. To address this problem, we present a novel multi-task learning framework that effectively exploits web images for various fine-grained classification tasks. An adversarial discriminative loss is proposed to advocate representation coherence between standard and web data.


**** 
If you use this dataset in your research, please kindly cite our work as, <br>
```
@article{yang2018recognition,
  title={Recognition from Web data: A progressive filtering approach},
  author={Yang, Jufeng and Sun, Xiaoxiao and Lai, Yu-Kun and Zheng, Liang and Cheng, Ming-Ming},
  journal={IEEE Transactions on Image Processing},
  volume={27},
  number={11},
  pages={5303--5315},
  year={2018}
}

```
