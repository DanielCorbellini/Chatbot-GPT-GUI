# ChatBot with PyQt6 and OpenAI
This project is a simple chatbot application that allows you to interact with a chatbot powered by
OpenAI's davinci-003 engine. The chatbot is integrated into a graphical user interface (GUI) 
created using PyQt6. 
Users can input messages, and the chatbot responds with text-based replies.

## Features
- Real-time chat with a chatbot powered by OpenAI's GPT-3.
- User-friendly graphical interface created with PyQt6.
- Messages are displayed in a chat-like interface.
- Easy-to-use input field with a "Send" button.

## Prerequisites
### Before you begin, ensure you have met the following requirements:

1. Python 3.x installed on your system.
2. OpenAI API key. Replace "YOUR API KEY" in the backend.py file with your actual OpenAI API key.

## Installation
- Clone this repository to your local machine:

- Navigate to the project directory:
- Install the required Python packages:
` pip install PyQt6 openai \`

## Usage
1. Run the main.py file to start the chatbot application:
2. The chat window will appear.
3. Type your message in the input field at the bottom and press "Enter" or click the "Send" button.
4. The chatbot will respond with a text-based message in the chat area.
5. Continue the conversation by typing new messages and pressing "Send."
6. To exit the application, close the chat window.

## Configuration
You can customize the behavior of the chatbot by adjusting the parameters in the 
get_response method of the ChatBot class in the backend.py file. For example, 
you can change the engine, max_tokens, and temperature values 
to influence the style and length of responses.

## Please Note:
To use this chatbot program, you must have an active and paid subscription with OpenAI. 
OpenAI's GPT engine, which powers this chatbot, requires a valid API key associated with a paid account.

If you do not have an OpenAI subscription or API key, 
you won't be able to access the engines, and this program will not function as expected.

To obtain an API key and subscription, please visit the 
[OpenAI website](https://platform.openai.com/overview) for more information on their pricing and subscription plans.
