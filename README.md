# Python Automation with ChatGPT

This Python script enables automated interactions with OpenAI's ChatGPT, using the `requests` library for HTTP requests and `argparse` for command-line argument parsing. This approach allows users to dynamically send prompts to ChatGPT and receive responses, suitable for various applications such as data scraping, content generation, and automation tasks.

## Features

- **Dynamic Prompt Submission:** Use the command line to send custom prompts to ChatGPT.
- **Flexible Integration:** Designed for easy incorporation into more complex Python projects or automation workflows.
- **Simplified Configuration:** Minimal setup required, with environment variable support for API keys.

## Getting Started

### Prerequisites

Ensure you have the following prerequisites installed:
- Python 3.6 or newer.
- `requests` library.
- No installation required for `argparse` as it's part of the Python standard library.

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/data-setup/Python-automation-chatgpt.git
    cd Python-automation-chatgpt
    ```

2. Install required Python packages:

    ```bash
    pip install requests
    ```

### Configuration

- **API Key:** Securely store your OpenAI API key. We recommend using environment variables. For instance, in a Unix-based system, you can add the following line to your `.bashrc` or `.zshrc`:

    ```bash
    export OPENAI_API_KEY='Your-OpenAI-API-Key'
    ```

- Replace `'Your-OpenAI-API-Key'` with your actual API key.

### Usage

To use the script, you'll need to pass a prompt as a command-line argument. Here's how you can do it:

```bash
python script_name.py "Your custom prompt here"
