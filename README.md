# ChatGPT to generate a succinct summary of research abstracts.

Use the OpenAI API for ChatGPT to summarize, suggest applications and organize a collection of research abstracts.  Builds uppon OpenAI's [quickstart](https://platform.openai.com/docs/quickstart)

## Run the example

Developed and tested on Ubuntu 22.04 with Python 3.10.6

Install Python dependency


1. If you don't have the `venv` package, install:

   ```bash
   sudo apt install python3.10-venv
   ```

2. Clone this repository.

3. Navigate into the project directory:

   ```bash
   cd abstract_summarizer
   ```

4. Create a new virtual environment:

   ```bash
   python3 -m venv venv
   . venv/bin/activate
   ```

5. Install the requirements:

   ```bash
   pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file:

   ```bash
   cp .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file.

8. Execute the script

   ```bash
   ./summarizer.py
   ```

which should generate `summary.md`.
