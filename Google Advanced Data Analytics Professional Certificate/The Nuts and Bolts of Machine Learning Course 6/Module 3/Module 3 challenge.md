# Module 3 challenge

### **Question 1**  
Which of the following statements correctly describe key aspects of k-means? Select all that apply.

- **Answer:**
  - K-means organizes unlabeled data into clusters.
  - The k-means clustering process has four steps that repeat until the model converges.
  - The position of the k-means centroid is the center of the cluster, also known as the mathematical mean.

---

### **Question 2**  
Which of the following is NOT a step in the k-means algorithm?

- **Answer:**  
  - For each point, if a centroid exists within a radius of k from that point, assign the point to the nearest such centroid.

---

### **Question 3**  
Fill in the blank: In order to evaluate the _____ space in a k-means model, a data professional uses the inertia metric. This is the sum of the squared distances between each observation and its nearest centroid.

- **Answer:**  
  - Intracluster

---

### **Question 4**  
Which of the following statements accurately describe agglomerative clustering? Select all that apply.

- **Answer:**
  - There are numerous hyperparameters available for agglomerative clustering.
  - Agglomerative clustering progressively combines clusters based on intercluster distance.
  - The algorithm will stop when an intercluster distance threshold is reached.

---

### **Question 5**  
Which type of linkage determines whether to merge clusters by considering the maximum pairwise distance between the clusters?

- **Answer:**  
  - Complete

---

### **Question 6**  
A data analyst creates a k-means model. They examine the silhouette coefficient of an observation and find it to have a value of zero. What conclusion should they draw in this scenario?

- **Answer:**  
  - The observation is on the boundary between clusters.

---

### **Question 7**  
Which metric would a data professional use to better understand the intracluster distance between data points and their centroids?

- **Answer:**  
  - Inertia

---

### **Question 8**  
Which of the following statements accurately describe the elbow method? Select all that apply.

- **Answer:**
  - The elbow method uses a line plot to visually compare the inertias of different models.
  - There is not always an obvious elbow.

---

### **Question 9**  
You want to use an algorithm to group these data points. Which of the following statements are true? Select all that apply.

- **Answer:**
  - Running a k-means model with k=3 would result in a greater silhouette score than a model with k=2.
  - Running a k-means model with k=4 would result in lower inertia than a model with k=3.
  - Using k-means to cluster this data could be sub-optimal because it works using distance from centroids, and therefore is best used on clusters that are round.
  - DBSCAN would probably perform well to cluster this data, because the DBSCAN algorithm uses data density to determine cluster membership, not Euclidean distance from centroids.

---

### **Question 10**  
Which of the following scenarios make use of unsupervised learning? Select all that apply.

- **Answer:**
  - A data scientist develops a recommendation system to serve music on a streaming service.
  - A marketing department uses a clustering model to identify groups of similar customers.
