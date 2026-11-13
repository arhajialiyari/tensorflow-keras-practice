# TensorFlow and Keras Practice

Jupyter notebooks from my deep learning coursework and hands-on practice. These are **educational exercises**, not independently verified research or reproducible benchmarks.

## Notebooks

| Notebook | Topics | Status and limitations |
| --- | --- | --- |
| [S01_05_DL.ipynb](S01_05_DL.ipynb) | Vectors, matrices, tensors, and regression loss | A saved `ImportError` exists from the original TensorFlow environment. |
| [S06_10_DL.ipynb](S06_10_DL.ipynb) | ReLU, shallow/deep neural networks, and regression | Coursework examples; not a benchmark. |
| [S11_15_DL.ipynb](S11_15_DL.ipynb) | KL divergence, binary/multiclass classification, gradient descent, and SGD | Coursework examples. |
| [S16_20_DL.ipynb](S16_20_DL.ipynb) | Momentum, Nesterov acceleration, and learning-rate scheduling | Some Caltech-101 code uses a machine-specific dataset path. |
| [S21_25_DL.ipynb](S21_25_DL.ipynb) | Initialization, overfitting, L2 regularization, and dropout | Some Caltech-101 code uses a machine-specific dataset path. |
| [S26_30_DL.ipynb](S26_30_DL.ipynb) | CIFAR-10 data augmentation and classification | Coursework exercise, not a separately validated project. |
| [S31_35_DL.ipynb](S31_35_DL.ipynb) | CNNs, transfer learning, Xception, and exploratory U-Net segmentation | Parts are incomplete; U-Net contains an inactive `tfds` import and a step-count variable mismatch. |
| [S36_40_DL.ipynb](S36_40_DL.ipynb) | Introductory intersection-over-union (IoU) | Short practice notebook, not a complete detection model. |

The redundant/incomplete `S33.ipynb` and `test.ipynb` experiments are no longer tracked in this repository. Original local copies can be kept separately. `S41_45_DL.ipynb` has no substantive code and is excluded.

## Data and environment

The `caltech-101/` directory and `caltech-101.zip` are intentionally excluded. Some notebooks need dataset path changes to run on another computer. Saved outputs reflect earlier sessions and do **not** establish that each notebook runs start-to-finish with current TensorFlow versions.

## Provenance and scope

These notebooks document exercises associated with the Aghamohammadi deep learning course. Individual models and examples are educational implementations; the repository is not presented as original research. The [CIFAR-10 CNN Comparison](https://github.com/arhajialiyari/cifar10-cnn-comparison) repository contains a refactored version of one of the Colab exercises, with a separate validation split for model selection and the official test set reserved for final evaluation.
