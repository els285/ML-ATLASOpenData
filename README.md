# ML-ATLASOpenData
Repository for **machine learning** resources for ATLAS OpenData November 2025 tutorial.

![image](https://github.com/els285/ML-ATLASOpenData/blob/main/AOpenData_ML_IMAGE.png)

## Scope
This 90 minute session cannot cover an introduction to machine learning and PyTorch, guide you through parsing ATLAS OpenData for using in machine learning contexts, teach you how to build, train and evaluate the performance of a deep neural network, and apply this to train a classifier to separate two processes measured in ATLAS proton-proton collisions. But it's going to attempt that anyway...

The aims are:
* Learn some very high-level concepts about machine learning and DNNs
* Follow code for converting ROOT files to torch tensors, possibly through intermediate HDF5 format
* Apply pre-processing to particle physics data to ready it for machine learning purposes
* Build a DNN in PyTorch
* Evaluate the model performance

## Main Task
The main tutorial task is to build a binary classifier to distinguish between events produced from the decay of a Higgs boson into two W bosons, and from decay of a top-antitop quark pair.
The former will be classes as signal; the latter background.

### Setup
**It is recommended that you run this tutorial using Google Colab.** Colab is the preferred option for machine learning development: it comes with PyTorch pre-installed (usually), and has access to GPUs - though we won't need GPUs for the main task today.

The notebook will also run on Binder and SWAN. For Binder, you will need to pip install the necessary modules, which for PyTorch can take a little while.

## Other Resources
If you find this tutorial is moving too quickly, I have a more pedagogical set of slides and exercises [here](https://github.com/els285/Intro2NN4Physics). This takes you through basic operations with PyTorch tensors, introduces machine learning through linear models as a pre-cursor to deep learning, and finishes with the task we have tackled here!

If you already know about machine learning and can build a DNN, try some jet tagging tasks [here](https://github.com/els285/RAEngHEPTutorial). You can even build a transformer to classify jets 
