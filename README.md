
# Hyperspectral image classification using CNN and GCN 

Cuprite Data-set classification and mineral mapping

## Acknowledgements

 - [Graph Convolutional Networks for Hyperspectral Image Classification](https://ieeexplore.ieee.org/document/9170817) 
- [source code](https://github.com/danfenghong/IEEE_TGRS_GCN) 


## Run Locally

Clone the project

```bash
  git clone https://github.com/samrat-boda/Graph-Convolution-network-cuprite-dataset.git
```

Go to the project directory

```bash
  cd Graph-Convolution-network-cuprite-dataset
```

Install dependencies

```bash
  pip install -r requirements.txt
```


## Appendix

Files
- LABELED_Cuprie_Data folder containg labeled points.mat and labels.mat
- Cuprite.mat containing entire cuprite data
- requirement.txt file with all the package names and their versions
- Codes of various networks were tested in Tensorflow 1.14 version (a little bit different from 2.0 version in some functions) in Python 3.7 on Windows 11 machines.


## How to use 
Here an example experiment is given by using cuprite data. Directly run .ipynb functions with different networks to reproduce the results on the Cuprite data. Please note that we fixed the randomness of the parameter initialization to reproduce the unchanged results.

This toolbox consists of different hyperspectral classification networks as follows

- 1DCNN: one-dimensional convolutional neural network
- 2DCNN: two-dimensional convolutional neural network
- GCN: graph convolutional network
- miniGCN: mini-batch GCN
## Support

For support, email bodsamrat3@gmail.com or join our Slack channel.

