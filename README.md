
- **sentiment analysis.ipynb.ipynb**: Jupyter Notebook containing the complete implementation of sentiment analysis.
- **README.md**: Project documentation.

---

## 🛠️ Technologies & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NLTK
- scikit-learn
- Matplotlib
- WordCloud

---

## 🔄 Project Workflow

### 1️⃣ Data Collection
Movie review text data is used as input for sentiment classification.

### 2️⃣ Text Preprocessing
The following NLP techniques are applied:
- Converting text to lowercase
- Tokenization
- Stopword removal
- Lemmatization using WordNet

### 3️⃣ Feature Extraction
Text data is converted into numerical format using:
- **Bag of Words (CountVectorizer)**
- **TF-IDF (TfidfVectorizer)**

### 4️⃣ Model Training
A **Logistic Regression** model is trained on the transformed text data to learn sentiment patterns.

### 5️⃣ Model Evaluation
The trained model is evaluated using accuracy on test data.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/HaripriyaDhanireddy/SentimentAnalysis.git
