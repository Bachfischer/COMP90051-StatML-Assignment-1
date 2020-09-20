# Statistical Machine Learning (Team VivaLaVida-Lockdown)
This repository contains the source code for assignment 1 of the COMP90051 Statistical Machine Learning course at the University of Melbourne.

### Submission Details

**Team members:**

- Matthias Bachfischer (Student ID: 1133751)

- Liam Simon (Student ID: 1128453)

- Parikshit Diwan (Student ID: 1110497)

**Tean location:** Melbourne


## Project structure

* `data/` -- Original dataset and preprocessed dataset in form of individual (source, target) pairs
* `doc/` -- Documentation and report 
* `src/` -- Source code for the classifiers
* `src/01_sklearn` -- Source code for the SVM and ensemble classifiers
* `src/02_fastgae` -- Source code and configuration for the fastgae graph autoencoder. Parts of the source code were obtained from the [fastgae repository](https://github.com/deezer/fastgae)  
* `src/03_biggraph` -- Source code and configuration for the PyTorch biggraph classifier. Parts of the source code were obtained from the [PyTorch BigGraph repository](https://github.com/facebookresearch/PyTorch-BigGraph)

## System overview

The source code in this repository contains five classification systems for the task of predicting links between users in online social networks:  A traditional [SVM classifier](https://scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVC.html), two [ensemble classifiers](https://lightgbm.readthedocs.io/en/latest/), the [FastGAE graph autoencoder](https://github.com/deezer/fastgae) using a convolutional graph neural network (CGN) as well as a classifier built using the [PyTorch BigGraph framework](https://github.com/facebookresearch/PyTorch-BigGraph).

For further information, please refer to the project report attached to this submission.
