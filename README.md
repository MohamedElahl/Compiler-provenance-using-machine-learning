# Compiler provenance using machine learning

**Problem:**
Identifying the compiler family and optimization level is a crucial phase for malware analysis and reverse engineering. Cracking binary files for extracting provenance information supports a faster detection of malware files. 

**Dataset:**
BinComp compiler fingerprinting dataset. https://github.com/BinSigma/BinComp/tree/master/Dataset.

**Methodologies:**
In this project, Logistic Regression, Support Vector Machines (SVM), Multi-Layer Perceptron (MLP), Decision tree, AdaBoost classifier, Random forest, 
ensemble learning, and model stacking were exploited for compiler provenance of executables. Features engineering was carried out by Strings utility 
and the Ndisasm disassembler. Besides all, the optimization classification problem was tested over deep learning.

**Results:**
The best test accuracy of 100% was achieved by the stacking model for the classification of the compiler family, and 85.9%  for the optimization level by the deep learning model.


![This is an image](https://github.com/MohamedElahl/Compiler-provenance-using-machine-learning/blob/main/assits/compiler%20family%20results.png)


**Keywords:** Compiler Provenance, Machine Learning, Deep Learning, Portable Executable, Feature Extraction
