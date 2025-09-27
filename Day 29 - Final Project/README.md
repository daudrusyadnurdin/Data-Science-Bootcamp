# Final Project Intro:

- In this Data Analysis final assignment, students are given the freedom to determine which data to use. The most important thing is that it meets the criteria for conducting the analysis.
- In this case, I used UK-Ecommerce data, which records e-commerce business transactions for a company (presumably) located in the UK. However, transactions also originate from other countries, both in Europe and beyond.
- In this final assignment/ project, the topic is Customer Segmentation using RFM analysis, and the visualization is done using Power BI. The RFM is created into eight segments, and recommendations are then provided based on the results of the customer segmentation.

# Key Lessons Learned:
- During data preparation, there are many things to do, including data cleaning, removing outliers, removing duplicates, etc.
- However, the interesting part is when cleaning the StockCode and Description columns. These two columns should actually be aligned, as StockCode is the item code, and Description is the description of the item itself. The problem is, the two are sometimes out of sync, as explained in the presentation document.
- Another interesting issue arises when imputing missing values ​​for the CustomerID column, where the total missing values ​​are >20%. Discarding the entire column is impossible, as the information is needed for analysis. Using the Mode approach (because the column is categorical) is also impossible, as the results would be poor. Ultimately, after discussions with Meta AI, it was recommended to use the KNN (K-Nearest Neighbors) method, as Machine Learning had not yet been taught in class.
