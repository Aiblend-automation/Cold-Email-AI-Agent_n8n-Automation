# Cold Email AI Agent Automation (n8n)
## Problem
Sending personalized cold emails manually is time-consuming.
Tracking which lead received an email and updating status is also difficult.

## Solution
I built an AI-powered automation using n8n that:
- Reads lead data from Google Sheets
- Uses an AI Agent to generate personalized cold emails
- Sends emails automatically via Gmail
- Updates email status back in Google Sheets

## Tools Used
- n8n
- OpenAI Chat Model
- AI Agent
- Google Sheets
- Gmail

## Workflow Overview
1. Schedule trigger runs the workflow
2. Lead data is fetched from Google Sheets
3. AI Agent generates a personalized cold email
4. Email is sent automatically via Gmail
5. Sheet is updated with sent status

## Use Case
- Lead outreach
- Sales prospecting
- Cold email campaigns
- Automated follow-ups

## Files Included
- `workflow.json` → n8n workflow backup
- `workflow.png` → Visual workflow overview

## How to Reuse This Workflow
1. Download `workflow.json`
2. Import into n8n
3. Connect your credentials (Gmail, OpenAI, Sheets)
4. Update prompt or email content as needed

## Status
This project was built as part of my AI automation learning journey.

