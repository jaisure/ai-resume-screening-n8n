AI-Powered Resume Screening & Recruitment Automation System

An AI-powered recruitment automation workflow built using n8n, Google Gemini, Telegram, Google Sheets, and Gmail. The system processes resumes, generates ATS-style scores, extracts candidate information, classifies candidates based on a score threshold, and automates recruitment notifications.

🚀 Project Overview

Manually screening resumes can be time-consuming, especially when recruiters receive applications in different formats. This project automates key steps in the initial resume screening process using AI and workflow automation.

Candidates submit resumes through Telegram. The workflow processes PDF resumes and supports ZIP-based resume submissions, extracts text, and uses Google Gemini to evaluate the available candidate information. Based on the screening score, candidate details are recorded in Google Sheets, and an email notification is sent through Gmail.

✨ Key Features

AI-Powered Resume Screening: Uses Google Gemini to analyze resume content and generate ATS-style scores.

PDF and ZIP Processing: Supports PDF resumes and ZIP-based resume submissions through the workflow.

Candidate Information Extraction: Extracts structured candidate details from resume content.

Automated Candidate Classification: Uses conditional logic to classify candidates according to a configurable score threshold.

Google Sheets Integration: Stores screening results for candidate tracking.

Automated Email Notifications: Uses Gmail to send shortlisting or rejection notifications.

Telegram Integration: Provides an interface for submitting resumes to the workflow.

🛠️ Tech Stack

Technology

Purpose

n8n

Workflow automation and orchestration

Google Gemini

AI-based resume analysis and scoring

Telegram

Resume submission interface

Google Sheets

Candidate data storage and tracking

Gmail

Automated candidate notifications

PDF/ZIP processing

Resume file handling and text extraction

🔄 Workflow Architecture

Resume Submission: A candidate submits a resume through Telegram.

File Processing: The workflow identifies the submitted file and routes it through the appropriate PDF or ZIP processing path.

Text Extraction: Resume content is extracted for AI analysis.

AI Evaluation: Google Gemini evaluates the extracted content and generates a structured screening result.

Score-Based Classification: An IF condition checks whether the candidate's score exceeds the configured threshold.

Data Storage: Candidate information and screening results are added to the appropriate Google Sheets records.

Email Notification: Gmail sends the corresponding shortlisting or rejection notification.
