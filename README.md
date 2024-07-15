# British Airways Reviews Analysis

## Description
This project aims to analyze customer reviews for British Airways, deriving actionable insights and providing data-driven recommendations to enhance customer satisfaction and service quality. The analysis involves data collection, preprocessing, sentiment analysis, and interactive visualizations.

![Screenshot 2024-07-15 011721](https://github.com/user-attachments/assets/8388c745-d81c-46c1-a4e9-6db80ec2a52d)


## Business Relevant Metrics & Dimensions
- **Metrics**:
  - Customer Satisfaction Score
  - Review Sentiment Score
  - Frequency of Common Complaints
- **Dimensions**:
  - Review Date
  - Reviewer Location
  - Flight Route

## Insights & Recommendations
- **Insights**:
  - Identification of key factors influencing customer satisfaction.
  - Common complaints and areas for improvement.
  - Trends over time regarding service quality.
- **Recommendations**:
  - Improve customer service in identified weak areas.
  - Address frequent complaints to enhance overall satisfaction.
  - Implement training programs for staff based on feedback trends.

## Data Sources
- **ba_reviews.csv**: Contains customer reviews data.
- **Countries.csv**: Contains country-specific information related to reviews.

## Installation & Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/British_Airways_Reviews_Analysis.git
    cd British_Airways_Reviews_Analysis
    ```
2. **Install necessary dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the analysis script**:
    ```bash
    python src/main_code_file.py
    ```

## Examples
Here are some examples of how to use the project:

```python
# Example code snippet
import pandas as pd

# Load data
reviews = pd.read_csv('data/ba_reviews.csv')

# Display data
print(reviews.head())
