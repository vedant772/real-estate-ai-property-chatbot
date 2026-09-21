# real-estate-ai-property-chatbot
AI-powered conversational property discovery system built with n8n, Google Sheets and LLMs.
# Real Estate AI Property Chatbot

An AI-powered conversational property discovery system built for real estate businesses.

The system allows customers to describe the property they are looking for using natural language and automatically searches the available property inventory for relevant matches.

## Example

Customer:

> 3bhk in Juhu around 4 crore

The system understands:

- Property type: 3 BHK
- Location: Juhu
- Budget: ₹4 crore

It then searches the property inventory and returns relevant properties conversationally.

## Architecture

Customer
↓
Webhook
↓
AI Requirement Extraction
↓
Google Sheets Property Inventory
↓
Property Matching
↓
AI Response Generation
↓
Customer

## Features

- Natural-language property search
- AI requirement extraction
- Google Sheets inventory integration
- Budget normalization
- Location matching
- Property-type matching
- Conversational property discovery
- Automated responses

## Tech Stack

- n8n
- Google Sheets
- JavaScript
- LLM / AI
- Webhooks

## Project Status

Currently under development.

## Goal

Build a conversational property discovery system that allows real estate customers to search property inventory without filling out traditional forms.
