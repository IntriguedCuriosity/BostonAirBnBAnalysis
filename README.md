Read my blog on this at: https://medium.com/@arshad.haque555/unveiling-boston-with-airbnb-how-jamaica-plain-was-the-winner-1737c0bc5e22

# BostonAirBnBAnalysis
Overview
This project looks into Airbnb markets in Boston, with an emphasis on the relationship between price and review. Several other factors are considered in this research in order to really get a feel for what matters in guest satisfaction. In this study, Kaggle datasets were used to extract useful insights for both prospective guests and hosts in making effective decisions.

# Motivation
This project's purpose is to enlighten both travelers and hosts of the most common pitfalls that are often encountered by answering some of the most important questions, such as:

1. Is price related to reviews/feedback?
2. What are some review keywords that define a positive experience?
3. How do super-hosts differ from regular hosts?
4. Are there any price trends over time?
5. What neighborhoods do guests love the most?

# Datasets Used
The analysis is done based on three datasets available on Kaggle https://www.kaggle.com/datasets/airbnb/boston, also attached in the repository:

listings.csv: Detailed information about every listing available on Airbnb in Boston.

reviews.csv: All the reviews left by guests for listings.

calendar.csv: Info on availability and cost for every listing for some period.

# Repository Structure
README.md: This file provides an overview of the project, its motivation, and how the repository is structured.
Boston_Airbnb_Analysis.ipynb: This is the actual Jupyter notebook where the analysis was conducted. This includes loading data, cleaning, exploration, and visualizing, with insights derived from the data.
datasets/: The datasets used in the analysis: listings.csv, reviews.csv, calendar.csv.
images/: graphs and visualizations generated in the course of the analysis
requirements.txt: A list of Python libraries that need to be installed to run the analysis.
Libraries Used
The following libraries were used in this project:

Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Matplotlib: For creating static plots and visualizations.
Seaborn: For enhanced data visualizations.
TextBlob: To extract sentiments from reviews.
Scikit-learn: For additional data preprocessing and analysis tools.
NLTK: Natural Language Processing and keyword extraction from reviews.
wordcloud
langdetect

# Results Summary
Below are the key findings from our analysis:

Sentiment Analysis: No clear linear relationship was found to exist between price and sentiment scores. There were positive reviews in all price ranges, which means that there are probably other drivers like quality of service, cleanliness, and neighborhood that drive customer decisions and not just price alone.

Keyword Analysis: Great, perfect, clean, and location words were the most used in positive reviews. Negative reviews mentioned the bathroom, kitchen, and location, too.

Price Trends: Prices tend to be more expensive in the spring and summer seasons, maybe since this is the most popular season of the year. There is a clear indication of a price drop towards the end of the year, maybe because of the reduced demand during the fall and winter seasons.

Neighborhood Insights: There were the most listings on Airbnb in Jamaica Plain and the fewest in the Leather District.

# How to Run the Project

1. Clone the repository:
git clone https://github.com/IntriguedCuriosity/BostonAirBnBAnalysis.git

2. Install the required libraries:
pip install -r requirements.txt

3. Open the Jupyter Notebook:
cd to the path where you have extracted below python file and then run the command:
jupyter notebook Boston_Airbnb_Analysis.ipynb

5. Run the cells in the notebook to see the analysis and visualizations.


# Acknowledgments:
The datasets used in this project are provided by Kaggle Boston Airbnb Dataset.
The libraries and tools used in this project are open-source and maintained by their respective communities.

Contributing
If you have suggestions or improvements, feel free to fork the repository and create a pull request. Contributions are always welcome!
