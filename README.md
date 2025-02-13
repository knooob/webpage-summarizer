# Webpage Summarizer

A simple Python tool that extracts and summarizes the content of a webpage using a locally hosted AI model via **Ollama**.

## Features

✅ Fetches webpage content ✅ Cleans up unnecessary elements like scripts and images ✅ Summarizes using a locally hosted AI model ✅ Works with **Ollama** (default: `localhost:11434`)

## Installation & Usage

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/webpage-summarizer.git
cd webpage-summarizer
```

### 2. Install Dependencies

```sh
pip install -r requirements.txt
```

### 3. Run the Script

```sh
python summarizer.py
```

### 4. Enter a Website URL

You'll be prompted to enter a URL. Example:

```
Enter a website URL to summarize: https://example.com
```

The AI will then generate a summary.

## Configuration

Modify `config.py` to change Ollama's API URL or the model name.

```python
OLLAMA_URL = "http://localhost:11434/v1"  # Default Ollama URL
MODEL = "llama3.2"
```

## Example Output

```sh
Summary:
This website is about ... (AI-generated summary)
```

## Dependencies

- `requests`
- `beautifulsoup4`
- `openai` (used for compatibility with Ollama's API)

## License

Free to Use / Modify

## Author

Developed by **Kaustubh**. Reach out on GitHub for any queries!

