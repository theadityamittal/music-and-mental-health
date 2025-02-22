# Tunes & Tendencies: Exploring Mental Health

## Project Overview

This project explores the relationship between music preferences and mental health conditions using machine learning. The dataset used is the Music and Mental Health (MxMH) survey, which contains self-reported data on individuals' music habits and their experiences with mental health conditions such as anxiety, depression, insomnia, and OCD.

## Objective

- Analyze correlations between music preferences and mental health conditions.
- Use exploratory data analysis (EDA) to uncover trends in the dataset.
- Develop predictive models to classify mental health conditions based on music listening habits.
- Provide insights for potential applications in music therapy and personalized recommendations.

## Dataset

The dataset consists of survey responses collected via Google Forms, shared on various online platforms. It includes:

- **Music Background Data**: Streaming services used, listening frequency, and musical engagement.
- **Genre Preferences**: Self-reported listening frequency for 16 music genres.
- **Mental Health Ratings**: Anxiety, Depression, Insomnia, and OCD, rated on a scale from 0 (none) to 10 (severe).
- **Demographic Information**: Age, gender, and other personal attributes.

## Methodology

### 1. Data Preprocessing

- Loaded and cleaned the dataset, dropping irrelevant columns.
- Handled missing values and standardized categorical variables.
- Transformed categorical features using label encoding and one-hot encoding.

### 2. Exploratory Data Analysis (EDA)

- Analyzed the distribution of mental health conditions and music preferences.
- Created visualizations including heatmaps, histograms, and violin plots to identify trends.
- Correlation analysis to determine relationships between music genres and mental health conditions.

### 3. Feature Engineering

- Encoded categorical variables such as gender and streaming services.
- Standardized numerical features to improve model performance.
- Selected most relevant features using correlation analysis.

### 4. Machine Learning Models

- Implemented supervised learning models to predict mental health conditions based on music preferences.
- Models used:
  - Random Forest Classifier
  - Logistic Regression
  - Support Vector Machine (SVM)
- Evaluated model performance using accuracy, precision, recall, and confusion matrices.

### 5. Model Evaluation

- Achieved an **82% accuracy** with the Random Forest Classifier, outperforming the baseline by 15%.
- Analyzed feature importance to identify key predictors of mental health conditions.

### 6. Insights and Findings

- Certain music genres showed a strong correlation with higher levels of anxiety and depression.
- Streaming habits also influenced mental health, with some services linked to lower mental health scores.
- These findings can be used to develop AI-driven personalized music therapy recommendations.

## Technologies Used

- **Python**
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for machine learning models
- **Google Colab** for development and execution

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/theadityamittal/music-and-mental-health.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook ML_Project.ipynb
   ```
4. Follow the steps inside the notebook to explore the dataset and execute models.

## Future Work

- Expand dataset with more diverse demographic groups.
- Implement deep learning models for improved accuracy.
- Conduct real-world applications by collaborating with mental health professionals.

## Contributors

- **Aditya Mittal**

## Acknowledgments

- Data collected via survey by [@catherinerasgaitis](https://www.linkedin.com/in/catherine-rasgaitis/).
- Inspiration from research on music therapy and mental health interventions.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
