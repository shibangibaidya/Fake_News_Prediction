# Fake News Prediction Using Machine Learning

This project involves building a machine learning model to classify news articles as fake or real. The model was trained using the logistic regression algorithm and evaluated on performance metrics to ensure its effectiveness. A user-friendly prediction system has been implemented, allowing users to input new articles and check whether they are classified as fake news or real news.

---

## Model Workflow

### 1. **Data Preprocessing**:
   - Cleaned and prepared the dataset for analysis.
   - Text preprocessing steps included:
     - Converting text to lowercase for uniformity.
     - Removing stopwords using NLTK's `stopwords` corpus.
     - Tokenization of the text data using `word_tokenize`.
     - Applied stemming using the Porter Stemmer to reduce words to their base forms.

### 2. **Feature Extraction**:
   - Used `TfidfVectorizer` to convert text data into numerical feature vectors.

### 3. **Model Training**:
   - Trained a logistic regression model on the transformed dataset.
   - Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.

### 4. **Prediction System**:
   - Users can input new articles into the system.
   - The system converts text into numerical features and predicts whether the article is fake or real.

---

## Model Performance

- **Accuracy (Training Data)**: 98.64%
- **Accuracy (Test Data)**: 97.91%

---

## Tech Stack

### **Language**:
- `Python`

### **Libraries**:
- `numpy`
- `pandas`
- `nltk` (Natural Language Toolkit)
- `scikit-learn`

---

## How It Works

### 1. **User Input**:
   - The system accepts a news article from the user as input.

### 2. **Text-to-Feature Conversion**:
   - The article is converted into a feature vector using the `TfidfVectorizer`.

### 3. **Prediction**:
   - The pre-trained logistic regression model predicts whether the input article is fake or real.

### 4. **Output**:
   - If the article is classified as fake news, the system outputs: `This is Fake News`.
   - Otherwise, the system outputs: `This is Real News`.

---

## Authors

- [@shibangibaidya](https://www.github.com/shibangibaidya)

