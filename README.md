# Identifying Master Service Agreement Changes Using Python

In this project, I used Python to develop a tool that can be used to identify the changes that have been made in an updated Master Service Agreement(MSA). It consists of 6 parts:
* 1. Web scraping to automatically download the MSA files from the Salesforce website for testing
* 2. Extracting text from the PDF files
* 3. Cleaning up the extracted text using regular expressions
* 4. Using a pre-trained NLP model to tokenize the text into sentences
* 5. Comparing two files sentence by sentence
* 6. Testing with Salesforce MSA files
