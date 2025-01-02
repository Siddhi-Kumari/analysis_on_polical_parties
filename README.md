# analysis_on-_polical_parties

# Delhi Election Analysis and Political Sentiment Analysis

This repository contains two major components related to Delhi election data analysis and political sentiment analysis:

1. **Delhi Election Data Analysis**:
   - Data from the Delhi election is processed to analyze key aspects such as **AAP strongholds**, **swing constituencies**, **voter turnout**, and more.
   - Visualizations are generated using **Matplotlib** and **Seaborn** for better insights into voting patterns and constituency performance.
   - Machine learning models (Linear Regression) are applied to predict future election outcomes based on various features such as turnout percentage, votes, and margin of victory.

2. **Political Sentiment Analysis**:
   - Sentiment analysis is performed on tweets related to political parties, specifically BJP and INC.
   - The model is trained using **TF-IDF vectorization** and **Logistic Regression** to classify tweets based on political leaning.
   - The project uses a cleaned dataset of political tweets for training and evaluation, with visualizations to represent the distribution of political tweets and predictions.

## Getting Started

### Prerequisites

To run this project locally, you need to have **Python 3.x** installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- re
- re (for text cleaning)
- scikit-learn (for machine learning models)

You can install all dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
