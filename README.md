# Prompt-engineering
I have tasked my AI to perform sentiment analysis and language translation. The resulting code explicitly shows how I can create prompt engineering templates to perform a specific task as well.
The results on sentiment and autofill are given in JSON format and can be used for further analysis. 

First step is to import the necessary modules and I'll be using OpenAI's helper function to process my prompts and give a response based on the instructions I have given to my AI. It's prudent to store your OpenAI API Key as an environment variable to avoid any leaks.
The model used is GPT 3.5 Turbo. (You could try with GPT-4 or any other model of choice).

I generated 20 reviews with ChatGPT and I will be using them as my data points (You could try with your own sample data). I then instructed my AI to perform several tasks and return the results in a JSON file format. I did the same with my contract data and instructed the AI to perform language translation from English to Swahili.

Prompt engineering is necessary, especially since LLMs are prone to hallucinations. It allows you to generate responses and helps the AI focus at the task at hand. I assure you, it's fun. Try it sometime!
