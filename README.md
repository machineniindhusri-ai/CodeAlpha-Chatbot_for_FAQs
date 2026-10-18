readme_content = """# FAQ Chatbot Using Python

## Project Overview
This project is a simple FAQ Chatbot built using Python.
It answers frequently asked questions automatically.

## Objectives
- Automate answers to common questions.
- Learn the basics of Natural Language Processing (NLP).
- Build a simple interactive chatbot.

## Technologies Used
- Python
- NLTK
- Google Colab

## Features
- Accepts questions from users.
- Matches questions with predefined FAQs.
- Provides automatic responses.
- Displays a fallback response for unknown questions.

## How to Run
1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Run the chatbot code.
4. Enter a question and view the response.

## Example
User: Hi
Chatbot: Hello! How can I help you?

## Future Improvements
- Add more FAQs.
- Improve question matching.
- Create a graphical user interface.
- Integrate AI-based responses.

## Author
Indhusri

B.Tech Artificial Intelligence
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(readme_content)

print("README.md created successfully!")
