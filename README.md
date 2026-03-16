# AI Email Summarizer (n8n + OpenAI)

## Overview
This workflow summarizes incoming emails using AI.  
It listens for new emails using a Gmail trigger, summarizes the email content using OpenAI, and saves the summary in Google Sheets.

## Tools Used
- n8n
- OpenAI API
- Gmail Trigger
- Google Sheets

## Workflow
Gmail Trigger → AI Email Summary → Save Summary in Google Sheets

## How It Works
1. A new email arrives in Gmail.
2. Gmail trigger activates the workflow.
3. The email content is sent to OpenAI.
4. AI generates a summary of the email.
5. The summary is stored in Google Sheets.

## Setup
1. Import the `workflow.json` file into n8n.
2. Configure Gmail, OpenAI, and Google Sheets credentials.
3. Activate the workflow.

## Note
API keys are not included in this repository for security reasons.
