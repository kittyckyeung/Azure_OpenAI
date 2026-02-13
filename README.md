# Azure OpenAI Lab Notebook

This repository contains a Jupyter Notebook that demonstrates various use cases and best practices for interacting with Azure OpenAI services. Below is an overview of the notebook's content and structure.

## Notebook Overview

### Step 1: Setup
- **Description**: This section sets up the environment for interacting with Azure OpenAI services.
- **Code**: Imports necessary libraries and initializes the Azure OpenAI client.

### Step 2: Clarity, Specificity, and Iteration
- **Description**: Demonstrates how to create clear and specific prompts for better AI responses.
- **Code**: Examples include generating JSON structures for tourist attractions.

### Step 3: Structured Prompting with RTCF
- **Description**: Introduces the RTCF (Rules, Tone, Clarity, Formatting) structure for creating effective prompts.
- **Code**: Applies RTCF rules to refine prompts and extract specific information.

### Step 4: Multi-Turn Conversations
- **Description**: Implements a loop for multi-turn conversations with the AI, maintaining context across turns.
- **Code**: Includes a function `call_LLM_loop` for interactive conversations.

### Step 5: Responsible and Safe Prompting
- **Description**: Focuses on creating prompts that mitigate hallucinations and ensure responsible AI usage.
- **Code**: Example includes a prompt where the AI explicitly states "I don't know" if the answer is unknown.

## How to Use
1. Open the `lab_notebook.ipynb` file in Jupyter Notebook or VS Code.
2. Follow the steps in the notebook sequentially.
3. Modify the prompts and code as needed to suit your use case.

## Prerequisites
- Python installed on your system.
- Azure OpenAI credentials (API key, endpoint, and API version).
- Required Python libraries: `openai`, `os`, `json`.

## Notes
- Replace placeholder values (e.g., `XXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX`) with your actual Azure OpenAI credentials.
- Ensure your Azure OpenAI service is properly configured to use the specified API version and endpoint.
