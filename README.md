# AI-Based_Chatbot

Gemini CareerBot
Welcome to the Gemini CareerBot project! This is a simple Python command-line application that acts as a career guidance assistant. It uses the Gemini API to take your interests, skills, and favorite school subjects as input and suggests suitable career options.

Features
Interactive Command-Line Interface: Guides you through a series of questions to gather information.

Gemini API Integration: Uses the gemini-1.5-flash model to generate personalized career advice.

Easy to Use: The setup is straightforward, and the bot provides clear output.

Prerequisites
Before you begin, ensure you have the following installed:

Python 3.x

pip (Python package installer)

Setup
Follow these steps to get the project up and running:

Clone the repository (if applicable) or save the files:
Make sure you have chat.py and .env in the same directory.

Install the required Python libraries:
The project uses python-dotenv and requests. You can install them using pip:

pip install python-dotenv requests

Get a Gemini API Key:

Go to the Google AI Studio to obtain an API key.

Copy your API key.

Configure the .env file:

Open the .env file in a text editor.

Paste your API key after the equals sign. It should look like this:

GEMINI_API_KEY=YOUR_API_KEY_HERE

Important: Do not commit your .env file to a public repository, as it contains sensitive information.

How to Run the Chatbot
Once the setup is complete, you can run the bot from your terminal.

python chat.py

The bot will then start the conversation, asking you for your interests, skills, and favorite subjects.

Example Interaction
$ python chat.py
👋 Welcome to Gemini CareerBot!
I'll ask you a few questions to recommend a suitable career.

1. What are your interests?
> IT Support
2. What are your top skills?
> troubleshooting, desktop support
3. What are your favorite school subjects?
> networking

🤖 Thinking...

🔍 Career Suggestions:
Based on your interests in IT support and networking, along with your skills in troubleshooting and desktop support, here are a few career options to consider:

1. **IT Support Specialist:** This is a direct match for your skills. You'd be the first point of contact for technical issues, helping users with software and hardware problems. It's a great way to grow your troubleshooting abilities.
2. **Network Administrator:** With your interest in networking and troubleshooting skills, this is a natural progression. You'd be responsible for maintaining the computer networks of an organization, ensuring they run smoothly and securely.
3. **Systems Analyst:** This role combines your technical skills with problem-solving. You would analyze a company's computer systems and design solutions to improve efficiency and productivity.
