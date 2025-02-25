# Restaurant Tips EDA

## Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset containing restaurant tips. The goal is to analyze tipping behavior based on various factors such as bill amount, day of the week, time, gender, and group size. By visualizing and interpreting patterns, we aim to gain insights into what influences tipping habits in restaurants.

## Dataset
The dataset used in this project consists of the following features:
- `total_bill`: Total bill amount in dollars
- `tip`: Tip amount in dollars
- `sex`: Gender of the customer (Male/Female)
- `smoker`: Whether the customer is a smoker (Yes/No)
- `day`: Day of the week (Thursday, Friday, Saturday, Sunday)
- `time`: Meal time (Lunch/Dinner)
- `size`: Number of people in the party

## Installation
To run this project, ensure you have Python installed along with the required libraries. You can install them using:

```bash
pip install pandas numpy matplotlib seaborn
```

## Exploratory Data Analysis Steps
1. **Loading the Dataset** - Read the dataset into a pandas DataFrame.
2. **Data Cleaning** - Handle missing values and check data types.
3. **Descriptive Statistics** - Summarize the data with measures like mean, median, and standard deviation.
4. **Visualizations**:
   - Distribution of total bills and tips
   - Relationship between bill amount and tip percentage
   - Tipping behavior based on gender, smoker status, and group size
   - Comparison of tips on different days and meal times
5. **Insights & Conclusion** - Summarizing findings and trends observed in the dataset.

## Usage
Run the `eda.ipynb` Jupyter Notebook to explore the data and generate visualizations:

```bash
jupyter notebook eda.ipynb
```

## Results
Key takeaways from the analysis include:
- The average tipping percentage varies based on meal time and day of the week.
- Larger groups tend to leave lower percentage tips.
- Smokers and non-smokers exhibit different tipping habits.
- Gender differences in tipping behavior may exist but require further statistical analysis.

## Contributing
If you have suggestions for additional analyses or visualizations, feel free to open a pull request or submit an issue.

## License
This project is licensed under the MIT License.

---
Happy analyzing! 🚀
