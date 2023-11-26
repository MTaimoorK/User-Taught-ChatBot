# _User-Taught Chatbot_

## Overview
This project implements a simple chatbot that learns from user interactions. The chatbot is designed to answer questions based on a pre-defined knowledge base but prompts users to teach it when it encounters unfamiliar queries.

## Files
- `user_taught_chatbot.py`: The main Python script containing the chatbot implementation.
- `knowledge_base.json`: JSON file storing the initial set of questions and answers for the chatbot.
- `README.md`: Project documentation.

## Usage
1. Run the `user_taught_chatbot.py` script.
2. Enter your questions or queries when prompted.
3. If the chatbot recognizes the question, it provides the corresponding answer.
4. If the question is not recognized, the chatbot asks the user for assistance and prompts them to provide an answer.
5. The user can choose to skip teaching the chatbot by typing 'Skip' or contribute a new answer.

## Dependencies
- Python 3.x
- `difflib` module (standard library)

## Instructions
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/MTaimoorK/User-Taught-ChatBot.git
   cd user-taught-chatbot

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request.
