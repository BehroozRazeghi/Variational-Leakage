<p align="center">
    <img alt="GitHub Repo license" src="https://img.shields.io/github/license/BehroozRazeghi/Variational-Leakage?logo=license&style=flat-square">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/BehroozRazeghi/Variational-Leakage?logo=stars&style=flat-square">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues-raw/BehroozRazeghi/Variational-Leakage?logo=open_issues&style=flat-square">
</p>

# Description

This is a repository of the code for "Variational Leakage: The role of Information Complexity in Privacy Leakage".

## Getting Started

### Dependencies

* Python 3.8.X
* TensorFlow 2.4.1+
* Pandas
* Matplotlib (for graphs and figures)
* OpenCV-python (to read and preprocess image data in CelebA experiments)

### Installing

* Download repository
* Install Dependencies
* Download [img_align_celeba.zip](https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg) and extract it to the CelebA folder in the root of the project

### Executing program

* Run `data_colored_mnist.ipynb` to generate Colored-MNIST dataset (both biased and uniform)
* Run `exp_colored_mnist.ipynb` for Colored-MNIST experiments of the paper

* Run `exp_celeba.ipynb` for CelebA experiments of the paper

## Help

It is highly recommended to select the appropriate batch size based on your GPU's memory and computer specification to utilize maximum efficiency on your computer. 

## Authors

* Amir Atashin
* Behrooz Razeghi

## Version History

* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details

## Citation

Please consider referencing the following research paper of this repository if you find it useful or relevant to your research:
```
```
## Acknowledgments

Inspiration, code snippets, etc.
* [download CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
* The innovative concept behind our Colored-MNIST dataset was influenced from ["A Variational Approach to Privacy and Fairness"](https://arxiv.org/abs/2006.06332)
