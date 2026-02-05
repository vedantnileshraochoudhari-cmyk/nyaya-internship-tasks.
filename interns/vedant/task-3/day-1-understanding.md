# Day 1 — Understanding Embeddings Cluster

In this task we work with sentences and try to group similar sentences together.

First we convert sentences into embeddings because clustering cannot work on text directly. It needs numbers, so embeddings help to convert sentences into numeric form.

After that KMeans clustering is used with k = 3 to group similar embeddings into three groups. Each sentence gets one cluster label.

PCA is used only to visualize the clusters in 2D so we can see them. It does not change the clustering result.

If embeddings are missing, not numeric, or have wrong shape then clustering will fail. If sentences are empty then the whole pipeline will not work properly.
