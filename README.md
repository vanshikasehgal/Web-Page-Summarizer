# Web-Page-Summarizer

A Python-based web content summarizer using BeautifulSoup for web scraping and Olama for AI-driven text summarization.

## Features
- **Web Content Scraping**: Extracts text content from web pages using BeautifulSoup.
- **AI-Powered Summarization**: Leverages Olama's language models to generate concise summaries of the extracted content.
- **Dynamic Input**: Provide any URL, and the application fetches and summarizes the text content.

## Requirements
- Python 3.7+
- `beautifulsoup4`
- `requests`
- `ollama`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Web-Page-Summarizer.git
   
## Navigate to the project directory:
bash
cd Web-Page-Summarizer

## Install dependencies:
bash
pip install -r requirements.txt

## Usage
### Run the Application:
For terminal-based usage:
bash
python script.py
For Jupyter Notebook: Open the notebook file and execute cells as needed.
Provide the URL: Enter the URL of the website you want to summarize.
View the Summary: The application extracts text from the website and displays the summarized content.
# Example Output
Input: https://example.com

Output:
Website Title: Example Domain
Summary: This is an example website created for demonstrating web content summarization. It provides placeholder text and a few examples of how to use it effectively.
## Deployment (Optional)
You can deploy this project using:

Streamlit: Create a web-based interface for your summarizer.
Heroku: Deploy as a web application accessible via a URL.
Example Streamlit command:

bash

streamlit run app.py
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
