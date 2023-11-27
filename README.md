# Intelligent-College-Assistant-Using-OpenAI-APIs
The project aims to develop an intelligent chatbot system integrated with the college website using OpenAI API and advanced technologies. The existing college website lacks an efficient communication channel, requiring users to navigate through various pages to find information. The proposed chatbot system addresses this limitation by providing a user-friendly interface for students, faculty, and visitors to interact with the website. Leveraging natural language processing and machine learning algorithms, the chatbot can understand user queries and provide accurate and personalized responses related to courses, faculty members, and other important details. By utilizing LangChain Vector Database and OpenAI API, the chatbot enhances the user experience, streamlines information retrieval, and offers quick access to relevant information, ultimately improving the overall efficiency of the college website.

# SOFTWARE REQUIRMENTS
  ●	Operating System: Windows , macOS, or Linux
  
  ●	Python: Version 3.7 or higher
  
  ●	Integrated Development Environment (IDE): Visual Studio Code or any preferred Python IDE
  
  ●	Dependencies:
  
      ➢	streamlit
      ➢	python-dotenv
      ➢	PyPDF2
      ➢	langchai
      ➢	numpy
      ➢	faiss-cpu
      ➢	OpenAI API

![image](https://github.com/Karthikeya2302/Intelligent-College-Assistant-Using-OpenAI-APIs/assets/130597328/c72fb0fd-bf8b-49cc-9aa3-8a6edba198f8)

# DEVELOPMENT ENVIRONMENT SETTING
To set up the development environment for the intelligent college assistant chatbot 
system, follow these steps:
1. Install Python:
 - Download the latest version of Python from the official Python website.
 - Run the installer and follow the on-screen instructions to complete the installation.
 - Make sure to select the option to add Python to the system PATH during the installation 
process.

2. Install Required Packages:
 - Open a command prompt or terminal.
 - Navigate to the project directory using the `cd` command.
 - Run the following command to install the necessary packages:
 ```
 pip install streamlit dotenv PyPDF2 langchain
 ```
 This will install the required packages for running the chatbot system.
 
3. API Configurations:
 - Obtain an OpenAI API key by signing up for an account on the OpenAI website.
 - Create a file named `.env` in the project directory.
 - Add the following line to the `.env` file, replacing `YOUR_API_KEY` with your actual
 - OpenAI API key:
 ```
OPENAI_API_KEY=YOUR_API_KEY
 ```
 - Save the `.env` file.
 - 
4. Environment Setup Verification:
 - Run the following command to verify that the development environment is set up correctly:
 ```
 python app.py
 ```
 - If the development environment is properly configured, the chatbot system will start 
running and can be accessed through the provided URL.

By following these steps, we can successfully set up the development environment for the 
intelligent college assistant chatbot system.

"To customize the chat bot with your own information, simply substitute the existing data files in the data folder with your personal data."
