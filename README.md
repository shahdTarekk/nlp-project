*Project Title
Automatic Review Analysis using BERT and RoBERTa

1)Overview
This project implements an automatic sentiment analysis system using two transformer models: BERT and RoBERTa. The goal is to compare their performance and determine which gives better results on review classification tasks.

 2)Project Structure
notebook.ipynb – Main Jupyter notebook with all implementation steps
data/ – Folder containing the dataset
models/ – (Optional) Saved models, if any
Search_Engine_Report.pdf – Project report in PDF format
README.md – Project instructions and overview

3)How to Run?
Clone the repository or download the files.

4)Install the required libraries:
bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter notebook:
bash
Copy
Edit
jupyter notebook notebook.ipynb
Follow the cells to preprocess data, train models, and view performance.

5)Models Used
BERT (Bidirectional Encoder Representations from Transformers)
RoBERTa (A Robustly Optimized BERT Approach)

6)Results Summary
Model	Accuracy	F1-score
BERT	69.33%	69.51%
RoBERTa	70.33%	69.86%
RoBERTa slightly outperformed BERT in both accuracy and F1-score.

7) Requirements
Python 3.7+
PyTorch
Transformers
NLTK
Pandas, NumPy, Scikit-learn
