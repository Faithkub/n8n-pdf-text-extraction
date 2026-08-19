# n8n-pdf-text-extraction
n8n workflow for extracting text from a PDF and answering questions using a Groq LLM.

Project title

PDF Text Extraction and Question Answering using n8n

Description

The workflow extracts text from a PDF document and uses a Large Language Model to answer questions based on the extracted content.

Workflow
<img width="1906" height="706" alt="image" src="https://github.com/user-attachments/assets/1f811128-aca9-4681-a9a7-474e1556b50a" />


1. Manual Trigger

Starts the workflow manually.

2. Read/Write Files from Disk

Reads the PDF file from the local .n8n-files directory.

3. Extract from File

Uses the Extract from PDF operation to extract the text.

4. Basic LLM Chain

Uses the extracted PDF text as context and asks the LLM to answer the user's question.

5. Groq Chat Model

Provides the language model used by the Basic LLM Chain.
