##  Book-Recommendation-System

# A Semantic Book Recommender with LLMs


- Text data cleaning (code in the notebook data-exploration.ipynb)
- Semantic (vector) search and how to build a vector database (code in the notebook vector-search.ipynb). This allows users to find the most similar books to a natural language query (e.g., "a book about a person seeking revenge").
- Doing text classification using zero-shot classification in LLMs (code in the notebook text-classification.ipynb). This allows us to classify the books as "fiction" or "non-fiction", creating a facet that users can filter the books on.
- Doing sentiment analysis using LLMs and extracting the emotions from text (code in the notebook sentiment-analysis.ipynb). This will allow users to sort books by their tone, such as how suspenseful, joyful or sad the books are.
- Creating a web application using Gradio for users to get book recommendations (code in the file gradio-dashboard.py).
This project was initially created in Python 3.11. In order to run the project, the following dependencies are required:

- kagglehub
- pandas
- matplotlib
- seaborn
- python-dotenv
- langchain-community
- langchain-opencv
- langchain-chroma
- transformers
- gradio
- notebook
- ipywidgets