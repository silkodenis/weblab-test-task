# weblab-test-task

## Implementation Details:

### Feature Extraction

I didn’t overcomplicate this part.

Each image was converted to grayscale, then histogram equalization was applied to normalize contrast. After that, I extracted gradient magnitude maps using the Sobel operator in both horizontal and vertical directions.

### Clustering

Initially, I used classic k-means with a manually chosen number of clusters — and it worked reasonably well.
However, to make the approach more robust (and honest in terms of not knowing the true number of clusters), I switched to HDBSCAN, which can infer the number of clusters automatically and handle noise.

## Results
- Total images: **466**
- Total clusters: **20**

![Cluster 1](result/cluster_1.png)
![Cluster 2](result/cluster_2.png)
![Cluster 2](result/cluster_3.png)
![Cluster 2](result/cluster_4.png)
![Cluster 2](result/cluster_5.png)
![Cluster 2](result/cluster_6.png)
![Cluster 2](result/cluster_7.png)
![Cluster 2](result/cluster_8.png)
![Cluster 2](result/cluster_9.png)
![Cluster 2](result/cluster_10.png) 
![Cluster 2](result/cluster_11.png) 
![Cluster 2](result/cluster_12.png) 
![Cluster 2](result/cluster_13.png) 
![Cluster 2](result/cluster_14.png) 
![Cluster 2](result/cluster_15.png) 
![Cluster 2](result/cluster_16.png) 
![Cluster 2](result/cluster_17.png) 
![Cluster 2](result/cluster_18.png) 
![Cluster 2](result/cluster_19.png) 
![Cluster 2](result/cluster_20.png) 
