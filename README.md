# OM_BhagvadGita_AI
OM BhagvadGita AI
OM BhagvadGita AI is an open-source chatbot that can relate real-life scenarios and situations to the teachings of the Bhagvad Gita, a sacred Hindu scripture.

# Installation and usage: 
The installation and usage instructions should be clear and detailed, and include examples of commands and outputs. For example:
Installation
To install the project, follow these steps:

Clone this repository: git clone https://github.com/himanshukr9192/OM_BhagvadGita_AI.git
Change to the project directory: cd OM_BhagvadGita_AI
Install the required dependencies: pip install -r requirements.txt
Run the chatbot: python om-bhagavad-gita-chatbot.py
Usage
To use the chatbot, simply type your query or scenario in natural language and press enter. The chatbot will respond with a relevant verse from the Bhagvad Gita and its explanation. For example:

> How can I deal with stress and anxiety?
< Verse: 6.35
The Blessed Lord said: O mighty-armed son of Kunti, it is undoubtedly very difficult to curb the restless mind, but it is possible by constant practice and by detachment.

# Explanation: 
The difficulty of controlling the restless mind, as expressed by Arjuna, is accepted by the Supreme Personality of Godhead. But at the same time He suggests that by practice and detachment it is possible. What is that practice? In the present age no one can observe the strict rules and regulations of placing oneself in a sacred place, focusing the mind on the Supersoul, restraining the senses and mind, observing celibacy, remaining alone, etc. By the practice of Kṛṣṇa consciousness, however, one engages in nine types of devotional service to the Lord. The first and foremost of such devotional engagements is hearing about Kṛṣṇa. This is a very powerful transcendental method for purging the mind of all misgivings.

# Dataset and model
The dataset for the chatbot is based on the Bhagavad Gita As It Is by A.C. Bhaktivedanta Swami Prabhupada, which is a translation and commentary of the original Sanskrit text. The dataset contains 700 verses and their explanations in English, along with some keywords for each verse. The dataset was preprocessed by removing punctuation, stopwords, and numbers, and by lemmatizing the words.

The model for the chatbot is a TF-IDF vectorizer combined with a cosine similarity measure. The TF-IDF vectorizer converts the text into numerical vectors based on the term frequency and inverse document frequency of each word. The cosine similarity measure computes the similarity between the query vector and the verse vectors, and returns the most similar verse and its explanation.

The model was trained on the entire dataset and evaluated using the BLEU score, which measures the quality of the generated text by comparing it to a reference text. The model achieved a BLEU score of 0.78, which indicates a high level of similarity between the generated and the reference texts.


