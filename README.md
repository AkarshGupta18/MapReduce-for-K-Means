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
 
