# Bundestag Speech NLP Analysis

This project applies **Natural Language Processing (NLP)** techniques to a dataset of ~8,000 speeches from the German Bundestag. The analysis explores systematic gender-based differences in political discourse through **topic modeling, sentiment analysis, and text classification**.  

## Key Results
- Identified systematic **gender-based differences** in the topics addressed by Bundestag members.  
- Built and evaluated several text classification models to predict the gender of the speaker:
  - **Naïve Bayes**  
  - **Multi-Layer Perceptron (MLP)**  
  - **BERT (Bidirectional Encoder Representations from Transformers)**  
- **BERT achieved the highest accuracy at 65%** in predicting gender from text.

---

## Repository Structure
- `NLP_Final_Full_Code.ipynb` – Jupyter Notebook containing the full code for preprocessing, modeling, and evaluation.  

---

## Methods
1. **Preprocessing**
   - Text cleaning and normalization  
   - Tokenization  
   - Vectorization (TF-IDF and embeddings)  

2. **Topic Modeling**
   - Latent Dirichlet Allocation (LDA) to uncover latent topics across speeches  

3. **Sentiment Analysis**
   - Polarity analysis to capture differences in emotional tone  

4. **Text Classification**
   - Implemented multiple models (Naïve Bayes, MLP, BERT)  
   - Compared model performance on gender classification  

---
