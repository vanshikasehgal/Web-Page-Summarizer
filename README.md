# Web-Page-Summarizer
A Python-based web content summarizer using BeautifulSoup for web scraping and Olama for AI-driven text summarization.

## Features
- **Web Content Scraping**: Extracts text content from web pages using BeautifulSoup.
- **AI-Powered Summarization**: Leverages Olama's language models to generate concise summaries of the extracted content.
- **Dynamic Input**: Provide any URL, and the application fetches and summarizes the text content.

## Requirements
To run this project, you need the following:
- Python 3.7+
- Python libraries:
  - `beautifulsoup4`
  - `requests`
  - `ollama`
  - `IPython` (for Markdown display)


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Web-Page-Summarizer.git
   cd Web-Page-Summarizer
   pip install -r requirements.txt

   ## Usage
Follow these steps to run the project:

1. **Run the Application**:
   - If you have a script version:
     ```bash
     python script.py
     ```
   - If you're using the Jupyter Notebook:
     - Open `website_summarizer.ipynb` in Jupyter Notebook or Jupyter Lab.
     - Execute each cell sequentially.

2. **Provide the URL**:
   - Enter the URL of the website you want to summarize in the designated input.

3. **View the Summary**:
   - The application extracts text content from the given URL and summarizes it using Olama's summarization model.
## Example Output
Here’s an example of what the application provides:

**Input**: `https://example.com`

**Output**:
Website Title: Example Domain Summary: This is an example website created for demonstrating web content summarization. It provides placeholder text and a few examples of how to use it effectively.

## Contributing
We welcome contributions! If you’d like to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name

