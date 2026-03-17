# 🔍 SearchSphere: Large-Scale Information Retrieval System

SearchSphere is a complete Information Retrieval (IR) system built from scratch for large-scale passage ranking. It is designed to efficiently retrieve relevant documents from the MS MARCO dataset (8.8M passages) while balancing effectiveness and performance.

## 🚀 Features

- Full IR pipeline implementation from scratch  
- Large-scale dataset handling (MS MARCO – 8.8M passages)  
- Efficient in-memory indexing and retrieval  
- Query processing with stopword removal and stemming  
- Performance profiling and optimization  
- Evaluation using standard IR metrics  

## 📊 Dataset

- **MS MARCO Passage Ranking Dataset**
- ~8.8 million passages  
- Widely used benchmark for modern search systems  
- Data loaded and processed using memory-efficient techniques  

## 🧠 Approach

### 🔹 Data Processing
- Cleaning and filtering passages  
- Stopword removal using NLTK  
- Stemming using PyStemmer  

### 🔹 Indexing & Retrieval
- Custom-built indexing pipeline  
- Efficient data structures for large-scale search  
- Ranking based on relevance scoring  

### 🔹 Evaluation
- Metrics used:
  - nDCG (Normalized Discounted Cumulative Gain)  
  - MAP (Mean Average Precision)  
  - Recall  
  - Precision  
- Benchmarking using `ir_measures`  

### 🔹 Optimization
- Performance profiling for runtime efficiency  
- Use of Polars and NumPy for fast data handling  
- Memory-efficient processing of large datasets  

## 🛠️ Technologies Used

- Python  
- Python-Terrier  
- ir_datasets  
- ir_measures  
- NLTK  
- PyStemmer  
- Polars  
- NumPy / Pandas  
- Matplotlib / Seaborn  

## 📈 Results

- Successfully retrieves relevant passages at scale  
- Achieves strong performance on standard IR metrics  
- Demonstrates balance between efficiency and effectiveness  

## 📌 Conclusion

This project demonstrates how a large-scale search engine can be built from scratch using core Information Retrieval principles. It highlights the importance of efficient data handling, ranking strategies, and evaluation in real-world search systems.
