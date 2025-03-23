# NLP_ 


### **Sentiment Analysis on Sentiment140 Dataset using Naïve Bayes**  

#### **Dataset Overview**  
The **Sentiment140 dataset** from Kaggle is a large-scale Twitter sentiment analysis dataset containing **1.6 million tweets** labeled as **positive (1)** or **negative (0)**. Each tweet includes information such as the timestamp, user handle, and text content. The dataset is commonly used to train and evaluate sentiment classification models.  

#### **Model Used**  
A **Naïve Bayes classifier** was implemented for sentiment analysis. Naïve Bayes is a probabilistic model that assumes independence between features and is widely used for text classification tasks due to its simplicity and efficiency.  

#### **Performance Metrics**  
- **Accuracy:** **0.7411 (74.11%)**  
- **Precision & Recall:** Balanced performance for both positive and negative sentiments.  
- **F1-score:** **0.74** for both classes, indicating a well-balanced model.  

#### **Observations & Potential Improvements**  
1. **Feature Engineering:**  
   - **Switching to TF-IDF** instead of simple count-based vectorization could improve results.  
   - **Using n-grams** (bigrams and trigrams) can capture context better.  
2. **Handling Imbalance:**  
   - Though the dataset is balanced, techniques like **SMOTE** (oversampling) or **undersampling** can be applied in imbalanced cases.  
3. **Exploring Other Models:**  
   - **Logistic Regression, Random Forest, XGBoost, or Deep Learning (LSTM, BERT)** could improve performance.  
4. **Hyperparameter Tuning:**  
   - Experimenting with **alpha smoothing** in Naïve Bayes or tuning other model-specific parameters.  

#### **Conclusion**  
The Naïve Bayes model achieves **74.11% accuracy** on the Sentiment140 dataset, showing a solid baseline performance. Enhancing feature extraction, balancing classes, and experimenting with advanced models like **TF-IDF + SVM** or **transformers (BERT)** could further improve accuracy. 🚀
