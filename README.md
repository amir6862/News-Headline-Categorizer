
# NewsWise: News Headline Categorizer 🧠📰

This project uses machine learning to classify news articles into categories like Sports, Politics, Technology, etc., based on their titles. It is trained on the `news.tsv` dataset using TF-IDF features and a Logistic Regression model.

## 🚀 Features
- Cleans and processes news data from a TSV file
- Uses TF-IDF to extract textual features
- Trains a classifier to predict article categories
- Evaluates model performance with precision, recall, and F1-score
- Predicts the category of any new headline

## 🧰 Tech Stack
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization

## 📊 Example
**Input Title:** `Pakistan wins cricket world cup`  
**Predicted Category:** `Sports`

## 📁 Files
- `news.tsv` – The dataset used for training
- `news_classifier.py` – Main training and evaluation script

## 💡 Future Improvements
- Use BERT embeddings for better understanding of headlines
- Build a web interface for live predictions
- Extend support for multi-label categorization

## 📜 License
MIT License

---

Give your news reader a brain — classify news headlines in seconds!
