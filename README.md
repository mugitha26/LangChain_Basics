# LangChain Basics – College Assistant Chatbot

## Project Description
This project is a College Assistant Chatbot developed using LangChain and Ollama. It helps students by answering college-related questions.

## Objectives
- To learn LangChain basics.
- To create reusable prompt templates.
- To build LLM chains.
- To generate chatbot responses.
- To save user queries and chatbot responses in CSV files.

## Technologies Used
- Python
- LangChain
- Ollama
- Gemma3 Model
- Pandas
- Jupyter Notebook

## Features
1. Five Prompt Templates:
   - General
   - Admission
   - Exam
   - Library
   - Placement
2. Tests 20 user queries.
3. Generates chatbot responses.
4. Summarization Chain.
5. Question Answering Chain.
6. Saves outputs in CSV files.

## Project Structure
```text
LangChain_Basics/
├── dataset/
├── notebook/
│   └── Week10_LangChain_Basics.ipynb
├── langchain_chatbot.py
├── README.md
└── requirements.txt
```

## How to Run
1. Install the required packages.
2. Install Ollama.
3. Download the Gemma3 model using `ollama pull gemma3`.
4. Run the Python file using:

```bash
python langchain_chatbot.py
```

## Output
The chatbot generates answers for user questions and saves the results in CSV files inside the dataset folder.

## Conclusion
This project demonstrates how LangChain Prompt Templates and LLM Chains can be used to build a simple College Assistant Chatbot.