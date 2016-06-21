# VIBIKNet
This repository contains the code for the Visual Bidirectional Kernelized Network for Visual Question Answering,
presented to the [VQA Challenge](http://visualqa.org/challenge.html) at CVPR'16. 
With this module, you can replicate our experiments and easily deploy new models. VIBIKNet is built upon the 
[Keras](https://github.com/fchollet/keras) framework and tested for the [Theano](http://deeplearning.net/software/theano)
backend.

Code available soon.

## Installation

VIBIKNet requires the following libraries:

 - [Our version of Keras](https://github.com/MarcBS/keras) v1.0.4 or newer
 - [Staged Keras Wrapper](https://github.com/MarcBS/staged_keras_wrapper) v0.1 or newer
 - [VQA challenge evaluation scripts](https://github.com/lvapeab/coco-caption/tree/master/pycocoevalcap/vqa)

Additionally, if you want to run the tutorials and the visualization module, you'll need:

  - [Jupyter Notebook](http://jupyter.readthedocs.io)
  - [Matplotlib](http://matplotlib.org)
 
If you want to extract KCNN features you will need (see /repository_root/features_extraction/KCNN/README.md for more info):

 - [Matlab](http://es.mathworks.com/products/matlab/) 2014a or newer or [Octave](https://www.gnu.org/software/octave/download.html)
 - [Caffe](https://github.com/BVLC/caffe). Download into ~/code/caffe folder or change path in extractCNNfeatures.m
 - [EdgeBoxes](https://github.com/pdollar/edges) object detection. Download into /repository_root/edges folder.
 - [Piotr Dollar toolbox](https://github.com/pdollar/toolbox). Download into /repository_root/piotr_toolbox folder.
 - [Inria's Yael library](https://gforge.inria.fr/projects/yael/) for Matlab. Download into /repository_root/yael folder and compile for you system. See yael's release notes for more information.

If you want to use GLOVE word embedding:


## How to use
 
 - For training a new model, follow the [train](ttps://github.com/MarcBS/VIBIKNet/tutorials/train.ipynb) notebook.
 - For using a trained model, follow the [visualize_results](ttps://github.com/MarcBS/VIBIKNet/tutorials/visualize_results.ipynb) notebook.
 

## Examples

These answers have been automatically generated by VIBIKNet:

![Examples](./docs/examples.png)

## About

Joint collaboration between the [Computer Vision at the University of Barcelona (CVUB)](http://www.ub.edu/cvub/) group at [Universitat de Barcelona](www.ub.edu)-[CVC](http://www.cvc.uab.es) and the [PRHLT Research Center](https://www.prhlt.upv.es) at [Universitat Politècnica de València](https://www.upv.es).

## Contact

Marc Bolaños ([web page](http://www.ub.edu/cvub/marcbolanos/)): marc.bolanos@ub.edu

Álvaro Peris: lvapeab@prhlt.upv.es 
 
 
