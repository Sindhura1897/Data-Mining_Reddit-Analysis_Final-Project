# Reddit Comments to Post Relevance Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue) 
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-orange) 
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2.2-yellow) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.10-red)
![BERT](https://img.shields.io/badge/BERT-transformers-green)
![LDA](https://img.shields.io/badge/LDA-Topic%20Modeling-blueviolet)

## 📌 Overview  
This project analyzes the relevance of Reddit comments to posts by assigning ratings from 1 to 5, where 5 represents the highest relevance. The approach involves vectorization, embeddings, clustering, and a custom relevance metric considering user engagement factors like score and reply count.

## 🛠 Tools & Technologies  
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow, Hugging Face Transformers  
- **Models Used**: LDA, LSTM, BERT, MiniLM, Hybrid Models  
- **Other**: Reddit API, TF-IDF, KMeans Clustering  

## 🔍 Approach  
1. **Data Collection** – Extracted Reddit posts and comments using the Reddit API.  
2. **Preprocessing** – Removed deleted/spam comments, special characters, URLs, and emojis.  
3. **Vectorization & Embeddings** – Applied TF-IDF and embeddings using LDA, BERT, MiniLM, and LSTMs.  
4. **Clustering** – Used KMeans to classify comments into 5 relevance categories.  
5. **Relevance Scoring** – Developed a custom metric incorporating semantic similarity, sentiment analysis, comment scores, and reply counts.  

## 📊 Results  
- Hybrid models (LDA + MiniLM) provided the best clustering performance.  
- The relevance rating effectively identifies meaningful comments.  
- Model effectiveness was evaluated through visual inspection and clustering coherence.  

## 📸 Visuals  

🧩 Design Thinking Process Flowchart  
This flowchart illustrates the end-to-end approach taken in the project, from data acquisition to relevance scoring.  
![Design Thinking Process](images/design_thinking_process_flowchart.png)  

🔍 LDA + MiniLM Clustering  
Visualization of how the LDA + MiniLM model clusters Reddit comments based on relevance.  
![LDA + MiniLM Clustering](images/lda_minilm_clustering.png)  

📊 LDA + MiniLM Clustering Scores  
The final relevance scores assigned to clusters using the custom scoring metric.  
![LDA + MiniLM Clustering Scores](images/lda_minilm_scores.png)  
 


## 🚀 Future Work  
- Improve the relevance metric by introducing weighted factors.  
- Implement automated evaluation techniques for model validation.  
- Incorporate multi-modal content (images, videos) into relevance analysis.  

