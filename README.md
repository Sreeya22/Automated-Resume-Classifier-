# Resume Classification Project

This project utilizes Natural Language Processing (NLP) and machine learning techniques to classify resumes into various job categories. The project involves data cleaning, visualization, feature extraction, and model training using K-Nearest Neighbors (KNN).

## Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud

## Dataset
The dataset used in this project is a CSV file containing resumes labeled with their respective job categories. Each entry includes the resume text and its associated category.

## Installation
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Install the required packages:
   ```bash
   pip install numpy pandas matplotlib seaborn nltk scikit-learn wordcloud
   ```

3. Download the NLTK stopwords:
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

## Usage
1. Load the dataset by updating the path to the CSV file in the code:
   ```python
   resumeDataSet = pd.read_csv('path/to/JobResume_Dataset.csv', encoding='utf-8')
   ```

2. Run the main script to clean resumes, visualize data, and classify them into categories.

## Results
The project outputs accuracy scores of the KNN classifier on both training and test datasets, along with a classification report detailing precision, recall, and F1-score.
