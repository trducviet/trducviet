# Trịnh Đức Việt

**Computer Science Engineer · Applied AI & Backend Development**

I'm a Computer Science graduate from Hung Yen University of Technology and Education (Gifted and Talented Engineering Program, 2026).

I like building the software around machine learning: preparing data, making models accessible through APIs, and checking whether the output is actually useful. My recent projects span document-grounded chatbots, computer vision, and predictive modeling.

## Projects

### [Sử Việt — Vietnamese History RAG Chatbot](https://github.com/trducviet/vietnam-history-rag)

My individual graduation project. A Vietnamese-language chatbot that retrieves relevant historical sources before generating answers, with citations and safeguards for unsupported questions.

**Python · TypeScript · Node.js/Express · BM25 · FAISS · RRF · LLM APIs**

- Combined keyword and vector retrieval with reciprocal rank fusion.
- Evaluated the system internally on 500 answer-quality questions (**8.766/10** mean score) and 300 retrieval queries (**94.33% Recall@5**).
- The evaluated corpus focuses on selected topics from **1930–1975**, rather than comprehensive coverage of Vietnamese history.

[Source code & reports](https://github.com/trducviet/vietnam-history-rag) · [Academic demo package](https://github.com/trducviet/vietnam-history-rag-defense-v1)

### [Plant Disease Classifier](https://github.com/trducviet/plant-disease-classifier)

An image-classification project for four apple-leaf conditions. The experiments compare DenseNet121 and EfficientNet variants, explore class imbalance and ensembles, and use Grad-CAM to inspect predictions.

**Python · PyTorch · EfficientNet · DenseNet · FastAPI**

- The notebook reports **97% accuracy** and **0.93 macro F1** for a soft-voting ensemble on a **99-image test set**.
- A separate EfficientNet checkpoint powers the local image-prediction API; those ensemble metrics do not describe the API model.

### [Heart Disease Prediction API](https://github.com/trducviet/heart-disease-prediction-api)

A small machine-learning API built around logistic regression, feature selection, and saved preprocessing steps.

**Python · scikit-learn · pandas · Flask**

- Trains and saves a classification model, then serves predictions through a REST endpoint.
- An educational experiment, **not a medical diagnosis or clinical decision tool**.

## Research experience

During a **three-month internship** at the Institute of Information Technology and Electronics, Military Science and Technology Institute, I explored **Text-to-SQL** and built an early chatbot prototype for asking database questions in natural language. The internship received a final evaluation of **9.0/10**.

## Technical background

**Languages:** Python, TypeScript, JavaScript, SQL  
**Backend:** Node.js, Express, Flask, FastAPI  
**AI & data:** RAG, Text-to-SQL, hybrid retrieval, FAISS, BM25, PyTorch, scikit-learn  
**Fundamentals:** Database systems, data structures & algorithms, object-oriented programming

---

[All repositories](https://github.com/trducviet?tab=repositories)

*Evaluation figures above are reported in the individual project repositories and were not independently verified.*
