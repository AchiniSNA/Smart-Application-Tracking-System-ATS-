# Smart Application Tracking System (ATS)

## Overview

The **Smart Application Tracking System (ATS)** is an AI-powered tool designed to help job seekers optimize their resumes for Applicant Tracking Systems (ATS). By analyzing the match between a resume and a job description, it identifies missing keywords and provides personalized suggestions for improving the resume. The tool leverages generative AI models for text analysis, making it an intelligent assistant for job applicants.

## Features

- **Job Description Analysis**: Paste a job description and let the system analyze it.
- **Resume Upload**: Upload your resume in PDF format for evaluation.
- **Match Score**: The system calculates a match score that indicates how well your resume aligns with the job description.
- **Missing Keywords**: Identifies critical keywords missing in the resume and suggests them.
- **Profile Summary**: Generates a profile summary based on your resume and job description for better resume optimization.
- **Generative AI Integration**: Powered by advanced generative AI models to ensure high-quality analysis and suggestions.

## Technologies Used

- **Python**: Backend development and AI model integration.
- **Streamlit**: For the user interface, enabling easy-to-use web applications.
- **Google Gemini API**: For natural language processing and generative AI-based text analysis.

## Installation

### Clone the Repository
```bash
git clone https://github.com/AchiniSNA/Smart-Application-Tracking-System-ATS-.git
cd Smart-Application-Tracking-System-ATS-
```
### Install Dependencies
```
pip install -r requirements.txt
```
### Set Up Environment Variables
Create a .env file in the root directory and add your GOOGLE_API_KEY:
``` 
GOOGLE_API_KEY=your_google_api_key_here
```
### Run the Application
```
streamlit run app.py
```
This will start a local server and open the app in your web browser.

## Usage
- Enter Job Description: Paste the complete job description into the input box.
- Upload Resume: Upload your resume in PDF format.
- Click "Analyze Resume": After entering the job description and uploading the resume, click the button to analyze.
- View Results: The system will display a match score, missing keywords, and a profile summary.
