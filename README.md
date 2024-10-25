# Movie Genre Classifier

This repository contains a machine learning model designed to classify movies into various genres based on their plot summaries. The project leverages natural language processing (NLP) techniques and various classification algorithms to achieve high accuracy in genre prediction.

## Contents

1. **Data Preprocessing**:
   - Missing-value handling
   - Word tokenization
   - Text normalization
   - Punctuation removal
   - stopword removal
   - Word lemmetization
   - Non-ASCII characters removal
2. **Descriptive Statistics**:
   - Calculating the Summary statistics (mean, median, mode, standard deviation, range) for numerical variables
   - Determining the count and frequency of unique values for categorical variables
3. **Data Visualization**:
   - Plotting histograms or density plots for numerical variables
   - Creating bar plots or pie charts for categorical variables
   - Generating scatter plots or correlation matrices to explore relationships
4. **Genre Analysis**:
   - Creating a word cloud or bar plot for genre distribution (you can use bidi library for persian text)
   - Obtaining the 10 most frequently occurring words for each genre, based on both the initial summaries and the preprocessed summaries.
   - Analyzing the distribution of movies across genres
   - Exploring the relationship between genres and other variables
5. **Time-based Analysis**:
   - Plotting line or bar charts for movie releases over time
   - Investigating trends or patterns in movie releases
   - Analyzing the relationship between release year and other variables
6. **Rating Analysis**:
   - Visualizing the distribution of ratings
   - Obtaining the 10 most frequently occurring words for each Rating, based on both the initial summaries and the preprocessed summaries.
   - Exploring the relationship between ratings and other variables
7. **Correlation and Multivariate Analysis**:
   - Calculating correlation coefficients between numerical variables
   - Using scatter plot matrices or pair plots for multivariate visualization
   - Employing dimensionality reduction techniques (e.g., PCA) for better visualization
8. **Outlier Detection**:
   - Identifying and investigate potential outliers
   - Determining if outliers are genuine or result from data issues
9. **Data Balancing and Feature Engineering**:
   -Genre Mapping and Balancing
   -Resampling Considerations
   -Encoding Categorical Variables
8. **Fine-tuning and model evaluation**

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
   ```bash
   numpy==1.21.2
   pandas==1.3.3
   scikit-learn==1.0.1
   matplotlib==3.4.3
   seaborn==0.11.2
   nltk==3.6.3
   hazm==0.7.0
   wordcloud==1.8.1
   python-bidi==0.4.2
   transformers==4.12.5
   imbalanced-learn==0.9.1
   ```

Install the dependencies using:

```bash
pip install -r requirements.txt
```
## Usage

1. **Clone the repository**:

    ```bash
    git clone https://github.com/alirezamirrokni/MovieGenreClassifier-project.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd DMovieGenreClassifier-project
    ```
    
3. **Open `AI_NLP_Project.ipynb` file and run its cells**.

## Authors        
-[Alireza Mirrokni](https://github.com/alirezamirrokni)    

-[Asal Meskin](https://github.com/asalmsk)      
