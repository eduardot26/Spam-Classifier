# Spam-Classifier

# Spam Detection using Naive Bayes
Naive Bayes spam detector using probabilistic modeling

**Goal**: Classify messages as spam or ham using probabilistic modeling and machine learning.

## Tools Used
- Python
- scikit-learn
- pandas
- matplotlib
- Naive Bayes

## Project Steps
1. Loaded and preprocessed data (`spam.csv`)
2. Vectorized text with `CountVectorizer`
3. Trained Naive Bayes classifier
4. Evaluated with accuracy, confusion matrix, and ROC curve


## Results
- Accuracy: 98.6%
- Very clear distinction between spam and ham
- Strong confidence in predictions

## File Structure
- `spam_classifier.ipynb`: full working notebook
- `spam.csv`: dataset
- `README.md`: project summary

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook spam_classifier.ipynb
