# ETL-Challenge

# Objective

ETL or Extract, Tranform, Load, is a strategy of which to gather data from mutiple sources into once central location. The extraction is the means of gatheirng the data from the different sources. Transformation is the means of cleaning the data or standardizing the data. Lastly, Loading is the means of loading or placing the transformed data into its new destination to for future queries and analysis.


Project Goal:
Social media has, in recent year, become more and more of a major factor in our everyday lives. It is used to commmunicate with family and friends, make new friends across the world, learn new cultures, etc. Social media allows us to keep up with each other in real time, all the time. This has it benefits and it downfalls. Here we wanted to understand the behaviours of those on social media based on the presence.

This goal of this project is the following:
1. Gather data related to behaviour on social media
2. Transform the data
3. Load the data into a database

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

![image](https://user-images.githubusercontent.com/89175197/185862244-4c308238-2307-4057-90f0-397970237459.png)
![image](https://user-images.githubusercontent.com/89175197/185862333-f07be78b-3e37-49d0-a47b-6d34a5d76be2.png)
![image](https://user-images.githubusercontent.com/89175197/185862602-b934d7e4-16be-421e-bae1-05ab3e4391e4.png)


3. Tables with similar content were joined
![image](https://user-images.githubusercontent.com/89175197/185863052-74b9b7d2-94cf-408a-b840-6a5af2e8228f.png)
![image](https://user-images.githubusercontent.com/89175197/185863220-0f406a0d-1eac-4f5c-85b8-d63b56cf49eb.png)

4. All tables were loaded into a SQL database (PostgreSQL)
![image](https://user-images.githubusercontent.com/89175197/185863357-ec90c3a8-25ed-41e1-bf98-3da2151e9c7d.png)

