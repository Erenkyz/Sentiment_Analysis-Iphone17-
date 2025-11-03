📱 Sentiment Analysis on iPhone 17 Reviews
🧠 Project Overview

This project performs sentiment analysis on user reviews about the iPhone 17, determining whether each comment expresses a positive or negative sentiment.
The goal is to understand public opinion on the device based on real user discussions gathered from Reddit.

🗂️ Data Source

The dataset was collected using the Reddit API, scraping posts and comments related to the iPhone 17.
Each review was preprocessed and analyzed using state-of-the-art Transformer-based NLP models.

🧰 Technologies & Libraries

The project is implemented in Python and uses the following libraries:

pip install transformers torch pandas tqdm nltk matplotlib seaborn

Imported Modules:
import pandas as pd
from transformers import pipeline
from tqdm.notebook import tqdm
from collections import Counter
from nltk.corpus import stopwords
import re
import nltk
import matplotlib.pyplot as plt
import seaborn as sns

⚙️ How It Works

Data Collection – Reddit API is used to gather user comments mentioning “iPhone 17.”

Text Cleaning & Preprocessing – Unnecessary characters, stopwords, and special symbols are removed.

Sentiment Analysis – A pre-trained Transformer model classifies each review as positive or negative.

Visualization – The results are visualized using Matplotlib and Seaborn for better insight into sentiment distribution.

💻 How to Run

Clone this repository:

git clone https://github.com/yourusername/Sentiment_Analysis_Iphone17.git
cd Sentiment_Analysis_Iphone17


Run the notebook or script in the terminal:

python Sentiment_Analysis(Iphone17).ipynb


or open it in Jupyter Notebook:

jupyter notebook Sentiment_Analysis(Iphone17).ipynb

📊 Example Output

Bar chart showing the proportion of positive vs. negative sentiments.

Word frequency visualizations for each sentiment category.

Summary statistics of sentiment distribution.


👨‍💻 Author

Eren Kaymaz
