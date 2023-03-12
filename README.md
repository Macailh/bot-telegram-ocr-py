# Telegram OCR Bot
This repository contains the code for a Telegram bot that performs Optical Character Recognition (OCR) on images sent to it by users. The bot is written in Python and uses the pytesseract library to perform the OCR.

## Getting Started
To use this bot, you will need to create a Telegram bot and obtain an API token. You can follow the instructions here to create a new bot and obtain an API token.

Once you have obtained an API token, you can clone this repository to your local machine and install the required dependencies using the following command:

`pip install -r requirements.txt`
Next, you have to define an environment variable with the name BOT_TOKEN or replace the line with the API token you obtained from BotFather.

Finally, you can start the bot by running the following command:

`python main.py`

## Usage
Once the bot is running, you can send an image to the bot and it will perform OCR on the image and send the text back to you. The bot currently supports the following commands:

- /start: Displays a welcome message.
- /help: Displays a help message.
- /lang <language>: Sets the OCR language to the specified language. 

For example, /lang eng sets the OCR language to English.

## Contributing
Contributions to this project are welcome. If you find a bug or would like to add a new feature, please open an issue or a pull request.

## License
This project is licensed under the MIT License.
