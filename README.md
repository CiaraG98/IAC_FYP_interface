# IAC_FYP_interface
This repo contains the "I'm a Celebrity" chatbot interface. This web app is made using the Flask python framework.
## Installation Requirements
After cloning the project be sure to install the packages needed from requirements.txt using pip. It also might be useful to create a python venv to run this.
```
python -m pip install -r requirements.txt
python -m spacy download en
```
Before running the bot first cd into the project directory and download the chatbot model (400MB) using Git LFS.
```
git lfs pull
```
## Running the interface
This project was made and run with python 3.8.0 so there could be some dependency errors with the packages depending on the version used. Generally anything above python 3.6.0 should work.

To run the interface run this in the command line:
```
python flask_app.py
```
This should start the flask server and provide a local host address: http://127.0.0.1:5000/ where the interface should be running.
You can also access the already deployed interface at (https://c-fyp2021.scss.tcd.ie/)
## Interacting with the Bot
Click 'Start Bot' to initialise the bot.
Click 'Get Personality' for the bot to randomly select a celebrity persona.
From here you can chat with the bot. 
If you want to guess who the celebrity is click 'Guess Who'.
If you need a hint click 'Need a hint?'.
If you want to talk to a different celebrity just click 'Get Personality' again.
## Open-Sourced Code
**train.py**, **interact.py**, **utils.py**, **config.json** & **vocab.json** were sourced from the Hugging Face Project [Transfer-Learning-Conversational-AI](https://github.com/huggingface/transfer-learning-conv-ai)
