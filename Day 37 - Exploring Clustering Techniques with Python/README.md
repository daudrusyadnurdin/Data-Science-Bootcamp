# Assignment Intro:

- The assignment was to estimate a position as a Data Scientist at an airline company. Students were asked to segment customers using K-mean Clustering and to write down their insights (clustering analysis and clustering visualization) in a Python notebook, PDF, or Google Slides. The insights consisted of: (1) labels and (2) recommendations/treatments per cluster.

- An RFM analysis assignment with the same data was also added as an additional assessment bonus.

# Important lesson learned from this assignment:
- One interesting example in this assignment is a string date with the value: 29/2/2014. It cannot be converted directly to a date because such a date does not exist in reality, as 2014 is not a leap year. To address this, I changed the date to 28/2/2014, as it likely refers to the last date in February 2014.
- In this assignment, we gained experience using the Elbow Method and Silhouette Score as evaluation methods commonly used in unsupervised learning, specifically clustering, specifically K-Means, as the model we used in the assignment. Both methods help determine the most appropriate number of clusters (k). Here, I used the assumption of k=3, although in reality, according to my mentor, determining the k value is the result of a mutual agreement with other teams, especially the business team.
