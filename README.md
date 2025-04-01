# celere_bird
Welcome to celere bird, a revolutionary SaaS AI application designed to automate your email management process. This documentation will guide you through the features, setup, and usage of the app.

Overview
InboxRadarAI integrates seamlessly with your Gmail inbox, utilizing advanced Large Language Model (LLM) technology, Gemini, to intercept, process, and categorize your emails with precision.

Key Features
Intelligent Email Tagging and Classification: Automatically tags and classifies emails, allowing for custom label creation and automated labeling.
AI Suggestions and Autocomplete: Assists in drafting emails with AI-powered suggestions and autocomplete functionality.
AI Insights: Provides short summary of email content.
Multi-Inbox Support: Supports managing multiple Gmail inboxes within a single interface.
Email-Client: Capable of recieving, sending and replying to threads.
Subscription Tiers: Offers both free and pro tiers, integrated with Stripe for payment processing.
Getting Started
Technology Stack
Frontend:

Next.js
React
TypeScript
TailwindCSS
Backend:

Node.js
TypeScript
Prisma ORM
Database:

PostgreSQL
Authentication:

Auth.js (OAuth for Google)
AI & APIs:

Gemini API
Gmail API
Payment Integration:

Stripe
DevOps:

Vercel (for deployment)
Installation
Setup
Clone The Repo
Setup stripe product. Save new priceId to config/app.ts
Setup gmail API credentials, gemini API credentials
Setup postgreSQL database
Setup Resend
