# MapReduce-for-K-Means

Objective: 
Developed a distributed system to perform K-means clustering on large datasets using a custom-built MapReduce framework.

Technology Stack:
 Implemented the framework using Python, leveraging gRPC for inter-process communication.
 Utilized master-worker architecture where each mapper and reducer ran as separate processes.
 
Algorithm Implementation:
 Implemented the K-means clustering algorithm including:
  Random initialization of centroids.
  Assigning data points to nearest centroids.
  Recomputing centroids based on mean of assigned data points.
  Convergence criteria based on centroid stability or fixed iterations.

Fault Tolerance:
 Implemented fault tolerance mechanisms to handle failures of mappers or reducers, ensuring tasks were reassigned to ensure completion.
 
Uses:
 Online platforms like Netflix, Amazon, and Spotify employ MapReduce to analyze user behavior and preferences.
 Search engines like Google, Bing, and Yahoo use MapReduce to process and analyze vast amounts of web data for indexing, ranking, and relevance scoring.
 MapReduce is widely used in industries dealing with massive volumes of data, such as e-commerce, social media, and financial services.
