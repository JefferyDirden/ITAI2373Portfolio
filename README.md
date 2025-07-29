# ITAI2373Portfolio
# ITAI2373 NewsBot Midterm Project

## 📌 Project Overview
This project implements a complete NLP pipeline to classify news articles into categories, extract named entities, analyze sentiment, and generate insights using a custom-built `NewsBotIntelligenceSystem`. It combines supervised learning, linguistic feature extraction, and sentiment analysis to make predictions and provide recommendations.

## 💻 Technologies Used
- Python (Jupyter Notebook)
- spaCy
- NLTK (VADER)
- scikit-learn
- Matplotlib & Seaborn
- Google Colab

## 📂 Dataset
Due to hardware constraints, the project uses a scaled-down version of the BBC News Dataset (~600 articles) across 5 categories. The dataset includes full article content and labels.

## 👤 Individual Contributions
I completed the entire pipeline independently, including:
- Data preprocessing
- TF-IDF feature engineering
- Sentiment scoring with VADER
- Named Entity Recognition using spaCy
- Training and evaluating classifiers (Naive Bayes, Logistic Regression, SVM)
- Designing the final `NewsBotIntelligenceSystem` class
- Testing the model on new examples
- Creating all plots and insights

## 📊 Visualizations Included
- Sentiment distribution by category
- Confusion matrix for classification
- Named entity distribution and heatmap
- Model accuracy comparison table

## 🛠️ How to Run
1. Clone this repository.
2. Open `NewsBot_Notebook.ipynb` in Google Colab or Jupyter.
3. Upload the `news_dataset.csv` into the `/data/` folder.
4. Run the notebook cell by cell.

## 📈 Output Sample
The system predicts the category of a news article and provides:
- Predicted label and probability
- Sentiment analysis (positive/neutral/negative)
- Named entities with types
- Business insights based on the content

## 📬 Contact
*Jeffery Dirden* – `@screwheadz` – student at [Your School]

