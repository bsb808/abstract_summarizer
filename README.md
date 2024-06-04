# ChatGPT to generate a succinct summary of research abstracts.

Code example to go along with blog post: [ChatGPT to Summarize Research Abstracts](https://mearpub.com/ai-escapades/2023/05/26/chatgpt-to-summarize-research-abstracts/)

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
   cd ai-escapades/summary
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
   ./summary.py
   ```
