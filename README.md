# AI-Powered Text Completion App (Cohere Command R)

A interactive text completion app that uses Cohere's `command-r` model to generate text completions based on user prompts. This capstone project explores prompt engineering and parameter tuning to evaluate how temperature and token limits influence output.

---

## Files Included

├── text_completion_app.ipynb # Jupyter Notebook (Part 1 & 2)
├── project_report.pdf # Experimentation & Evaluation Report
├── README.md # This file


## Setup Instructions

### 1. Clone the Repository


```bash
git clone https://github.com/mynamalneedi/ai-text-completion-project.git
cd ai-text-completion-project
```

### 2. Create and Activate Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install cohere python-dotenv
```
### 4.  Add Your API Key
In the file named .env,  replace your_api_key_here with your own key from Cohere.
```bash
COHERE_API_KEY=your_cohere_api_key_here
```

##  To Run the App: 
Option 1: Jupyter Notebook
Open text_completion_app.ipynb and run each cell to interact with the app and test prompts.

Option 2: Python Script (Optional)
If you convert it to a .py file:
```bash
python text_completion_app.py
```
### Example Prompts to Try
1. Once upon a time, there was a robot who…
2. Explain photosynthesis to a 10-year-old.
3. Write a haiku about the ocean.
4. Give me the Python code for a Fibonacci series.

## Features in the app
1. Prompt input: Enter any natural language prompt
2. Temperature control: Adjust creativity of responses
3. Token limit tuning: Control response length
4. Input validation: Handles empty and overly long inputs gracefully
5. Error handling: Catches API errors and timeout issues

## Evaluation Report
See project_report.pdf for a breakdown of:
1. Prompt design and response quality
2. Effect of temperature and max token settings
3. Use cases: storytelling, summarization, education, coding
4. Observations, limitations, and improvement suggestions
