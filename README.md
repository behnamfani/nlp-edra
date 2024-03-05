# NLP - Dimensionality Reduction Approaches

## Description
Dimensionality reduction refers to the process of reducing the number of features or dimensions in a dataset while preserving its essential information. In NLP, it is commonly used to reduce the size of vector embeddings, which are high-dimensional representations of words or documents. Reducing the size of vector embeddings is beneficial for several reasons. First, it helps to mitigate the curse of dimensionality, which can lead to computational inefficiency and overfitting. By reducing the dimensionality, we can improve the efficiency of NLP algorithms and models. Second, it can help to improve interpretability and visualization of the data by reducing it to a lower-dimensional space that can be easily understood and visualized. In this project, various dimensionality reduction techniques, including t-distributed Stochastic Neighbor Embedding (t-SNE), Principal Component Analysis (PCA), Variational Autoencoder (VAE), and Latent Dirichlet Allocation (LDA), are used and compared with different datasets in terms of runtime, saved memory, and their performances on classification tasks via multiple ML models.

## Project Outline
- [project_outline](https://github.com/s-knauer/nlp-edra/tree/main/project_outline)

## Dataset
- We use three different [datasets](https://github.com/s-knauer/nlp-edra/tree/main/datasets): [Aspect Sentiment Classification Dataset](https://github.com/akkarimi/BERT-For-ABSA/tree/master/asc) - [CheckThat Lab 2023 - Subjectivity Detection](https://gitlab.com/checkthat_lab) - [FEVER](https://fever.ai/dataset/fever.html)
- The [embeddings](https://github.com/s-knauer/nlp-edra/tree/main/SBERT) are calculated using [SBERT](https://www.sbert.net/). 

## Approach [1](https://github.com/s-knauer/nlp-edra/tree/main/Approach%201)
- Variational Autoencoder

<p align="center" width="100%">
    <img width="40%" src="/Approach%201/vae.jpg"> 
    <figcaption>Architecture of Variational Autoencoder (<a href="https://learnopencv.com/variational-autoencoder-in-tensorflow/">source</a>)</figcaption>
</p>


## Approach [2](https://github.com/s-knauer/nlp-edra/tree/main/Approach%202)
- Traditional Dimensionality Reduction techniques such as PCA, LDA, and t-SNE.

## Approach [3](https://github.com/s-knauer/nlp-edra/tree/main/Approach%203)
- Inspired by: A novel approach for dimension reduction using word embedding: An enhanced text classification approach [Link](https://www.sciencedirect.com/science/article/pii/S2667096822000052) Singh et al., International Journal of Information Management Data Insights
Volume 2, Issue 1, April 2022


## Results and Report
- Experiments are done with ML classifiers such as SVM, MLP, and Random Forest on the three datasets, Naive Bayes, and KNN. F1-Scores, Time Inference, and Memory Consumption Plots: [Result](https://github.com/s-knauer/nlp-edra/tree/main/plots)
- Report: [Final report](https://github.com/s-knauer/nlp-edra/tree/main/Problem_Solving)
