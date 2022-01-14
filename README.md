# Iris Recognition - Siamese Neural Network

![keras_siamese_networks_header](https://user-images.githubusercontent.com/87704717/147671007-f94423c5-15b8-4615-8828-8308ee396e0e.png)

One-shot or few-shots learning is an approach that aims to classify objects based on few amount of data. 
In this project we explore the approach of few-shots learning by utilizing a Siamese Neural Network (SNN). In order to evaluate the impact of diﬀerent architectures of SNN on its performance, we implemented two basic models with several variations: Siamese Convolutional Neural Network (SCNN) and Siamese multi-layer perceptron (SMLP). Finally we compared the performance of the diﬀerent structures of the SNN based on a ranking metric.

A SNN can be modelled using any of the conventional neural networks architectures. The determination of the most suitable neural networks architectures with their optimal hyperparameters in a SNN is usually dependant on the desired application and the the dataset. In overall, researches about the diﬀerent architectures of the Siamese neural network have not attracted the interest of the machine learning community. 

This research is an attempt to pave the way to propose approaches to deal with the question: How would changes at the architectural level aﬀect the performance of the SNN? To fulﬁll this purpose, we investigated the performance of an IRIS recognition Siamese Neural Network. The architecture details of the network were: The structure of the SNN, number of layers, size of the kernel of the CNN layers, size of the ﬁnal embedding layer. Finally, we analyzed the performance of the diﬀerent implemented networks based on their learning behavior and accuracy.


Dataset used for training and testing: MMUII

Dataset used for further testing: UBIRIS v2.0

please see the script, the presentation and the report for more details.

brief explanation of the experiment: https://youtu.be/yHY5TXvVqpU

Author: Zahir Bilal
