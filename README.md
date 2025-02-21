# Part-A-Docs
# DeepSeek Job Tracker - Part A Documentation

## Table of Contents
- [Project Management & Progress](#project-management--progress)
- [Project Overview](#project-overview)
- [Functionality & Features](#functionality--features)
- [Target Audience](#target-audience)
- [Tech Stack](#tech-stack)
- [Dataflow Diagram](#dataflow-diagram)
- [Application Architecture](#application-architecture)
- [User Stories](#user-stories)
- [Wireframes](#wireframes)

## Project Overview

DeepSeek Job Tracker is an AI-powered job application management platform designed to help professionals, especially those in career transition, effectively manage their job search process. The platform leverages artificial intelligence to analyze resumes and match them with suitable job opportunities.

### Purpose

The platform serves three main purposes:
1. Simplify the job application process through AI-driven insights
2. Provide intelligent job matching based on skills and experience
3. Offer comprehensive application tracking and management

### Target Audience

Our platform primarily targets:
- Career transition professionals
- Job seekers in the tech industry
- Professionals with diverse skill sets

## Tech Stack

### Frontend
- React.js
- Material UI
- TypeScript
- TailwindCSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

### External APIs
- DeepSeek AI for resume analysis
- Brave Search API for job recommendations

### Deployment
- Railway (Backend)
- Vercel (Frontend)

## User Stories & Personas

### Career Transition Professional - Primary Persona

[Insert screenshot of Osman's persona card here]
<img width="1463" alt="Screenshot 2025-02-16 at 11 12 35 PM" src="https://github.com/user-attachments/assets/d18b681c-4096-47cd-b219-1d2b265e3e3a" />

**Osman's Profile:**
- Background: Mechanical Engineering degree, recent IT Web Development
- Goals: Transition to tech industry
- Frustrations: Complex skill presentation challenges

### Initial User Stories

#### Guest User
* As a guest, I want to learn about the platform's features
* As a guest, I want to try basic resume analysis
* As a guest, I want to see example job matches
* As a guest, I want to create an account

#### Registered User
- As a registered user, I want to upload my resume
- As a registered user, I want to create my profile
- As a registered user, I want to find matched jobs for my resume
- As a registered user, I want to link my social and professional profiles
- As a registered user, I want to track my applications
- As a registered user, I want to get AI feedback
- As a registered user, I want to visit suggested job application links and apply
- As a registered user, I want to showcase my applied jobs on my personal website/portfolio

### Refined User Stories

After developing our primary persona, we refined our user stories:

<img width="1137" alt="Screenshot 2025-02-16 at 11 23 23 PM" src="https://github.com/user-attachments/assets/5223a06b-5fc7-4535-ad29-bb4e4e70ce7c" />

#### Career Transition Focus
* As a career changer, I want my resume analyzed by AI so that I can effectively highlight my diverse educational background
* As a professional with varied experience, I want feedback on how to present my transferable skills from management to tech
* As a mature student, I want guidance on highlighting my recent tech education alongside my extensive work experience

## Application Architecture

<img width="805" alt="Screenshot 2025-02-16 at 11 04 47 PM" src="https://github.com/user-attachments/assets/a63b3c86-3cfe-4e6c-95c3-9176a1f3e6d9" />


Our application follows a modern three-tier architecture:
1. Frontend (React) handling user interactions
2. Backend (Node.js/Express) processing requests
3. MongoDB database for data persistence

## Data Flow Diagram

<img width="769" alt="Screenshot 2025-02-16 at 10 54 40 PM" src="https://github.com/user-attachments/assets/54cd0e8d-5f56-4a6b-a3ea-8acae176abc8" />


The diagram illustrates:
- User authentication flow
- Resume upload and analysis process
- Job search and recommendation system
- Application tracking workflow

## Future Development Plans

### Immediate Goals
1. Complete core functionality
   - Resume analysis
   - Job matching
   - Application tracking

### Future Expansion
1. Local Partnerships
   - Collaboration with Melbourne and Sydney job agencies
   - Specialized portals for local opportunities

2. Industry Specialization
   - Partnerships with tech companies
   - Custom AI analysis for specific sectors

3. Community Features
   - Mentorship opportunities
   - Success stories
   - Career transition guides
## Trello Board
Our Trello board can be viewed [here](https://trello.com/b/TIJBsAuq/careerlens).