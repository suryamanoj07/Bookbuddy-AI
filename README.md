Semantic Book Recommender with LLMs 

<img width="1825" height="734" alt="image" src="https://github.com/user-attachments/assets/e56a47e3-7a02-470e-b47e-a8918e1e6ca7" />

<img width="1827" height="726" alt="image" src="https://github.com/user-attachments/assets/5053ce00-9384-4110-8d36-4ed955e4457d" />



* Text data cleaning (code in the notebook `data-exploration.ipynb`)
* Semantic (vector) search and how to build a vector database (code in the notebook `vector-search.ipynb`). This allows users to find the most similar books to a natural language query (e.g., "a book about a person seeking revenge").
* Doing text classification using zero-shot classification in LLMs (code in the notebook `text-classification.ipynb`). This allows us to classify the books as "fiction" or "non-fiction", creating a facet that users can filter the books on. 
* Doing sentiment analysis using LLMs and extracting the emotions from text (code in the notebook `sentiment-analysis.ipynb`). This will allow users to sort books by their tone, such as how suspenseful, joyful or sad the books are.
* Creating a web application using Gradio for users to get book recommendations (code in the file `gradio-dashboard.py`).

This project was initially created in Python 3.12. In order to run the project, the following dependencies are required:
* [kagglehub](https://pypi.org/project/kagglehub/)
* [pandas](https://pypi.org/project/pandas/)
* [matplotlib](https://pypi.org/project/matplotlib/)
* [seaborn](https://pypi.org/project/seaborn/)
* [python-dotenv](https://pypi.org/project/python-dotenv/)
* [langchain-community](https://pypi.org/project/langchain-community/)
* [langchain-chroma](https://pypi.org/project/langchain-chroma/)
* [transformers](https://pypi.org/project/transformers/)
* [gradio](https://pypi.org/project/gradio/)
* [notebook](https://pypi.org/project/notebook/)
* [ipywidgets](https://pypi.org/project/ipywidgets/)

A requirements.txt file containing all the project dependencies is provided as part of this repo.


