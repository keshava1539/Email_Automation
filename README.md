## AI-Powered Email Automation
## 📧 Overview
-This project showcases an intelligent system that automates the entire process of drafting and sending emails using a Large Language Model (LLM). By providing a simple user request and context, the application leverages the LangChain framework to generate a complete, structured email in JSON format. The system then securely dispatches the email using Python's native smtplib library, demonstrating a full end-to-end automation pipeline.

## 👥 Team Members

-Kallutla Veera Keshava Reddy

## 🧠 Project Highlights

-Generative AI Integration: Utilizes the LangChain framework to interface with a powerful LLM (Llama from groq) hosted on Hugging Face, enabling dynamic content creation.

-Advanced Prompt Engineering: Implements sophisticated prompt templates that instruct the AI to return a clean, structured JSON object containing the recipient, subject, body, and required SMTP details.

-End-to-End Automation: Creates a seamless workflow from receiving a user's intent to the final, successful dispatch of the email.

-Robust Data Parsing: Employs regular expressions to clean and validate the raw text output from the LLM, ensuring it can be reliably parsed as a JSON object.

-Secure Email Dispatch: Integrates Python's smtplib with SSL encryption (smtplib.SMTP_SSL) for secure and authenticated email sending.

-Flexible and Reusable: The architecture is designed to be easily adapted for different email providers and LLMs with minimal changes.

## 🔍 Techniques Used

-Python: Primary programming language for the entire application.

-LangChain: Framework for developing applications powered by language models.

-Hugging Face API: Used for accessing the LLM inference endpoint.

-OpenAI Library: Leveraged to create a compatible client for the Hugging Face endpoint.

-smtplib & ssl: Python libraries for sending emails securely over SMTP.

-JSON: Used as the structured data format for communication between the LLM and the email sending module.

-Regular Expressions (re): Applied for cleaning and pre-processing the AI's output.

## 📁 Files

-model.ipynb: The main Jupyter Notebook containing all code for prompt design, LLM integration, response parsing, and the email sending function.

## 📅 Timeline

-Project developed and completed in July 2025.
