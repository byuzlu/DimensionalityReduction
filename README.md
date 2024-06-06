# DimensionalityReduction
This project focuses on evaluating various dimensionality reduction techniques for a classification task using a subset of the Fashion-MNIST dataset. The dataset comprises 10,000 samples, with 1,000 samples from each of the 10 categories, representing items such as t-shirts, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots. Each sample is represented by a vector of length 784, obtained by flattening the corresponding 28x28 image.

### Data Description
The dataset is provided in two text files: "fashion mnist data.txt" containing the feature matrix with 10,000 rows and 784 columns, and "fashion mnist labels.txt" containing the corresponding category labels.

### Dimensionality Reduction Techniques
- **Principal Components Analysis (PCA):** PCA is utilized to project the high-dimensional data onto lower-dimensional subspaces. The goal is to observe the effect of dimensionality reduction on the performance of a Gaussian classifier.
  
- **Random Projections:** Random projections offer a simple and computationally efficient alternative for dimensionality reduction. A random matrix is generated to project the data onto a lower-dimensional subspace. The results are compared with those obtained from PCA.

- **t-Distributed Stochastic Neighbor Embedding (t-SNE):** t-SNE is employed for visualization of high-dimensional datasets. The dataset is mapped to two dimensions, facilitating visual exploration. The resulting scatter plot displays samples together with their class information.

### Implementation
- For PCA and random projections, the transformation matrices are generated accordingly. The same number of subspaces is used for comparison.
- For t-SNE, the parameters for initialization, iterations, and stopping criteria are carefully chosen. The resulting visualizations are analyzed and discussed.

### Contribution and Support
Contributions and feedback are welcome to enhance the functionality and usability of the dimensionality reduction techniques explored in this project. For any questions or assistance, please reach out to the project contributors. Thank you for your interest and support as we continue to develop and improve our understanding of handling high-dimensional data for classification tasks.
