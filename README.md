# CSCR3204-Case-Studies-Kartikeya-Mohan
📝 NLP Projects – Articles & Product Reviews Classification with BiLSTM

This repository showcases two deep learning projects focused on Natural Language Processing (NLP):
Articles Classification
Product Reviews Sentiment Analysis

Both projects utilize fine-tuned embeddings and a Bidirectional LSTM (BiLSTM) architecture to achieve strong performance in text classification tasks.

🔹 Project 1: Articles Classification
This project builds a model to classify articles into categories.
Key Steps
Text preprocessing: cleaning, tokenization, padding
Fine-tuned embeddings for task-specific word representations
BiLSTM to capture past and future word dependencies
Dense layers for final classification
Applications
Topic categorization
News/article filtering
Document tagging

🔹 Project 2: Product Reviews Sentiment Analysis
This project analyzes product reviews to determine sentiment categories (positive, negative, or neutral).
Key Steps
Preprocessing of review texts
Embedding layer with fine-tuned vectors
BiLSTM for contextual sentiment understanding
Dense + Dropout layers for classification robustness
Applications
Customer feedback analysis
Brand monitoring
Recommendation systems

🏗️ Model Architecture
Embedding (fine-tuned) → BiLSTM → Dense (ReLU) → Dropout → Dense (Softmax)

Install dependencies:
pip install -r requirements.txt

Run training:
python train_articles.py
python train_reviews.py

📊 Results
Achieved high validation accuracy on both datasets
Demonstrated flexibility for multi-class and binary classification
Potential to improve further with pre-trained embeddings (GloVe, Word2Vec, BERT)

🔮 Future Work
Integrate pre-trained embeddings for richer semantic understanding
Deploy as REST API using Flask or FastAPI
Build an interactive dashboard for predictions

👨‍💻 Author
Kartikeya Mohan
Passionate about Machine Learning, NLP, and AI-driven applications
