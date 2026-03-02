# RecruitIQ — AI-Powered Recruiting Assistant

> Helping HR teams analyse resumes faster, score candidates consistently, 
> and generate interview emails automatically.

## Live Demo
[Live Video Demo](https://drive.google.com/file/d/1kOkG6458RDwv7-1MD2StS1Fh4LN7AmPs/view?usp=sharing)

## The Problem
HR teams waste hours manually screening resumes and writing repetitive 
interview emails. RecruitIQ automates the analysis and communication layer 
so recruiters focus on decisions, not admin.

## What It Does
- Accepts resume input and extracts key candidate information automatically
- Scores candidates against role criteria using AI analysis
- Maintains a tracker of evaluated candidates
- Generates personalised interview invitation emails ready to send

## How It Works
[Main Workflow](https://github.com/user-attachments/assets/ac56ff82-7d15-42b0-a19c-fde508e83642) | 
[Resume Uploader to Google Drive](https://github.com/user-attachments/assets/6a793b88-340d-474e-ac3f-43f274bc89e2) | 
[Interview Email Sender](https://github.com/user-attachments/assets/d80b8aca-b91a-4ed2-afab-c2d75239b8a5) 


The tool runs on an agentic workflow built in n8n, using Gemini as the 
reasoning engine. Each resume triggers a sequential chain: extraction → 
scoring → tracker update → email generation.

## Screenshots
[Dashboard](https://github.com/user-attachments/assets/1b35d844-fe83-4c79-960e-c8f1dd396d85) |
[Job Description Detail Page](https://github.com/user-attachments/assets/234b9631-c5d6-4290-b3c2-943ebb024178) |
[Candidate Detail Page](https://github.com/user-attachments/assets/480ef4f4-32df-46b6-805a-3c989bbef3e4) |
[Interview Scheduler Pop-up](https://github.com/user-attachments/assets/640f0378-0978-40b2-907e-e63313e59a19)


## Tech Stack
- **Workflow automation:** n8n
- **Frontend:** Lovable
- **AI reasoning:** Gemini
- **Built as part of:** Certification in Product Management & Agentic AI, IIT Patna (2025–2026)

## Why I Built This
This project was part of my agentic AI certification at IIT Patna. 
The design challenge that interested me most was how to structure 
multi-step AI reasoning into a reliable, repeatable workflow — 
the same core problem at the heart of conversational agent design.
