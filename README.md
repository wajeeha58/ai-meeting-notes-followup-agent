# ai-meeting-notes-followup-agent

# AI-Meeting Notes & Follow-Up Agent

# Overview

AI Meeting Notes & Follow-Up Agent is an intelligent workflow automation system built using n8n, Groq LLM, Gmail, and Google Calendar.

The agent analyzes meeting transcripts, extracts key discussion points and action items, generates professional meeting summaries, automatically creates calendar events, and sends follow-up emails to participants.

# Features
Meeting Analysis
Extracts meeting title
Generates concise meeting summaries
Identifies key discussion points
Detects action items

# AI-Powered Follow-Up
Generates professional follow-up emails
Summarizes meeting outcomes
Includes agreed action items
Uses business-friendly communication

# Calendar Automation
Creates Google Calendar events automatically
Extracts event date and time from meeting discussions
Schedules follow-up meetings

# Email Automation
Sends automated follow-up emails through Gmail
Maintains professional formatting
Includes meeting decisions and next steps

# Workflow Architecture
User Meeting Transcript
          ↓
     AI Agent
          ↓
 Structured Output Parser
          ↓
 Google Calendar Event
          ↓
 Gmail Follow-Up Email
 
# Tech Stack
n8n
Groq LLM
Gmail API
Google Calendar API
Structured Output Parser
JSON

# Workflow Nodes
# 1. Chat Trigger

Receives meeting transcript input from the user.

# 2. AI Agent

Analyzes the meeting transcript and generates:

Meeting title
Meeting summary
Key discussion points
Action items
Follow-up email
Event date
Event time

# 3. Google Calendar Node

Creates calendar events automatically based on extracted meeting information.

# 4. Gmail Node

Sends professional follow-up emails to meeting participants.

# Sample Input

Meeting with John regarding AI Automation.

Need to send pricing proposal by Friday.
Schedule a product demo for next week.

# Sample Output

# Meeting Summary  
Discussion regarding AI automation opportunities and next steps.

# Action Items
- Send pricing proposal by Friday
- Schedule product demo next week
- 
# Follow-Up Email
Dear John,

I wanted to follow up on our meeting and confirm the action items discussed.

As agreed, we will send a pricing proposal by Friday and schedule a demo for next week.

Thank you for taking the time to meet with us.

Best regards,

AI Meeting Assistant
Automated Meeting Intelligence

# Project Screenshots
Workflow Architecture
AI Agent Configuration
Structured Output Parser
Google Calendar Event Creation
Automated Gmail Follow-Up Email
End-to-End Workflow Execution

# Business Value
Reduces manual note-taking
Automates meeting follow-ups
Improves productivity
Ensures action items are tracked
Streamlines meeting management

# Future Enhancements
Meeting transcript ingestion from Zoom/Google Meet
Slack notifications
CRM integration
Multi-user support
RAG-powered meeting memory
Sentiment analysis
Task management integration

# Author

Wajeeha Sheikh

https://www.linkedin.com/in/twajeeha | https://github.com/wajeeha58/ai-meeting-notes-followup-agent 
