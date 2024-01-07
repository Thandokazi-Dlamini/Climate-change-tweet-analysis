# Climate-change-tweet-analysis

# Introduction
In an era where climate change is at the forefront of global discourse, businesses are increasingly aligning with eco-friendly and sustainable practices. Companies focused on reducing environmental impact are not only contributing to the welfare of the planet but are also catering to a growing segment of environmentally conscious consumers. Understanding public perception of climate change is vital for these companies as it shapes their product development, marketing strategies, and overall brand positioning. Social media, particularly Twitter, has emerged as a rich data source for gauging public sentiment in real-time across diverse demographic and geographic backgrounds.

# Problem Statement
The challenge presented by the Explore Data Science Academy (EDSA) during the Classification Sprint is to develop a Machine Learning model capable of discerning whether individuals believe in the threat of climate change based on their Twitter activity. The accuracy and robustness of such a model are crucial for businesses to tap into a wide base of consumer sentiment, offering insights that transcend geographical and demographic boundaries. By effectively classifying tweets into distinct categories reflecting belief or skepticism towards climate change, companies can refine their market research, adjust their communication strategies, and ensure that their eco-friendly products and services resonate with their target audience. The goal is to harness the predictive power of Machine Learning to empower businesses with actionable insights, enabling them to spearhead environmental stewardship while achieving commercial success.

# Objective
The primary goal is to create a robust classifier that can accurately identify whether a person believes in climate change based on their tweets. This classifier will provide valuable insights into public opinion on climate change, aiding businesses in their marketing strategies.

# Methodology
The notebook demonstrates the process of data preprocessing, exploratory analysis, and model building. It includes the handling of textual data, feature extraction, and the application of different classification algorithms.

# Technologies Used
The project utilizes Python and its libraries such as Pandas for data manipulation, along with machine learning libraries for building and evaluating models.

# Model Performance:

The classification report from the notebook indicates the performance metrics of the model. The model achieved an overall accuracy of 74%, with the following class-specific performance metrics:
Class -1 (likely representing disbelief in climate change): Precision of 67%, Recall of 49%, and F1-score of 57%.
Class 0 (neutral stance): Precision of 52%, Recall of 48%, and F1-score of 50%.
Class 1 (believes in climate change): Precision of 79%, Recall of 83%, and F1-score of 81%.
Class 2 (actively discussing climate change): Precision of 77%, Recall of 77%, and F1-score of 77%.
These results suggest a strong performance in identifying tweets from individuals who believe in climate change, with comparatively lower performance in classifying disbelief and neutral stances.

# Code and Notebook
For a detailed view of the analysis and modeling, you can access the Jupyter Notebook: 
