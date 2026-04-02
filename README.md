# Movie Sentiment Analysis using RNN

## Problem Statement
The objective of this project is to classify movie reviews as positive or negative using Natural Language Processing techniques. This is a binary classification problem where the model learns patterns from textual data.

## Dataset
- IMDB Movie Reviews Dataset  
- Contains 50,000 labeled reviews (positive/negative)  
- Dataset not included in this repository due to size constraints  
- Download from Kaggle: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews  

## Approach
- Built a Recurrent Neural Network (RNN) for sentiment classification  
- Performed text preprocessing including tokenization, padding, and sequence generation  
- Converted text data into numerical form for model input  
- Trained the model to classify sentiment based on review text  

## Methodology
- Cleaned and preprocessed text data  
- Tokenized reviews and converted them into sequences  
- Applied padding to ensure uniform input length  
- Built and trained RNN model  
- Evaluated model performance on test data  

## Model Architecture
- Embedding Layer for text representation  
- RNN Layer to capture sequential dependencies  
- Dense Output Layer for binary classification  

## Results
- Successfully classified movie reviews into positive and negative sentiment  
- Achieved good performance on unseen test data  

## Key Observations
- Text preprocessing plays a critical role in model performance  
- RNN effectively captures sequential dependencies in text  
- Longer reviews provide richer context for predictions  
- Noise in text (stopwords, punctuation) can impact model accuracy  

## Tech Stack
- Python  
- TensorFlow  
- NumPy  
- Pandas  
- NLP preprocessing techniques  

## Project Structure
RNN_Implementation.ipynb  
requirements.txt  

## How to Run

1. Clone the repository:
git clone https://github.com/Rajneel-Chavan/movie-sentiment-analysis-rnn.git  
cd movie-sentiment-analysis-rnn  

2. Install dependencies:
pip install -r requirements.txt  

3. Run the notebook:
jupyter notebook RNN_Implementation.ipynb  

## Key Learnings
- Understanding sequence models like RNN  
- Handling textual data using NLP techniques  
- Importance of tokenization and padding  
- Working with sequential data for classification  

## Notes
- Demonstrates NLP-based sentiment classification using deep learning  
- Dataset excluded due to large size  

## Future Improvements
- Use LSTM or GRU for better performance  
- Apply pretrained embeddings like GloVe or Word2Vec  
- Deploy the model using a web interface  
