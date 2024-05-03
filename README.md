## WhatsApp Chat Analyzer: A Comprehensive End-to-End Project Deployed on Heroku

## Overview
This project is designed to analyze WhatsApp chats, providing insights through sentiment and emotion analysis. It utilizes Python libraries such as Streamlit for visualization and is configured for deployment on platforms like Heroku.

## Prerequisites and Dependencies
To run this project, you'll need:

Python 3.7+
Streamlight, Matplotlib, Seaborn, Wordcloud, Pandas, Emoji
All necessary libraries are detailed in the requirements.txt file.

## Codebase
# Key components:

app.py: Main application script with Streamlit.
helper.py: Helper functions.
preprocessor.py: Text preprocessing utilities.
Procfile: Configuration for Heroku deployment.
setup.sh: Streamlit configuration.
requirements.txt: Dependency details.
FastAPI Integration Essentials
While the current project setup is based on Streamlit, it can be adapted for FastAPI integration if required.

## Installation
**Clone the Repository**: `git clone [repository-url]`
**Install Dependencies**: `pip install -r requirements.txt`

# Environment Setup:
Execute the shell script to configure environment variables for deployment: `bash setup.sh`

## Running the Application
Start the application locally by running:  `streamlit run app.py`
The application will be accessible in a web browser at the default Streamlit port.

## Deployment
This application is ready for Heroku deployment with the configurations provided in the **Procfile** and **setup.sh.** To deploy:

Ensure Heroku CLI is installed and configured.
Deploy using Git or Heroku CLI.
Interacting with the Application
After deployment, the application allows for uploading WhatsApp chat logs and visually analyzing the extracted data.


HERE IS THE APP LINK:
[Whatsapp chat analyzer heroku](https://whats-app-chat-analyzer-146a3e48c2bc.herokuapp.com/)

# HOW TO USE THE WEB APP;
1.  Open the web app
2.  Expert any WhatsApp chat which you want to analyze there.
3.  Remember that chat should be exported in 24 hour-date format; otherwise, it won't work.
4.  Upload the chat to the app and press the button that indicates show analysis.
5.  Voila, you will have all the analysis of that chat, and you will get to know which day is the busiest and also who is the most talkative, and much more.

   
## Contributing
To contribute, please fork the repository, make changes, and submit a pull request.
