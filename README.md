<img width="1682" alt="Screenshot 2024-12-30 at 8 18 48 PM" src="https://github.com/user-attachments/assets/b8aadfdd-ebbf-4815-ac5e-6cd4d0be4e1c" /># AdvanceTalent-ATS
One of the projects I am most proud of is the Smart Applicant Tracking System (Smart ATS) that I developed. This project addresses the challenges faced in recruitment processes by automating candidate screening and ranking.

The project is to assist the users in enhancing their resumes and to match them with job descriptions. It does the following functions;

Resume Analysis: Extracts text from uploaded PDF resumes.
#Job Description Matching: Compares the resumes with the job descriptions and provides the following information:
	•	Match percentage.
	•	Missing keywords.
	•	Summary of the resume content.
#Visualizations:
  •	Bar charts of the best matching resumes.
	•	Word clouds of the most frequent words in the resumes.
	•	Box plots of match percentages.

#Generative AI Integration:
	•	Incorporates Google’s Generative AI
	•	Gemini model for state-of-the-art natural language processing
 Key Features
 Frontend: It is developed using Streamlit for the user interface. 
 Generative AI: To assess the resumes it uses google-generativeai. 
 PDF Parsing:  PyPDF2 library is used to extract text from PDF resumes. 
 Visualizations: The following libraries are used  for generating graphics: Matplotlib, Seaborn and WordCloud. 
 Environment Management: To ensure  that API keys are secured and managed properly the following is used; dotenv. 


Setup Instructions
Install Dependencies: Use the requirements.txt file to install necessary dependencies:
pip install -r requirements.txt
Set Up Environment Variables: Create a .env file and add your Google Generative AI API key:
api_key=your_api_key_here
Run the Application: Start the Streamlit app using the command:
streamlit run HR-Assist.py





