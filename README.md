# AI-Powered HR Screening Automation

An automated recruitment workflow that uses AI to analyze job applications and streamline the candidate screening process. This system helps HR teams efficiently evaluate resumes, classify candidates, and automate communication with applicants.

---

## Project Overview

Recruitment teams often receive hundreds of job applications, making manual resume screening time-consuming and inefficient.

This project implements an **AI-powered automation workflow** that:

- Collects job applications through an online form
- Extracts and analyzes candidate resumes
- Evaluates candidate-job compatibility
- Categorizes applicants based on suitability
- Sends automated responses to candidates
- Provides HR teams with detailed candidate insights

The automation significantly reduces manual screening effort while improving consistency in candidate evaluation.

---

## Key Features

### Automated Job Application Processing
Candidates submit their applications through an online form with personal details, resume, and cover letter.

### Resume Parsing and Processing
The system downloads the uploaded resume and converts it into structured text for analysis.

### AI-Based Candidate Evaluation
An AI model analyzes the resume and generates:

- Compatibility score
- Technical skills analysis
- Candidate strengths
- Potential concerns
- Relevant work experience

### Candidate Classification
Candidates are automatically categorized into three groups:

- **Strong Candidate** – Highly suitable for the role  
- **Moderate Candidate** – Potential fit but requires further review  
- **Weak Candidate** – Not suitable for the role  

### Automated Candidate Communication
Based on classification, the system sends personalized emails:

- Interview invitation for strong candidates
- Application status update for moderate candidates
- Rejection message with feedback for weak candidates

### HR Notification System
HR receives a detailed candidate report containing:

- Resume summary
- Compatibility score
- Key strengths
- Skill breakdown
- Suggested interview questions

---

## Workflow Architecture

The system follows a sequential workflow pipeline:

---

## Technologies Used

### Automation Platform
- n8n

### Form Management
- Jotform

### AI Resume Analysis
- OpenAI API

### Resume Parsing
- LlamaCloud Parsing API

### Email Automation
- Gmail API

---

## How It Works

### Step 1 — Candidate Application
Candidates fill out an online job application form and upload their resume.

### Step 2 — Workflow Trigger
Form submission automatically triggers the recruitment automation workflow.

### Step 3 — Resume Processing
The system downloads the resume and extracts structured text from the document.

### Step 4 — AI Resume Analysis
The AI model evaluates the resume and generates structured insights including skills, experience, and candidate suitability.

### Step 5 — Candidate Categorization
Based on the compatibility score, candidates are categorized as strong, moderate, or weak matches.

### Step 6 — Automated Communication
Candidates receive personalized email updates regarding their application status.

### Step 7 — HR Insights
The HR team receives a detailed analysis report of strong candidates along with recommended interview focus areas.

---

## Benefits

- Reduced manual resume screening time
- Improved recruitment efficiency
- Consistent candidate evaluation
- Automated communication with applicants
- Structured insights for HR decision-making

---

## Potential Improvements

- Integration with Applicant Tracking Systems (ATS)
- Automated interview scheduling
- Candidate analytics dashboard
- Multi-language resume analysis
- Integration with job portals

---

## Use Cases

- Recruitment automation for startups
- HR teams handling high application volumes
- AI-based applicant screening systems
- Automated hiring workflows

---

## Repository Structure

---

## Future Scope

The system can be expanded into a full **AI-powered recruitment assistant**, including:

- Interview scheduling automation
- Candidate ranking dashboard
- Predictive hiring analytics
- Integration with LinkedIn and job portals

---

## Suggested GitHub Topics
