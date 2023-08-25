# Hotel Review Sentiment Analysis

This repository contains a project focused on sentiment analysis of hotel reviews using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. The dataset used in this project includes various attributes related to hotel reviews, such as hotel details, reviewer information, review content, sentiment scores, and more.

## Project Overview

The main goals of this project are as follows:

- Perform sentiment analysis on hotel reviews using the VADER sentiment analysis tool.
- Explore the distribution of positive and negative sentiment scores.
- Investigate the relationship between reviewer scores and sentiment scores.
- Visualize key insights from the analysis.

## Dataset

The dataset used in this project includes the following fields:

- Hotel_Address
- Review_Date
- Average_Score
- Hotel_Name
- Reviewer_Nationality
- Negative_Review
- Review_Total_Negative_Word_Counts
- Positive_Review
- Review_Total_Positive_Word_Counts
- Reviewer_Score
- Total_Number_of_Reviews_Reviewer_Has_Given
- Total_Number_of_Reviews
- Tags
- days_since_review
- Additional_Number_of_Scoring
- lat
- lng

The text data has been preprocessed by removing unicode and punctuation and transforming it to lowercase.

## Analysis Steps

1. **Sorting Reviews by Sentiment:**
   - The reviews are sorted by negative sentiment and positive sentiment in separate steps.
   - Negative and positive reviews along with their sentiment scores are printed for analysis.

2. **Column Reordering:**
   - The columns are reordered for better visualization.

3. **Saving Results:**
   - The modified DataFrame is saved to a CSV file named "Hotel_Reviews_NLP.csv".

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the analysis script to perform sentiment analysis and generate insights.

## Results

The analysis provides insights into the sentiment distribution of hotel reviews, reviewer scores, and more. Visualizations can be generated based on the analysis results to enhance understanding.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use and modify this code as needed.

## Acknowledgments

- The dataset used in this project is sourced from [https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe].
- The sentiment analysis is performed using the VADER sentiment analysis tool.
