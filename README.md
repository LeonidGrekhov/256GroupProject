# 256GroupProject

This project uses the huging face dataset from the following link: https://huggingface.co/datasets/amazon_us_reviews

In this project we are trying to implement recommendation systems using content based filtering and collaborative filtering. We decided to use the “amazon_us_reviews” dataset from Hugging Face, specifically the “Books_v1_00” subset of the dataset. We used this subset of data because it had the most robust data as well as one of the most amount of data entries. The “Books_v1_00” subset of the entire dataset contains many different entries such as the “customer_id”, “review_id”, “product_id”, “star_rating”, and more. For this project, we wanted to filter through reviews of books and build a recommendation system using this dataset.
	We used three different algorithms to create these recommendation systems. One of the algorithms is a Matrix Factorization-based algorithm. The algorithm we chose to work with is the Singular Value Decomposition algorithm which comes from the Surprise library. The next algorithm we used is the Non-negative Matrix Factorization algorithm also from the surprise library. Lastly we chose KNN as our third algorithm with its several variants from the surprise library.The objective of this project is to build a recommendation system using different algorithms and record the results of each algorithm.

To run these notebooks please install the suprise python library, and pandas

plotly can be installed to view graphs in several notebooks
