# Compiler provenance using machine learning

**Problem:**
Identifying the compiler family and optimization level is a crucial phase for malware analysis and reverse engineering. Cracking binary files for extracting provenance information supports a faster detection of malware files. 


**Methodologies:**
In this project, Logistic Regression, Support Vector Machines (SVM), Multi-Layer Perceptron (MLP), Decision tree, AdaBoost classifier, Random forest, 
ensemble learning, and model stacking were exploited for compiler provenance of executables. Features engineering was carried out by Strings utility 
and the Ndisasm disassembler. Besides all, the optimization classification problem was tested over deep learning.

**Results:**
The best test accuracy of 100% was achieved by the stacking model for the classification of the compiler family, and 85.9%  for the optimization level by the deep learning model.

![Compiler Family Confusion Matrix](https://github.com/MohamedElahl/Compiler-provenance-using-machine-learning/blob/main/assets/compiler%20family%20results.png)
![optimization level results](https://github.com/MohamedElahl/Compiler-provenance-using-machine-learning/blob/main/assets/optimization%20level%20results.png)


## Dataset
BinComp compiler fingerprinting dataset. https://github.com/BinSigma/BinComp/tree/master/Dataset.

Disassembled and strings csv files are available upon request.
[Request complete dataset](mailto:dohaelhady14@gmail.com,zezo.elahl@gmail.com,hassan.mohamed21997@gmail.com,karimbadreldin98@gmail.com?subject=Request%20Compiler%20Provenance%20CSV%20Dataset) 


## Contributors
[Mohamed Elahl](https://github.com/MohamedElahl) - [Hassan Mohamed](https://github.com/Hsnmhmd) - [Karim Youssef](https://github.com/KarimYoussef98) - [Doha ElHady](https://github.com/DohaElHady)
