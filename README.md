# Deep Learning
> This repository is an ensemble of different kinds of applications implemented using Tensorflow and Keras. A very good guide for beginners. The following table gives a overview(besides the name) of what different folder contains.

#### **_Table of contents_**:
| Folders        | Descriptions       |
| :-------------: |:-------------|
|DeepNetBasic| Low level implementation of shallow/basic feed forward network to perdom classification task on MNIST dataset using custom training loop.| 
|DenseNet| Implementation of DenseNET network to perform classification task on CIFAR10 dataset, and experiments with different hyper-parameters.|
|ExperimentsWithOptimizers| Experiments with different regularizer choices(and different parameters) and their impact on model training.|
|ExperimentsWithRegularizers| Experiments with different optimizer choices(and different parameters) and their impact on model training.|
|Autoencoder_basic| Basic Autoencoder implementation to reconstruct the MNIST dataset digits. The notebook also contains an small experiment of walking the code(latent) space.|
| CatsVsDogs|Binary classification between cats and dogs images from Kaggle dogs-vs-cats dataset, using RESNET architecture. The model is inspired from Coursera course. |
| HandGestureDigitRecog| Classification of digits from images, where digits are shown by hand gesture, using LENET model.|
| Titanic - Kaggle | Binary classification task performed on Titanic dataset from Kaggle using (not so deep) Dense model using Keras. Good example for ultimate starters.|
|RNN_LowLevel| Low level implementation of RNN basic concepts for character level data generation.|
|LSTM| Implementation of RNN using LSTM(Tensorflwo) for character level sequence generation. The model is capable of taking variable length input sequence.| 
|NMTWithAttention|Attention based Neural Machine Translation(NMT) implemented to translate from bengali to english. This notebook implements and compare three different attention mechanisms- Bahdanau, Dot-product & Luong product. |
|ObjectDetectionInImage_YOLOv3| Object detection task perform using YOLOv3 model on images. Code and model are inspired by Coursera course.|
|ObjectDetectionInVideo_YOLOv3| Object detection task perform using YOLOv3 model on video frames. Code and model are inspired by Coursera course.|
|TransferLearning|This notebook shows implementation of different transfer learning strategies and their comparison.|
|BERTFineTuning|A BERT model is fine-tuned with a binary classification task of finding grammatical correctness of a sentence. This implementation uses 'glue-CoLA' dataset.|
|VAE|This notebook contains implementation of a basic Variational Autoencoder(VAE) on MNIST dataset.|
|ImprovedGAN_WGAN|Implementation of Wasserstein GAN(WGAN) and WGAN with Gradient Penalty(WGAN-GP) to generate new images for FMNIST dataset.|


###### **_Note:_**  
Some of the implementations/experminets are inspired by some blogs. You can find relevant links in the notebooks itself.

---

#### Citation:

>If this repository helps you or you use some of its code, please refer the following archive as citation in your codes/publications.

[![DOI](https://zenodo.org/badge/333051227.svg)](https://zenodo.org/badge/latestdoi/333051227)

#### Contact:
For any issues, clarification, bug or improvement suggestion, please send an email to **arnabdas8901@gmail.com**. I will reach back as soon as possible.

