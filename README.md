# Materials for #NGSchool2019 - Machine Learning for Biomedicine

You will find here the materials for workshops, hackathons and lectures at the #NGSchool2019, together with installation directions and tips for running the software necessary for participation in the NGSchool2019.

## Table of Content 

  * [General instructions](#general-instructions)
     * [Colab](#colab)
  * [Workshops](#workshops)
     * [Intro to HPC](#intro-to-hpc)
     * [Intro to R](#intro-to-r)
     * [Intro to Python](#intro-to-python)
     * [Intro to Stats](#intro-to-stats)
     * [Unsupervised learning](#unsupervised-learning)
     * [Bayesian Inference](#bayesian-inference)
     * [Natural language processing](#natural-language-processing)
     * [Reinforcement Learning](#reinforcement-learning)
     * [Deep learning methods for genomics](#deep-learning-methods-for-genomics)
     * [Deep Generative Models for dimensionality reduction](#deep-generative-models-for-dimensionality-reduction)
     * [Tree based methods](#tree-based-methods)
     * [Lasso workshop](#lasso-workshop)
  * [Hackathons](#hackathons)
     * [Dilated Convolutional Neural Nets for DNase-seq and ATAC-seq footprinting](#dilated-convolutional-neural-nets-for-dnase-seq-and-atac-seq-footprinting)


## General instructions

### Colab
[Google Colab](https://colab.research.google.com) is an online service in which you can run jupyter notebooks (and even use some limited GPU!) It comes with some preloaded libraries which makes it easier to teach and run tutorials without having to spend too much time on fixing dependencies etc.

## Workshops

### Intro to HPC
tutor: Klemens Noga

The wbsite with info about the workshop can be accessed [here](https://docs.cyfronet.pl/display/~plgnoga/NGSchool2019)

### Intro to R
tutor: Maja Kuzman


### Intro to Python
tutor: Kasia Kędzierska

The whole workshop will be executed in the Jupyter notebook, and will rely on several Python packages. In the directory you can find a `setup_check.sh` script you can run to see if your enviorenment satisfies all requirements.

Requirements:
* `python3`  
* `Jupyter` 
* python3 modules:
	* `numpy`
	* `pandas` 
	* `matplotlib`
	* `scipy`


### Intro to Stats
tutor: German Demidov

### Unsupervised learning
tutor: Kasia Kędzierska

The workshop will be run in R notebook. We would work locally and in order to check if all requirements are satisfied.

Requirements:
* `R` 3.5+
* `tidyverse` 1.2.1+
* `dslabs` 0.7.1+
* `factoextra` 1.0.5+
* `ggpubr` 0.2+
* `ggsci`  2.9+
* `MASS` 7.3-50+
* `tidyverse` 1.2.1+
* `tsne` 0.1-3+
* `umap` 0.2.3.1+


### Bayesian Inference
tutor: Roman Cheplyaka

### Natural language processing
tutor: Noura Al Moubayed

*create conda environment:*

`conda create -n workshop python=3.7`

*access the environment:*

`source activate workshop`

*install the libraries:*

```
conda install pandas
conda install jupyter
conda install matplotlib
conda install -c conda-forge spacy
conda install -c anaconda scikit-learn
python -m spacy download en_core_web_lg
conda install keras
```

*download the workshop folder can be found here:*

https://drive.google.com/open?id=154y730NtzsLDjXrT7SwJmbjnlFvkGQC4

*start Jupyter:*

In the terminal “cd” to the workshop folder (NLP_workshop) and then type: `jupyter notebook`

### Reinforcement Learning
tutor: Robert Loftin

### Deep learning methods for genomics
tutor: Ron Schwessinger

The seminar hands-on workshop will be run in a [google colab notebook](https://colab.research.google.com/drive/1SRHe_SXmKeXImNBR6tnhFQ3eThM4-iZu). A google account is required though. Additional information can be found in this [repo](https://github.com/rschwess/tutorial_dl_for_genomics) but no need to install anything for the workshop.

### Deep Generative Models for dimensionality reduction
tutor: Kaspar Märtens

### Tree based methods
tutor: Rosa Karlic

### Lasso workshop
tutor: Tim Padvitski

## Hackathons

### Dilated Convolutional Neural Nets for DNase-seq and ATAC-seq footprinting 
Requirements: 
* `python3`
* `keras` and `Tensorflow v1.14` as backend
* `numpy`
* `scikit-learn`
* google account for colab notebook work

Literature:
* [Dnase Footprinting general Introduction](https://www.nature.com/articles/nmeth.3768)
* [Learning genomic signals at base pair resolution](https://drive.google.com/file/d/1kg6Ic0-FvJtVUva9Mh3FPnOAHJcN6VB-/view)


### 
