# 🎬 IMDb Movie Review Sentiment Analysis

An interactive Machine Learning application that analyzes IMDb movie reviews and classifies them as **Positive** or **Negative** using Natural Language Processing (NLP) and Logistic Regression.

Built with Python and Streamlit, this project allows users to explore movie review data, understand sentiment distribution, evaluate model performance, and predict the sentiment of custom movie reviews.

## 🚀 Project Overview

Online movie reviews contain valuable information about audience opinions and experiences. Manually analyzing thousands of reviews can be time-consuming.

This project uses Machine Learning and NLP techniques to automate sentiment classification.

The application processes movie review text, converts it into numerical features using TF-IDF Vectorization, and applies a Logistic Regression model to predict whether a review expresses positive or negative sentiment.

## ✨ Key Features

- **Sentiment Classification:** Predicts whether a movie review is positive or negative.
- **Text Preprocessing:** Cleans review text by removing HTML tags, special characters, and unnecessary spaces.
- **TF-IDF Vectorization:** Converts textual reviews into numerical features.
- **Logistic Regression:** Uses a supervised machine learning algorithm for sentiment prediction.
- **Data Visualization:** Displays sentiment distribution using interactive charts.
- **Confusion Matrix:** Visualizes actual and predicted classification results.
- **Model Evaluation:** Displays model accuracy.
- **Custom Review Prediction:** Allows users to enter their own movie reviews.
- **Interactive Dashboard:** Provides an easy-to-use Streamlit interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive web application |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Scikit-learn | Machine Learning |
| TF-IDF | Text feature extraction |
| Logistic Regression | Sentiment classification |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Regular Expressions (Regex) | Text cleaning |

## 🧠 Machine Learning Workflow

### 1. Data Collection
- Uses the IMDb movie review dataset.
- Contains movie reviews and their corresponding sentiment labels.
- Sentiments include Positive and Negative.

### 2. Data Preprocessing
- Converts text into lowercase.
- Removes HTML tags.
- Removes special characters and numbers.
- Removes unnecessary whitespace.
- Prepares clean text for model training.

### 3. Feature Extraction
- Applies TF-IDF (Term Frequency-Inverse Document Frequency).
- Converts text into numerical feature vectors.
- Uses a maximum of 5,000 features.

### 4. Model Training
- Uses Logistic Regression for classification.
- Splits the dataset into training and testing sets.
- Training data: 80%
- Testing data: 20%

### 5. Model Evaluation
Evaluates model performance using:
- Accuracy Score
- Confusion Matrix

### 6. Sentiment Prediction
- Accepts custom movie reviews.
- Cleans the input text.
- Transforms text using the trained TF-IDF vectorizer.
- Predicts Positive or Negative sentiment.
- Displays prediction confidence.

## 📊 Application Modules

### 🏠 1. Home
- Introduces the IMDb Sentiment Analyzer.
- Provides an input area for movie reviews.
- Displays sentiment prediction results.

### 📈 2. Data Insights
- Displays sample dataset records.
- Visualizes positive and negative sentiment distribution.
- Shows the confusion matrix.
- Displays model accuracy.

### 🧠 3. Sentiment Prediction
- Allows users to enter custom movie reviews.
- Predicts the sentiment.
- Displays the prediction result and confidence percentage.

## 📂 Project Structure

```text
imdb-review-analysis/
│
├── IMDB_Dataset.csv
│
├── app.py
│
├── requirements.txt
│
└── README.md
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### Step 1: Clone the Repository

```bash
git clone https://github.com/udaygore3421/imdb-review-analysis.git
```

### Step 2: Navigate to the Project Folder

```bash
cd imdb-review-analysis
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 4: Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### Step 5: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 6: Run the Application

```bash
streamlit run app.py
```

The application will automatically open in your default web browser.

## 📦 Requirements

- Python 3.10 or compatible version.
- Required Python libraries.
- IMDb dataset (`IMDB_Dataset.csv`).
- Internet connection for initial package installation.

## 💻 Example Prediction

**Input Review:**

"This movie was absolutely fantastic! The acting, storyline, and direction were excellent. I really enjoyed watching it."

**Expected Output:**

- Sentiment: Positive
- Confidence: Model-generated probability.

**Another Example:**

"The movie was boring and disappointing. The story was weak, and the acting was terrible."

**Expected Output:**

- Sentiment: Negative
- Confidence: Model-generated probability.

*Note: Actual predictions and confidence scores depend on the trained model.*

## 🔮 Future Enhancements

- Implement advanced NLP techniques.
- Compare multiple machine learning algorithms.
- Add Naive Bayes and Support Vector Machine (SVM).
- Improve model performance using hyperparameter tuning.
- Add word clouds for positive and negative reviews.
- Include precision, recall, and F1-score.
- Deploy the application using Streamlit Community Cloud.
- Add a larger review analysis dashboard.

## 👨‍💻 Author

**Uday Gore**

GitHub: https://github.com/udaygore3421

Project Repository: https://github.com/udaygore3421/imdb-review-analysis

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with Python, Machine Learning, NLP, and Streamlit.**
