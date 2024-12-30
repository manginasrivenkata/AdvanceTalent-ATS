# AdvanceTalent-ATS
One of the projects I am most proud of is the Smart Applicant Tracking System (Smart ATS) that I developed. This project addresses the challenges faced in recruitment processes by automating candidate screening and ranking.

The project is to assist the users in enhancing their resumes and to match them with job descriptions. It does the following functions;

<n>Resume Analysis: Extracts text from uploaded PDF resumes.</n>
<b>Job Description Matching: Compares the resumes with the job descriptions and provides the following information:</b>
	•	Match percentage.</n>
	•	Missing keywords.</n>
	•	Summary of the resume content.</n>
#Visualizations:
        •       Bar charts of the best matching resumes.</n>
	•	Word clouds of the most frequent words in the resumes.</n>
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
<img width="1697" alt="Screenshot 2024-12-30 at 8 35 45 PM" src="https://github.com/user-attachments/assets/ab0fda84-60f6-4e93-8523-8c4054685aba" />
<img width="1660" alt="Screenshot 2024-12-30 at 8 35 02 PM" src="https://github.com/user-attachments/assets/7fc909b9-7ac2-489c-9614-358863e8c1fa" />
<img width="747" alt="Screenshot 2024-12-30 at 8 36 09 PM" src="https://github.com/user-attachments/assets/82f563af-8e50-4966-b839-634cd1c3323e" />
<img width="1195" alt="Screenshot 2024-12-30 at 8 35 59 PM" src="https://github.com/user-attachments/assets/26e105be-a944-4fc4-85b4-1e41ceee106e" />








