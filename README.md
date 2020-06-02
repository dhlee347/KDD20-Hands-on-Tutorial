# Scalable Graph Neural Networks with Deep Graph Library

Learning from graph and relational data plays a major role in many applications including social network analysis, marketing, e-commerce, information retrieval, knowledge modeling, medical and biological sciences, engineering, and others. In the last few years, Graph Neural Networks (GNNs) have emerged as a promising new supervised learning framework capable of bringing the power of deep representation learning to graph and relational data. This ever-growing body of research has shown that GNNs achieve state-of-the-art performance for problems such as link prediction, fraud detection, target-ligand binding activity prediction, knowledge-graph completion, and product recommendations. In practice, many of the real-world graphs are very large. It is urgent to have scalable solutions to train GNN on large graphs efficiently.

The objective of this tutorial is twofold. First, it will provide an overview of the theory behind GNNs, discuss the types of problems that GNNs are well suited for, and introduce some of the most widely used GNN model architectures and problems/applications that are designed to solve. Second, it will introduce the Deep Graph Library (DGL), a scalable GNN framework that simplifies the development of efficient GNN-based training and inference programs at a large scale. To make things concrete, the tutorial will cover state-of-the-art training methods to scale GNN to large graphs and provide hands-on sessions to show how to use DGL to perform scalable training in different settings (multi-GPU training and distributed training). This hands-on part will start with basic graph applications (e.g., node classification and link prediction) to set up the context and move on to train GNNs on large graphs. It will provide tutorials to demonstrate how to apply the techniques in DGL to train GNNs for real-world applications.

Presenters: Da Zheng, Minjie Wang, Quan Gan, Zheng Zhang, George Karypis

## Topics covered include:
* Overview of Graph Neural Networks and training methods
* Overview of Deep Graph Library
* GNN models for basic graph tasks
* GNN training on large graphs
* GNN models for real-world applications
