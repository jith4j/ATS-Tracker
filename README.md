# ATS Resume Evaluator using Google Gemini API

This project is an **ATS Resume Evaluator** powered by **Google Gemini AI**. It helps job seekers align their resumes with job descriptions by providing a detailed analysis of keyword matches, missing keywords, and suggestions for improvement. By increasing the alignment between the resume and job description, this tool aims to boost the chances of passing through Applicant Tracking Systems (ATS) used by recruiters.

## Features
- **Resume Evaluation**: The tool compares a given resume with a job description.
- **Keyword Matching**: It identifies matching and missing keywords between the resume and job description.
- **Improvement Suggestions**: Provides specific recommendations on how to adjust the resume to reach an alignment of above 85%.
- **Matching Percentage**: Calculates a match percentage between the resume and the job description, giving a quantitative analysis.
  
## Technology Stack
- **Python**: The programming language used for the core logic and API interactions.
- **Google Gemini API**: Used for Natural Language Processing (NLP) and generating resume analysis based on the given job description.
- **Google Colab**: A cloud-based platform to run the Python code and interact with the API.

## Prerequisites
- **Google API Key**: You need a valid Google API key to use the Gemini API.
- **Google Colab Account**: The script runs on Google Colab, so a Google account is required.
- **Python Libraries**: The following Python packages are used:
  - `google-generativeai`

## How to Use
1. Open the project in Google Colab.
2. Insert your Google API Key in the provided section of the script.
3. Insert your resume text and the job description.
4. Run the cells, and the ATS evaluator will output:
   - Percentage match between your resume and job description.
   - Matching and missing keywords.
   - Suggestions for improving the resume to increase ATS compatibility.
