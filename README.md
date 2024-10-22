# Interview Q&A Chatbot

## Overview
This repository contains the source code for the **Interview Q&A Chatbot**, designed to assist with answering common interview-related questions. The chatbot utilizes advanced language models to generate responses based on the data it has been fine-tuned on. The goal of this project is to provide a helpful tool for preparing for interviews by offering automated, intelligent responses.

You can try the **live version** of the chatbot here:  
[**Live Chatbot**](https://interview-question-and-answer-chatbot-pajxgxusqrsbb8g6nw4nmq.streamlit.app/)

## Features
- Responds to various interview-related questions.
- Built using **Streamlit** for an intuitive web interface.
- Powered by a **GPT-Neo-based model**, fine-tuned on a dataset of interview questions and answers.

## Setup Instructions

### 1. Clone the Repository
Start by cloning this repository to your local machine:
```bash
git clone https://github.com/abulkhair2122/Interview-Question-and-answer-Chatbot.git
cd Interview-Question-and-answer-Chatbot
```

### 2. Install Dependencies
Make sure to install the required dependencies using pip:
```bash
pip install -r requirements.txt
```

### 3. Run the Application
To launch the chatbot, execute the following command:
```bash
streamlit run chatbot.py
```
This will start the chatbot interface in your default web browser.

## Repository Structure
- **chatbot.py**: The main script that runs the Streamlit-based chatbot interface.
- **requirements.txt**: A list of dependencies required to run the chatbot.
- **interview_qnda_model/**: Directory containing the pre-trained model files used by the chatbot.
- **interview_qna.json**: Contains the dataset used for training the chatbot.

## Usage
Once the Streamlit app is running, you can enter interview-related questions into the interface. The chatbot will generate responses based on the model's learned patterns from the training data.

### Important Notes
- The model files are already included in the repository, so there's no need to download them separately.
- The chatbot’s responses are generated based on patterns in the training data. Always verify the accuracy of the responses, especially in professional or formal settings.

## Contact
For any issues or queries, please feel free to open an issue in this repository or reach out via email:

**Abul Khair**  
Email: [meet.abulkhair2002@gmail.com](mailto:meet.abulkhair2002@gmail.com)

