Conversation Generator using GPT-3 and Sentiment Analysis

Description:
This Python program interacts with the user, generates responses using OpenAI's GPT-3 model via the Hugging Face API, performs sentiment analysis on the generated responses, and creates reports with data visualizations summarizing the sentiment analysis results.

Dependencies:
Python 3.x
transformers library from Hugging Face
textblob library for sentiment analysis
matplotlib library for data visualization

Installation:
Ensure you have Python installed on your system. If not, download and install it from here.
Install the required Python packages using pip:
pip install transformers textblob matplotlib
Clone or download the Python script (conversation_generator.ipynb) and run it.

Usage:
Run the Python script conversation_generator.py.
Follow the prompts and interact with the program. Type your messages when prompted with "You:".
Type "exit" to end the conversation.
After the conversation ends, the program will generate a report summarizing the sentiment analysis results with a pie chart visualization.

Example:
Welcome to Conversation Generator!
Type 'exit' to end the conversation.
You: Hi there!
Bot: Hello! How can I assist you today?
Sentiment: positive
You: What's the weather like today?
Bot: The weather is sunny and warm, perfect for outdoor activities!
Sentiment: positive
You: I'm feeling a bit down today.
Bot: I'm sorry to hear that. Remember, tomorrow is a new day filled with possibilities!
Sentiment: negative
You: exit

Report:
Positive Sentiments: 2
Negative Sentiments: 1
Neutral Sentiments: 0

Note:
The sentiment analysis is based on the polarity of the text, categorized as positive, negative, or neutral.
The program uses OpenAI's GPT-3 model via the Hugging Face API to generate responses, which may not always be accurate or contextually appropriate.
