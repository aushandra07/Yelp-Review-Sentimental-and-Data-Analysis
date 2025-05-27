# Yelp-Reviews-Sentimental-and-Data-Analysis
This project was a hands-on learning experience where I built a full data analytics pipeline using Python, AWS S3, and Snowflake. I worked with around 5GB of Yelp data (over 7 million reviews) to explore how raw data flows through modern data tools—from ingestion to insight.<br>

What This Project Covers :<br>

1. Preprocessed the Data with Python:<br>
The original JSON file was huge, so I wrote a script to split it into 10 smaller files. This made it easier and faster to work with.<br>

2. Used AWS S3 for Cloud Storage:<br>
Uploaded the cleaned and split files to an S3 bucket to keep everything organized and ready for loading into Snowflake.<br>

3. Loaded and Transformed Data in Snowflake:<br>
Used the COPY INTO command to bring the data into Snowflake, then transformed it into structured tables. This included flattening nested fields<br>

4. Added Sentiment Analysis with a Python UDF:<br>
I created a Python UDF inside Snowflake using TextBlob to calculate sentiment polarity for each review and label it as Positive or Negative. This made it possible to analyze customer sentiment.<br>

5. Ran SQL for Analysis:<br>
I used SQL to analyze various trends and patterns in the data, including customer sentiment, business performance, and regional differences over time.<br>

Learning:<br>
This was part of my self-learning journey to deepen my understanding of data engineering, data warehousing, and analytics using real-world tools and datasets. It helped me see how Python scripting, cloud storage with AWS S3, cloud data warehousing with Snowflake, SQL-based transformations and querying, as well as Python UDFs for data enrichment, all fit together in a modern, end-to-end data pipeline—from raw semi-structured files to actionable business insights.<br>

Link to downlaod the dataset: https://business.yelp.com/data/resources/open-dataset/
