# IBM Dev Day: AI Demystified Hackathon (January 2026)

## Overview

I participated in the IBM Dev Day: AI Demystified Hackathon, a 48 hour virtual event focused on building AI powered applications. The goal of the event was to design and implement a working prototype within a short time frame using large language model capabilities.

This repository documents the concept I worked on, the technical decisions I made during development, and my reflection on the experience.

---

## Project Concept

During the hackathon, I developed an AI powered financial insights feature that analyzes transaction data and generates structured recommendations based on user spending patterns.

The main system flow was:

User Input → API Route → AI Model → Structured Output → Dashboard Display

The focus was on successfully integrating an AI model into a full stack application within 48 hours. Rather than building a fully production hardened system, I prioritized getting the complete pipeline working from end to end.

Key components included:

- AI integration using the Groq API  
- Structured prompt design for consistent outputs  
- Input validation using Zod  
- Rate limiting for AI endpoints  
- Prisma with PostgreSQL for database management  

---

## Reflection

### Activity Description

I participated in the IBM Dev Day: AI Demystified Hackathon, which was a 48 hour virtual event focused on building practical AI powered applications. The goal was to create a working prototype that used large language models to solve a real problem. During the event, I worked on an AI powered financial insights feature that analyzes transaction data and generates helpful recommendations for users based on their spending patterns.

### Technical Decisions

Because the hackathon was limited to 48 hours, I had to make decisions carefully and prioritize what mattered most. I focused on creating a clean and modular structure instead of trying to build too many features. I separated the AI logic from the rest of the application so the system would be easier to maintain and extend later.

I used the Groq API for generating financial insights. I spent time refining prompts so the output would be structured and useful instead of random or overly verbose. I also added input validation using Zod and rate limiting for the AI endpoints to prevent misuse. For the database layer, I used Prisma with PostgreSQL to keep the system type safe and organized.

Instead of trying to perfect everything from the start, I focused on getting the full flow working first. That meant making sure data could move from the user interface to the API, then to the AI service, and back to the dashboard correctly. After that, I improved error handling and performance where possible.

### Contributions

I worked independently on this project. I handled the system design, backend API routes, AI integration, frontend dashboard, authentication setup, database schema design, and deployment. Managing everything myself helped me understand how each layer of the application connects and depends on the others.

### Quality Assessment

Overall, I am satisfied with how the project turned out. The system successfully integrates AI powered financial insights into a full stack application. However, there are still improvements I would make. In a real production setting, I would add stronger monitoring, better logging, and caching to improve response times and reduce API costs. I would also expand testing, especially for AI output consistency and edge cases.

This experience helped me better understand how to integrate AI into a real application while keeping security, structure, and scalability in mind. It also showed me the importance of balancing speed and quality when building under time pressure.

---

## Proof of Participation

See `/proof/ibm_hackathon_email.png` for confirmation of participation in the IBM Dev Day: AI Demystified Hackathon.