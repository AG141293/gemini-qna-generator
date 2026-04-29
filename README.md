# gemini-qna-generator
Python GenAI project for automated question-answer generation using the Google Gemini 2.5 flash API.


## Overview
This project uses Google's Gemini LLM to automatically generate question-answer pairs from user prompts or input content.

It demonstrates Generative AI, prompt engineering, and API integration using Python.

## Features
✅ Automated question generation  
✅ AI-generated answers  
✅ Prompt-based content generation  
✅ Gemini API integration  
✅ Q&A automation using LLMs  
✅ Notebook implementation for experimentation

## Tech Stack
- Python
- Google Gemini API
- Generative AI
- Prompt Engineering
- Jupyter Notebook

## Workflow
1. Configure Gemini API key
2. Initialize Gemini model
3. Send prompt/input
4. Generate question-answer pairs
5. Display or export generated output

## Installation
```bash
pip install google-generativeai
```

## Import Libraries
```python
import google.generativeai as genai
```

## Configure API
```python
genai.configure(api_key="YOUR_API_KEY")
```

## Initialize Model
```python
model = genai.GenerativeModel("gemini-pro")
```

## Generate Q&A
```python
response = model.generate_content(prompt)
print(response.text)
```

## Example Use Cases
- Interview question generation
- Educational quiz generation
- Study material creation
- FAQ generation
- Content automation
- LLM experimentation

## Sample Input
Generate 5 Python interview questions with answers.

## Sample Output
Q1. What is Python?
A1. Python is a high-level programming language...

## Future Improvements
- Export Q&A to PDF/CSV
- Add Streamlit interface
- Support document-based Q&A generation
- Add RAG integration
- Fine-tune prompt templates
