# British Airways Reviews Analysis

## Description
Welcome to the British Airways Reviews Analysis project! This initiative focuses on thoroughly analyzing customer reviews for British Airways to uncover valuable insights and provide actionable, data-driven recommendations aimed at enhancing customer satisfaction and overall service quality. The project encompasses data collection, preprocessing, sentiment analysis, and creating interactive visualizations using Tableau.

![Screenshot 2024-07-15 011721](https://github.com/user-attachments/assets/056fbabb-d8f5-4f0d-a3ea-b5211f8698b3)


## Business Relevant Metrics & Dimensions

### Metrics
- **Customer Satisfaction Score**: This metric measures the overall satisfaction level of customers based on their reviews. It helps identify areas where the airline excels and areas needing improvement.
- **Review Sentiment Score**: This score quantifies the sentiment expressed in customer reviews, indicating whether the feedback is positive, negative, or neutral.
- **Frequency of Common Complaints**: This metric tracks how often specific complaints are mentioned in reviews, providing insights into recurrent issues faced by customers.

### Dimensions
- **Review Date**: The date when the review was posted, which helps in identifying trends over time.
- **Reviewer Location**: The geographical location of the reviewer, providing insights into regional differences in customer satisfaction.
- **Flight Route**: The specific route taken for the flight, which can help identify route-specific issues or satisfaction levels.

## Insights & Recommendations

### Key Insights
- **Customer Satisfaction Score**: The analysis reveals key factors that influence customer satisfaction levels. For example, punctuality, in-flight services, and customer service are critical determinants of satisfaction.
- **Review Sentiment Score**: Understanding the emotional tone of customer feedback helps in gauging overall customer sentiment towards the airline.
- **Common Complaints**: Frequent issues such as delays, lost luggage, and poor customer service are identified, highlighting areas for immediate attention.
- **Trends Over Time**: Significant patterns in service quality and customer feedback from 2017 onwards are identified, showing periods of improvement or decline.

### Recommendations
- **Improve Customer Service**: Focus on enhancing customer service in identified weak areas to boost overall satisfaction. Implement training programs and regular assessments for staff.
- **Address Frequent Complaints**: Develop strategies to resolve common issues such as delays and lost luggage. Introduce more efficient processes and better communication with customers.
- **Training Programs**: Develop comprehensive training programs for staff based on feedback trends to ensure consistent service improvement. Regularly update training materials to reflect current customer expectations and best practices.

## Data Sources
- **ba_reviews.csv**: This file contains detailed customer reviews data, including ratings, review text, dates, and other relevant information.
- **Countries.csv**: This file includes country-specific information related to the reviews, such as country names, codes, and regions.

## Installation & Usage

### Prerequisites
- Ensure you have Python and Tableau installed on your system.
- Install necessary Python libraries by running:
    ```bash
    pip install -r requirements.txt
    ```

### Steps to Run the Project
1. **Clone the repository**:
    ```bash
    git clone https://github.com/DarshanRajarathnam/British_Airways_Reviews_Analysis.git
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

### Examples
Here are some examples of how to use the project:

```python
# Example code snippet for loading and displaying data
import pandas as pd

# Load data
reviews = pd.read_csv('data/ba_reviews.csv')

# Display the first few rows of the dataset
print(reviews.head())
