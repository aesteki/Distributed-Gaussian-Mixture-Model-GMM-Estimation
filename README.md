# Clustering-of-large-scale-Gaussian-Mixture-Model-GMM-via-accelerated-model-averaging-methods
A clustering problem formulated as a Gaussian Mixture Model (GMM), where the dataset is distributed over a network of devices, was estimated in a fully decentralized manner with a higher accuracy compared to existing works.
The project focuses on addressing the problem of accelerating the reaching of true estimates in a clustering problem when the dataset is distributed over a network of devices. The challenge in this scenario is that each device in the network only has access to a limited portion of the data and communication is necessary for devices to collaborate and achieve a solution for the clustering problem.

The project proposes a novel algorithm that incorporates the expectation-maximization (EM) method to speed up the convergence process. In this algorithm, each device calculates the local parameters of the Gaussian mixture model (GMM) using the EM method and shares these parameters with its neighboring devices at each iteration. After a specified number of communications, all devices in the network have an estimate of the true parameters of the global GMM model.

A comparison of the proposed method with existing algorithms in the literature is conducted, and the results show that the proposed method accelerates the convergence process and provides a more accurate estimate of the GMM model within the specified number of communications.

In conclusion, the project presents a novel approach to addressing the problem of distributed clustering in a network of devices. The proposed algorithm utilizes the EM method and allows for faster convergence and improved accuracy compared to existing methods. The results of this study can contribute to the development of efficient algorithms for solving clustering problems in distributed systems. The full details of the method can be found in the main publication referred to in the project report.