# *Job Seeker Assistant Chatbot*
A conversational AI assistant that helps users build resumes, write cover letters, and prepare for interviews, with a focus on tech industry positions.

## Project Overview
This project implements a chatbot using the DialoGPT model to provide personalized assistance throughout the job application process. The chatbot utilizes a conversational interface within a Jupyter Notebook and maintains context across conversation turns to deliver a natural interaction experience.

## Features
### Resume Building Assistance
 - Provides multiple resume templates (chronological, functional, combination, technical)
 - Suggests ATS-optimized keywords for different tech roles
 - Offers section-by-section guidance with examples and tips
 - Analyzes user queries to provide relevant resume advice

### Cover Letter Creation
  - Offers multiple cover letter templates (standard, modern, technical)
  - Provides guidance for each section of the cover letter
  - Includes tips for analyzing job descriptions
  - Offers personalization strategies and common mistake avoidance

### Interview Preparation
 - Contains a database of common interview questions by category
 - Provides specialized questions for various roles (software engineer, data scientist, etc.)
 - Offers tips for different interview formats (phone, video, in-person, technical)
 - Includes STAR method guidance for behavioral questions
 - Conducts mock interviews with relevant questions
 - Provides salary negotiation tips

### Conversation Management
  - Maintains context across multiple conversation turns
  - Detects conversation topics automatically
  - Provides appropriate specialized knowledge based on detected intent
  - Allows conversation history tracking and summarization

## Technical Implementation
The project is structured in a modular way, with separate components that work together:
  * Environment Setup: Configuration of libraries and parameters
  * Model Initialization: Loading the DialoGPT model and tokenizer
  * Basic Conversation Engine: Core text generation functionality
  * Context Management System: Maintaining conversation history and context
  * Resume Module: Specialized knowledge about resume creation
  * Cover Letter Module: Specialized knowledge about cover letters
  * Interview Preparation Module: Interview questions and guidance
  * Final Integration with UI: Interactive interface in Jupyter Notebook

## Dependencies
All required dependencies are listed in the `requirements.txt` file.

## Installation
  - Clone this repository:

```python
git clone https://github.com/sree-9523/Job-Seeker-Assistant-Chatbot.git
```
  - Install required packages:

```python
pip install -r requirements.txt
```

  - Run `Jupyter Notebook`
  - Open the `Job_Seeker_Assistant_Chatbot.ipynb` notebook and run all cells

## Usage
After running all cells in the notebook, an interactive chat interface will appear where we can:
  * Type questions or requests about job seeking in the text box
  * Click the "Send" button or press Enter to submit your message
  * Read the chatbot's response in the conversation display
  * Use the "Reset Chat" button to clear the conversation history
  * Use the "End Conversation" button to terminate the chatbot session

Example queries:
  * "What resume template should I use for a software engineering position?"
  * "How should I write the opening paragraph of my cover letter?"
  * "Can you give me some common interview questions for a data scientist role?"
  * "How should I prepare for a technical interview?"

## Project Structure
The project is organized into modular components:
  * `Job_Seeker_Assistant_Chatbot.ipynb`: Main Jupyter notebook containing all code
  * `README.md`: This file
  * `requirements.txt`: List of required Python packages

## Future Improvements
  - Fine-tuning the DialoGPT model on job-seeking specific data
  - Adding support for resume document analysis and feedback
  - Implementing a web-based interface for broader accessibility
  - Expanding the question database for more specialized roles
  - Adding support for non-tech industry roles
  - Implementing more sophisticated intent detection using machine learning
  - Integrating with job search APIs to provide real-time job recommendations

## License
MIT License

Copyright (c) 2025 sree-9523

## Acknowledgments
- Microsoft for the DialoGPT model
- Hugging Face for the Transformers library
- The open-source community for various libraries used in this project






