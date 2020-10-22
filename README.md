# Variational-Leakage

This is a repository of the code for "Variational Leakage: The role of Information Complexity in Privacy Leakage".

## Getting Started

### Dependencies

* Python 3.6+
* TensorFlow 2.3+
* Pandas
* Matplotlib (for graphs and figures)
* OpenCV-python (to read and preprocess image data in CelebA experiments)

### Installing

* Download repository
* Install Dependencies
* Download [img_align_celeba.zip] (https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg) and extract it to the CelebA folder in the root of the project

### Executing program

* Run data_colored_mnist.ipynb to generate Colored-MNIST dataset (both biased and uniform)
* Run exp_colored_mnist.ipynb for Colored-MNIST experiments of the paper

* Run exp_celeba.ipynb for CelebA experiments of the paper

## Help

It is highly recommended to select the appropriate batch size based on your GPU's memory and computer specification to utilize maximum efficiency on your computer. 

## Authors

* Amir Ahooye Atashin
* Behrooz Razeghi

## Version History

* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Citation


## Acknowledgments

Inspiration, code snippets, etc.
* [download CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
