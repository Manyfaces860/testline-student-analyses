# Quiz Performance Analysis Project

## Project Overview
This project performs a comprehensive analysis of quiz performance data using Python, pandas, and data visualization libraries. The analysis focuses on extracting insights from historical quiz data across different topics.

## Prerequisites
- Python 3.8+
- Libraries:
  - pandas
  - matplotlib
  - seaborn

## Setup Instructions
1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Ensure you have a `historical data.json` file in the same directory as the script

## Data Processing Approach
The script performs several key data transformations:
- Loads JSON data into a pandas DataFrame
- Extracts quiz information
- Calculates derived metrics like:
  - Time taken per quiz
  - Accuracy
  - Performance percentage
  - Speed metrics

## Visualization Techniques
The project generates multiple visualizations to analyze quiz performance:
- Topic-wise percentage performance
- Topic-wise accuracy
- Time spent per topic
- Speed across different topics
- Performance trends relative to days passed

## Key Analyses
1. Topic-based Performance Breakdown
   - Average percentage per topic
   - Accuracy comparison across topics
   - Time spent per topic
   - Speed analysis

2. Temporal Performance Analysis
   - Performance tracking relative to days passed
   - Trend analysis for:
     - Accuracy
     - Time taken
     - Percentage performance
     - Mistake counts
     - Speed variations

## Running the Analysis
```bash
python a.py
```

## Output
The script generates multiple matplotlib and seaborn visualizations showing performance insights across different dimensions.