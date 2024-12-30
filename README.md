# AdvanceTalent-ATS
One of the projects I am most proud of is the Smart Applicant Tracking System (Smart ATS) that I developed. This project addresses the challenges faced in recruitment processes by automating candidate screening and ranking.

The project is to assist the users in enhancing their resumes and to match them with job descriptions. It does the following functions;

Resume Analysis: Extracts text from uploaded PDF resumes.</n>
#Job Description Matching: Compares the resumes with the job descriptions and provides the following information:
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
<img width="1682" alt="Screenshot 2024-12-30 at 8 18 48 PM" src="https://github.com/user-attachments/assets/2ed0a5e0-7c19-4158-a3a1-7aba2cb4ff82" />
<img width="1280" alt="Screenshot 2024-12-30 at 8 17 36 PM" src="https://github.com/user-attachments/assets/485bae01-4ef7-4e3b-9411-a94e52838315" />
<img width="1693" alt="Screenshot 2024-12-30 at 8 17 19 PM" src="https://github.com/user-attachments/assets/420382c6-4fea-4450-8402-30a865266e89" />
<img width="1710" alt="Screenshot 2024-12-30 at 8 17 10 PM" src="https://github.com/user-attachments/assets/1251c150-d9a2-4a0c-8b97-aae9b3330e50" />








