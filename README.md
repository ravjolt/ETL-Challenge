# ETL-Challenge

# Objective

The main goal of this project was to extract, transform, and load data onto a database (SQL) for furture analysis of behaviour based on social media. 

# Datasets

This project focused on social media and news data. The datasets pulled are listed below.

Bhatia, Ruchi [Ruchi Bhatia]. (2021). Stress Analysis in Social Media: Dreaddit: A 		Reddit Dataset (Version 1)  [Data file and study]. Available from Web 			site: https://www.kaggle.com/ruchi798/stress-analysis-in-social-media

Chaturvedi, Kunal [Kunal Chaturvedi]. (2020). COVID-19 and its Impact on Students: Impact 	of Covid-19 Outbreak on Education, Mental health, and Daily Routine (Version 1).  	[Data file]. Available from Web site:									 https://www.kaggle.com/kunal28chaturvedi/covid19-and-its-impact-on-students

Lucif3r. (2021). Social Network Ads: Predict whether the product has been purchased or 		not (Version 1). [Data file]. Available from Web site:							https://www.kaggle.com/d4rklucif3r/social-network-ads

MorganMazer. (2017). How News Appears on Social Media: Comparing What’s on Twitter 	and Reddit to What’s Happening in the World (Version 1). [Data file]. Available from 	Web site: https://www.kaggle.com/socialmedianews/how-news-appears-on-social-media

Statcounter Global Stats. (2021). StatCounter. 			https://gs.statcounter.com/social-media-stats#monthly-200903-202112

# Tools and Libraries

Tools: Jupyter Notebook, PostgreSQL

Libraries: Pandas, Numpy, and datetime


1. CSVs from the above listed sources were read and turned into tables in jupyter notebook
2. Each table was cleaned for clarity and relevance
3. Tables with similar content were joined
4. All tables were loaded into a SQL database using PostgreSQL
