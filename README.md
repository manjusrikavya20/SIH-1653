# Smart India Hackathon Workshop
# Date:15/03/2025
## Register Number:212224040186
## Name:MANJUSRI KAVYA R
## Problem Title 
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

1.Candidate & Interviewer Login:

Unique ID generation for both candidates and interviewers.

Secure authentication system.

2.Start of Interview

Audio recording for security and transparency.

Speech-to-text conversion for real-time processing.

3.Intelligent Question Selection

AI-driven dynamic question selection based on:

Candidate's area of expertise.

Job role requirements.

Previous responses (adaptive questioning).

4.Candidate Response Processing

Microphone turned ON:

Responses converted to text using speech recognition.

AI evaluates correctness, depth, and relevance.

Data securely stored along with transcripts.

Microphone turned OFF:

Session either ends or proceeds to manual evaluation.

5.Real-time AI-driven Scoring System

The system grades:

--> Interviewers (based on relevance of questions asked).

--> Candidates (based on response accuracy and relevance).

--> Ensures bias-free and transparent evaluation.

6.Final Evaluation & Post-Interview Feedback

AI generates a comprehensive report, including:

Overall candidate score based on subject knowledge.

Comparative analysis against other applicants.

Personalized feedback for improvement.

7.Data Training & Continuous Improvement

All training data (transcripts & scores) are stored securely.

The DRDO AI system refines its models for better future evaluations.

## Proposed Solution / Architecture Diagram

![image](https://github.com/user-attachments/assets/31bd314e-af84-4aa1-a6de-d58519773c19)

## Use Cases

1.Recruitment Interviews: Evaluating fresh applicants based on domain knowledge.

2.Promotion Evaluations: Assessing DRDO scientists for higher positions.

3.Training Data for AI Models: Improving automated question-answer relevance detection.

## Technology Stack

1.Frontend: React.j

2.Backend: Node.js, Express.js

3.Database: MongoDB

4.Speech-to-Text Processing: Google Speech API

5.AI/ML Model for Grading: TensorFlow

6.Authentication & Security: OAuth

7.Cloud Hosting: AWS

## Dependencies

1.AI Model Training Data: Previous interview records

2.Secure Storage System: Encryption for recordings & transcripts

3.Speech Processing Module: Integration with NLP services

4.Scoring Algorithm: Machine learning model for question-response analysis
