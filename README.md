# Image Compression using K-Means Clustering

## Project Overview
This project aims to implement image compression using the K-Means clustering algorithm. The idea is to treat an image as a dataset, where each pixel's intensity values represent rows of data. By applying the K-Means algorithm, similar pixels are grouped together, and each cluster is assigned a representative color. This process effectively reduces the size of the image while preserving its essential features.

## Implementation

### 1. K-Means Algorithm

#### 1.1 Finding Closest Centroids
In the "cluster assignment" phase, the algorithm assigns each pixel to its closest centroid based on the current positions of centroids.

#### 1.2 Computing Centroid Means
In the second phase, the algorithm recomputes the mean of each centroid based on the assigned pixels.

#### 1.3 Running KMeans on an Artificial Dataset
The K-Means algorithm is run on an artificial dataset for testing purposes.

### 2. Data
An artificial dataset is generated using the make_blobs function from scikit-learn. This dataset is used for testing the K-Means algorithm.

## Results
After running the K-Means algorithm on the artificial dataset, the centroids and cluster assignments are obtained. These results can be used to compress images by replacing pixel values with the representative colors of the clusters.

<img width="1221" alt="Screenshot 2023-11-28 at 5 24 04 PM" src="https://github.com/mohamadkheirkhah/Image-Compression-using-an-Unsupervised-Learning-Algorithm-K-Means-/assets/144957293/dca45818-6b6d-42d9-a207-67661b86fe3c">
