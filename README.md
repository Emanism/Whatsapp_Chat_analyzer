## WhatsApp Chat Analyzer

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

## Contributing
To contribute, please fork the repository, make changes, and submit a pull request.
