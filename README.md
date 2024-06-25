# PDF Chatbot

This is a Streamlit application that allows users to query multiple PDF files and get responses from a conversational AI model. The application utilizes Google Generative AI for embeddings and conversational responses.

## Features

- Upload multiple PDF files
- Ask questions about the content of the PDFs
- Get detailed answers from the AI model
- Request a call back by providing your contact information

## Installation

Follow these steps to set up and run the application locally:

### Prerequisites

- Python 3.7+
- Virtual environment tool (e.g., `venv`)

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/notsubash/PDFChatbot.git
```

### Set Up the Virtual Environment

Create and activate a virtual environment:

```bash
conda create -p venv python == 3.11
conda activate /PDFChatbot/venv   
```

### Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
conda install -c conda-forge faiss-cpu       
```

### Set Up Environment Variables

Create a .env file in the root directory of the project and add your Google API key:

```env
GOOGLE_API_KEY=your_google_api_key      
```

### Run the Application

To run the Streamlit application, use the following command:

```bash
streamlit run app.py
```

### Usage

- Open the Streamlit application in your web browser. It should be running on http://localhost:8501.
- Upload your PDF files using the file uploader in the sidebar.
- Ask a question about the content of the uploaded PDFs in the input box.
- If you request a call back, fill out the form with your contact information.
  
### Project Structure
- app.py: Main application script
- requirements.txt: List of dependencies
- .env: Environment variables (not included in the repository)
- venv/: Virtual environment directory (not included in the repository)
  
### License

This project is licensed under the MIT License.

### Contributing

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.



