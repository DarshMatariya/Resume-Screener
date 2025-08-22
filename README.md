# Resume-Screener

Resume-Screener is a Streamlit-based application that uses Google’s Generative AI to analyze and evaluate resumes against job descriptions. The app helps recruiters and job seekers by providing professional insights about resume-job description compatibility, highlighting strengths, weaknesses, and providing a percentage match score based on ATS (Applicant Tracking System) principles.

## Features

- Upload a resume in PDF format.
- Input a job description.
- Get AI-generated evaluation of how well the resume matches the job description.
- Receive feedback on strengths, weaknesses, missing keywords, and final thoughts.
- Percentage match score between resume and job description based on ATS.

## Live Demo

Try the application live on Streamlit Cloud:

[https://resume-ats-score.streamlit.app/](https://resume-ats-score.streamlit.app/)

## Technologies Used

- Streamlit for the web interface
- Google Generative AI API (Gemini 2.0 model) for content generation
- PyMuPDF (fitz) for PDF text extraction
- Python Dotenv for environment variable management

## Setup and Installation

1. Clone the repository:
```git clone https://github.com/DarshMatariya/Resume-Screener.git```
```cd Resume-Screener```

2. Install dependencies:
- pip install -r requirements.txt

3. Create a `.env` file based on the `.env.example` (if available) or manually add your Google API key:
- GOOGLE_API_KEY="your_google_api_key_here"

4. Run the Streamlit app locally:
- streamlit run main.py


## Usage

- Enter the job description text.
- Upload a PDF resume.
- Click on "Tell Me About the Resume" to get an expert evaluation.
- Click on "Percentage match" to get a percentage score and feedback on keyword matches.

## Notes

- Make sure you have a valid Google Generative AI API key and quota.
- The app currently supports PDF resume uploads only.
---






  



