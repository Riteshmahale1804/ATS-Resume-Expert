# ATS-Resume-Expert
This is a Streamlit application that allows users to upload a resume (in PDF format) and input a job description. It uses the Gemini model from Google's Generative AI to generate responses based on the job description and the content of the resume.

## Installation

Clone the repository :

bash
git clone https://github.com/your_username/ats-resume-expert.git

pip install -r requirements.txt



## Setting Up Google API Key
This application utilizes the Google Generative AI API for generating responses. To use the API, you'll need to obtain an API key from the Google Cloud Console.

## Go to the Google MakerSuite.
https://aistudio.google.com/app/apikey
 
Set the environment variable GOOGLE_API_KEY to your API key:


## Usage
Run the Streamlit app:
streamlit run app.py

1.Open your web browser and navigate to the provided URL.
2.Input the job description and upload a resume in PDF format.
3.Click on the "Tell Me About the Resume" button to generate a response based on the resume and job description.
4.Optionally, click on the "Percentage Match" button to determine the percentage match between the resume and job description.




