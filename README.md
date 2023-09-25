# breast_feedGPT

breast_feedGPT is a chatbot application developed to provide answers to questions commonly asked by nursing mothers regarding breastfeeding and other related topics. 
The project includes both the chatbot model and a web interface for easy interaction. I made use of artilces about breastfeeding from Babymigo's site and a few other blogs that has worthy contents to form my knowldege base for the chatbot. To see the chatbot in action, check out this demo -https://youtu.be/gr9Ztli4RZk

## Features
- Utilizes the Langachain and chatgpt APIs to power the chatbot functionality.
- Integration with Pinecone for efficient storage and retrieval of chatbot responses.
- Built with Streamlit, providing a user-friendly web interface for seamless interaction.
- Handles a wide range of questions and concerns related to breastfeeding.

## Prerequisites
Before running the breast_feedGPT application, ensure you have the following dependencies installed:

- Python 3.7 or above
- Langachain API credentials
- chatgpt API credentials
- Pinecone API credentials

## Installation

1. Clone the repository:

```
git clone https://github.com/hope205/breast_feedGPT.git

```
2. Navigate to the project directory:

```
cd breast_feedGPT
```
3. Install the required dependencies:

```
pip install -r requirements.txt
```
4. Set up the necessary API credentials by following the instructions in the .env.example file. Rename the file to .env and populate the required fields with your own credentials.

## Usage

5. Start the web interface:

```
streamlit run app.py
```

6. Open your web browser and access the application at http://localhost:8501
7. Ask questions related to breastfeeding in the provided input field and receive responses from the chatbot.
8. Explore different features and functionalities offered by the breast_feedGPT application through the web interface. 
9. 
