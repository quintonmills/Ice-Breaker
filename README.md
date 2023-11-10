# Ice-Breaker
Personalized AI Conversation Starter
A web application that generates personalized icebreaker conversations using AI.

This project integrates multiple data sources including LinkedIn, Twitter, and SERP API to pull relevant personal and professional details for a specified individual. It then leverages LangChain and OpenAI to craft customized opening messages tailored to that person's background and interests.

The goal is creating an AI-powered tool that makes initiating networking conversations easier and more natural by automatically providing relevant personal hooks and talking points.

**Features**

Keyword extraction from social media profiles
Named entity recognition and relationship mapping
Topic modeling to identify interests and expertise
Contextual response generation with conversational AI
Customized icebreakers for sales, recruiting, networking

**Architecture**

Python backend built with FastAPI web framework
Vue.js frontend with TailwindCSS styling
MongoDB data persistence
Docker containerization for simple deployment

**Getting Started**

# Install dependencies
```pip install -r requirements.txt
# Configure environment variables

cp .env.example .env

# Run backend

uvicorn app.main:app --reload

# Run frontend

cd frontent
npm install
npm run dev
```

**Usage**
Enter the name and social profile URLs for the target individual
Click Generate Icebreaker to analyze their data and create a personalized opener
The customized conversation starter is displayed and can be copied
