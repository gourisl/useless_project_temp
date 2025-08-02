
### Technologies/Components Used
For Software:<img width="3188" height="1202" alt="frame (3)" src="https://github.com/user-attachments/assets/517ad8e9-ad22-457d-9538-a9e62d137cd7" />


#  🎯


## Basic Details
### Team Name: Gouri and Barza


### Team Members
- Team Lead: Barza Sajin - Marian Engineering College
- Member 1:Gouri S L - Marian Engineering College


### Project Description
Doc-Digest Pro is a web application designed to streamline document analysis. Users can upload PDF documents to receive an AI-generated concise summary, highlighted key points, and a list of insightful questions based on the document's content.

### The Problem (that doesn't exist)
Are you tired of your eyes glazing over while staring at endless PDF pages? Do you dream of a world where documents read themselves and then tell you exactly what you need to know, without you lifting a finger (or even a brain cell)? We're solving the critical issue of "PDF-induced Narcolepsy" and "Information Overload Syndrome," which has been plaguing humanity since the invention of digital paper.

### The Solution (that nobody asked for)
Doc-Digest Pro is your digital caffeine shot for documents! It's an AI-powered wizard that magically sifts through your PDFs, extracts the essence, sprinkles some highlight fairy dust, and then whispers profound questions into your digital ear. Now you can pretend you've read that 100-page report in seconds and still sound smart in meetings. More time for actual coffee breaks!

## Technical Details
Languages used: JavaScript (with JSX for React)

Frameworks used: React.js

Libraries used:

    pdfjs-dist: For efficient client-side PDF text extraction.

    Tailwind CSS: For rapid and responsive UI development with utility-first styling.

Tools used:

    Node.js: The JavaScript runtime environment for development.

    npm (Node Package Manager): Manages project dependencies and scripts.

    Gemini API: The core AI engine for text summarization, key phrase extraction, and question generation.

    Lovable (or local development environment like VS Code): For online development and depoloyment

For Software:
# Installation
To run this project locally, ensure you have Node.js and npm installed.
Bash

# 1. Clone the repository or create a new React app
# If starting fresh:
npx create-react-app doc-digest-pro
cd doc-digest-pro

# 2. Install the necessary PDF extraction library
npm install pdfjs-dist

After installation, ensure your src/App.js file contains the React code for the Doc-Digest Pro application.

# Run

To start the development server and view the website:
Bash

npm start

This command will typically launch the application in your default web browser at http://localhost:3000.

### Project Documentation
For Software:

# Screenshots (Add at least 3)

<img width="1827" height="853" alt="Screenshot 2025-08-02 140140" src="https://github.com/user-attachments/assets/585b4068-09e6-44d3-9c80-42c7ee1ab4f0" />

<img width="1629" height="893" alt="Screenshot 2025-08-02 140158" src="https://github.com/user-attachments/assets/1610fbd3-dd1b-4d09-ba8f-417c5d50adac" />


<img width="1692" height="1001" alt="Screenshot 2025-08-02 140212" src="https://github.com/user-attachments/assets/fff34e43-cc5a-4b8a-b34e-6c871db17a3d" />


# Diagrams
User Uploads PDF: User interacts with the web interface to select and upload a PDF file.

PDF Text Extraction (Frontend - pdfjs-dist): The pdfjs-dist library, running directly in the user's browser, efficiently parses the uploaded PDF and extracts all textual content.

Text Sent to LLM (Frontend -> Gemini API): The extracted text is then transmitted to the Google Gemini API. This request includes specific prompts tailored for summarization, identification of main points, and generation of relevant questions.

LLM Processes Text (Gemini API): The Gemini large language model processes the input text based on the provided prompts, generating the requested insights.

Results Displayed (Frontend): The AI-generated summary, main points, and questions are received back by the frontend and dynamically rendered on the web page for the user.

### Project Demo
# Video



https://github.com/user-attachments/assets/0f184924-17b7-4e4c-b6b1-ae808a1dccba



## Team Contributions
 Barza Sajin:  Responsible for the overall user interface design and user experience. Ensured responsive and visually appealing layouts across various devices utilizing Tailwind CSS, and implemented interactive elements such as loading indicators and error messages.
  Gouri S L: Focused on the robustness of the AI integration, including developing the callLLM function with exponential backoff for reliable API communication and fine-tuning the prompt engineering to optimize the quality and relevance of the AI-generated summaries, highlights, and questions.

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)



