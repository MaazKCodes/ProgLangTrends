# ProgLangTrends

## About the Project

Welcome to **ProgLangTrends**, a data science project analyzing trends in programming language popularity over the past two decades. By leveraging machine learning models and visualizations, this project identifies patterns, explores correlations, and predicts future trajectories for the most prominent programming languages. The insights derived from this analysis can help educators, developers, and industry professionals make informed decisions about which languages to focus on.

This project was developed by Maaz Khalil for the course "Problem Solving with Data," taught by Dr. Kiran Garimella at Rutgers University. It showcases a blend of data manipulation, statistical analysis, and machine learning to provide actionable insights into the ever-evolving landscape of programming languages.

## Repository Contents

This repository contains the following files:

1. **`proglanguages.ipynb`**: The main Jupyter Notebook containing the code for data analysis, visualizations, and machine learning models.
2. **`Trends_and_Predictions_in_Programming_Language.pdf`**: A comprehensive project report summarizing the analysis, insights, and takeaways from the project.
3. **`langdata.csv`**: Dataset containing historical popularity percentages of various programming languages from 2004 to 2023.
4. **`langtrends.csv`**: Supplemental dataset with metrics like GitHub activity, job market demand, and educational interest for over 30 programming languages.

## Key Features

### 1. Data Analysis
- Historical trends of programming language popularity visualized through refined graphs.
- Analysis of top 15 programming languages, identifying growth trajectories, consistent leaders, and declining languages.

### 2. Correlation Insights
- High correlation between Wikipedia page views and language popularity (0.93).
- Significant relationship between job market demand and popularity (0.71).

### 3. Machine Learning Models
- Explored multiple models, including Linear Regression and Random Forest.
- Gradient Boosting emerged as the best model with an R-squared value of 0.36.
- Identified Wikipedia page views as the most influential predictor.

## Usage

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn, Scikit-Learn libraries

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/ProgLangTrends.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ProgLangTrends
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook proglanguages.ipynb
   ```
4. Follow the cells in the notebook to execute the analysis and generate visualizations.

### File Descriptions
- **`langdata.csv`**: Provides historical trends of programming language popularity.
- **`langtrends.csv`**: Includes supplemental metrics for deeper insights.
- **`proglanguages.ipynb`**: Contains code for loading data, cleaning it, performing analysis, and training predictive models.
- **`Trends_and_Predictions_in_Programming_Language.pdf`**: Summarizes findings and provides actionable insights.

## Highlights
- Python has shown remarkable growth, driven by its versatility in web development, data science, and machine learning.
- JavaScript remains essential for web development, solidifying its position as a backbone of the internet.
- The correlation between job market demand and language popularity emphasizes the practical value of focusing on in-demand skills.

## Future Directions
This project lays the groundwork for deeper explorations, including:
- Expanding the dataset to include more recent metrics.
- Refining machine learning models to achieve higher predictive accuracy.
- Exploring niche programming languages and their unique trends.

## Acknowledgments
- **Dr. Kiran Garimella** for guidance throughout the course.
- Kaggle for providing the datasets used in this analysis.
- Libraries like Pandas, Matplotlib, Seaborn, and Scikit-Learn for enabling data exploration and machine learning.

---

Feel free to explore the repository and reach out with any questions or suggestions. If you find this project helpful or inspiring, consider starring the repository on GitHub!

