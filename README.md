# Ride Buddy AI Assistant

## Overview

Ride Buddy is an AI-powered motorcycle travel assistant built using Make.com, OpenAI, Telegram, Google Maps, and Google Sheets.

The assistant helps riders discover destinations, find restaurants, log rides, send SOS/help messages, retrieve weather forecast and receive AI-generated recommendations directly through Telegram.

## Workflow Architecture

![Workflow Overview](screenshots/workflow-overview.png.PNG)

## Workflow Process

1. User sends a command through Telegram.
2. Make.com routes the request.
3. External APIs retrieve required information.
4. OpenAI processes and enriches the response.
5. Results are returned to Telegram.
6. Ride data is optionally stored in Google Sheets.

## Features

### Motorcycle Trip Recommendations

* Finds nearby tourist destinations
* Uses Google Maps Places API
* Generates AI-powered travel suggestions

### Restaurant Recommendations

* Discovers highly-rated restaurants and bars
* Uses AI to summarize options
* Provides rider-focused recommendations

### Ride Logging

* Extracts ride information from messages
* Structures data into JSON format
* Stores ride information for future analysis

### Telegram Integration

* Accepts commands through Telegram
* Returns AI-generated responses
* Provides a conversational experience

## Technology Stack

* Make.com
* OpenAI GPT-4o
* Telegram Bot API
* Google Maps Places API
* Google Sheets
* HTTP APIs

## Repository Structure

* screenshots/
* prompts/
* Readme


## Skills Demonstrated

* Workflow Automation
* Prompt Engineering
* API Integration
* AI Assistants
* Data Extraction
* Make.com Automation
* OpenAI Integration
