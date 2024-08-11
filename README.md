# Addressing Student Mental Health and Well-being: A Chatbot Solution



  
In response to the growing concern around student mental health, I developed a simple chatbot using Python's NLTK library. This chatbot aims to provide accessible information and resources on mental health issues commonly faced by students in college, as well as offer solutions and practices to promote well-being.
 

### Usage Steps/Guidelines
* Read Code description from Readme/ipynb notebook
* Open the chatbot in a terminal for best experience
  - clone the repo
  - run 'python chatbot.py'
* Input 'bye' to stop the conversation with the bot.


### Problem Statement
**PS 2:** Student mental health is a critical issue. The objective is to create a solution that integrates mental health resources, promotes mindfulness practices, or creates a safe space for students to seek support.

### Overview
The chatbot leverages natural language processing (NLP) to interact with users, offering guidance and information based on a customized corpus. This corpus consists of documents that address various aspects of student mental health, including common challenges and effective strategies for managing stress and anxiety. The chatbot serves as a supportive tool, providing responses tailored to the user's input.  [ The corpus is 'corpus.txt' ]


### A Demo of the Chatbot in action  [ Open Chatbot in cmd for better experience ]
<img src="https://raw.githubusercontent.com/souvikcseiitk/Student-Mental-Health-Chatbot/main/extras/animation.gif" alt="Animation" width="600" height="338" />



### Features
- **Keyword Matching:** The bot uses keyword matching to recognize greetings and respond appropriately.
- **TF-IDF Vectorization:** Text is transformed into a numerical format, enabling the bot to assess and compare the relevance of responses.
- **Cosine Similarity:** The bot evaluates the similarity between user queries and potential responses to generate the most suitable answer.
- **Lemmatization:** Text is normalized, ensuring that the bot recognizes different forms of a word as equivalent.

### Usage
To interact with the chatbot, simply run the program in your terminal. It will greet you and begin responding to your queries. The chatbot is designed to help students find useful information and support related to mental health issues. To exit, type "Bye."

python chatbot.py

### Conclusion
This chatbot is a small but meaningful step towards addressing student mental health by making information and resources more accessible. By integrating NLP techniques, the bot creates a supportive environment where students can seek guidance on mental well-being.


# Open the main ipynb using this link (If Github Fails to open properly)

https://nbviewer.org/github/souvikcseiitk/Student-Mental-Health-Chatbot/blob/main/main.ipynb
