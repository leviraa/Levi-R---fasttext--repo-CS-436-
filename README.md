# Reproducing "Bag of Tricks for Efficient Text Classification" Using fastText

**Author:** Levi Ramirez  
**Course:** CS 436/536 - Machine Learning  
**University:** Binghamton University  

**"Bag of Tricks for Efficient Text Classification"** (Joulin et al., 2017).

The goal is to implement the fastText classifier, evaluate its performance on 
the 20 Newsgroups dataset, and test several modifications to understand 
which training strategies ("bag of tricks") affect accuracy and efficiency.

## Experiments Performed
- Baseline fastText model (bigrams + subwords)
- Unigram-only model
- No subword features
- Reduced training schedule (5 epochs, LR = 0.5)

## Results Summary
- Unigram-only model achieved highest accuracy.
- Removing subwords did not change accuracy.
- Reduced training schedule significantly decreased performance.

See the full report for detailed results and analysis.

## Included Files
- `fasttext_reproduction.ipynb` — Google Colab notebook with all experiments  
- `accuracy_comparison.png` — Accuracy graph  
- `time_comparison.png` — Training time graph  

## 🔗 Original Paper
https://arxiv.org/abs/1607.01759

## 🔗 Original fastText GitHub Repository
https://github.com/facebookresearch/fastText