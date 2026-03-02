Introduction to Machine Learning


## lecture notes:
- [machine learning fundamentals](https://drive.google.com/file/d/1Fxew6vX9__uNMHkwrYuJ0J2HT4bOB9M-/view?usp=sharing)

## laboratory classes:

#### 1. Preliminary problems
- simple perceptron networks
- Universal Approximation Theorem
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/18a24dcba8536ed4d1218c9a7bbd3eab/preliminary_problems.ipynb), see also [updated notebook](preliminary_problems_v2.ipynb)

#### 2. Image classification using *MNIST* dataset
- models: perceptron, deep fully-connected network, generic CNN
- overfitting, regularization, early stopping
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/7049be85d3e424693cd899a336a3511e/mnist_in_3_flavours.ipynb)

Extra task - **augmentation**: apply some simple geometric transformations (see e.g. [here](https://drive.google.com/file/d/1yt_euw4TQZT1g1OTepu9vtJ9cYrnbObi/view?usp=sharing)), and check if such dataset extending improves accuracy:
- use simple transformations (e.g. flip, rotate, translate, scale) using [scikit-image](https://scikit-image.org/docs/dev/api/skimage.transform.html), or [open-cv](https://docs.opencv.org/4.x/da/d6e/tutorial_py_geometric_transformations.html),
- or use [TorchVision](https://docs.pytorch.org/vision/0.13/transforms.html) library *online*, during the training.
- Verify if applying flips or rotations > 45 deg improve accuracy or not, why?

Extra task - generalization on **wallpaper groups** [dataset](https://drive.google.com/file/d/1BUz9eZdU-8wMGkEEmPk1IIUi05pH5ZUK/view?usp=sharing):
- repeat the classifier training for a 2D crystallographic structures dataset;
- can we extract similarities between the classes from the confusion matrix?

#### 3. ECG signal classification
- classifiers comparison: SVM, decision trees, random forests
- feature vectors and dimensionality reduction (PCA)
- *scikit-learn* library
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/38b38f6566048c5a5b30e691d22c14b4/ecg_classification.ipynb)

#### 4. Group equivariant CNNs
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/4b569399a39b16578da098eb9bb78c0b/equivariant_cnns.ipynb)

#### 5. Physics-informed NNs
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/bc9b1d9a06e7b75be32a90aa852e16f3/pinns.ipynb)

#### 6. Transformer encoder
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/fd5599f96dd3bc97a4c8d085fd9b5e57/simple_transformer.ipynb)

## Literature: 
- KP Murphy, [Probabilistic Machine Learning: An Introduction](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
- KP Murphy, [Probabilistic Machine Learning: Advanced Topics](https://github.com/probml/pml2-book/releases/latest/download/book2.pdf)
- MM Bronstein et al., [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)

## proposed seminar topics
- [list of proposed topics](https://github.com/jarek-pawlowski/ML2026/blob/main/seminar_project_topics.pdf)

## assessment
- [course requirements](https://github.com/jarek-pawlowski/ML2026/blob/main/rules.pdf)
