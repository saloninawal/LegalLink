# LegalLink
Legal-Link is a GenAI-powered platform that transforms complex contracts and policies into actionable insights. Instead of just summarizing documents, it empowers users through a Risk &amp; Opportunity.
Legal-Link Prototype
Project Overview
Legal-Link is an interactive prototype designed to simplify complex legal documents. It uses a large language model to analyze, summarize, and answer questions about legal text, making the information more accessible to a non-expert audience. The application is built with Gradio, providing a user-friendly, web-based interface.

Features
Document Simplification: Paste any legal document to receive a concise, easy-to-understand summary.

Key Highlights: The tool automatically extracts and lists important action items and potential risks from the text.

Interactive Chatbot: Engage in a conversation with a chatbot to ask specific questions about the document's contents. The chatbot is "grounded" on the provided text, ensuring its answers are based solely on the document itself.

Technologies Used
Gradio: Used to create the web-based user interface, allowing for a seamless and interactive experience directly in your browser.

Google Gemini API: Powers the backend language model, handling the natural language processing tasks of summarization and conversational AI.

How to Run the Code
This prototype is a single Python script designed to be run in an environment that supports Gradio and the necessary libraries.

Install Dependencies:

!pip install -q gradio requests

Execute the Script:
Save the provided Python code as legal_link_prototype.py and run it.

python legal_link_prototype.py

Access the Interface:
Once the script is running, it will generate a local URL and a public URL. Open the public URL in your browser to access the Legal-Link application.

Usage
Document Analysis: Navigate to the "Document Analysis" tab. Paste your legal text into the provided text box and click the "Process Document" button. The simplified summary and key highlights will appear in the output box below.

Chat with Document: After processing, switch to the "Chat with Document" tab. You can now ask the chatbot questions about the document you just provided. The chat history can be cleared using the "Clear Chat" button.

Disclaimer
This tool is a prototype for educational and demonstrational purposes only. It is not a substitute for professional legal advice. Always consult with a qualified legal professional for any legal questions or concerns.
