n8n Lead & Sales Automation

A demo automation built with n8n to automate the lead reception and sales process.

What it does

- Receives a new lead from a form
- Checks if the customer already exists
- Creates a new customer or updates an existing one
- Generates a unique Lead ID
- Assigns the lead to a sales representative based on the selected service
- Sends a WhatsApp welcome message
- Sends a meeting booking link
- Creates the meeting automatically in Google Calendar
- Sends a booking confirmation
- Sends a reminder before the meeting

Demo Stack

- n8n
- Tally
- Google Sheets
- Evolution API
- WhatsApp
- Google Calendar

Demo Flow

Tally Form
↓
n8n Webhook
↓
Lead Validation & Duplicate Check
↓
Create / Update Customer
↓
Service-Based Sales Assignment
↓
WhatsApp Message
↓
Meeting Booking
↓
Google Calendar
↓
WhatsApp Confirmation
↓
Meeting Reminder

Production Plan

The demo integrations can be replaced with production services:

- Tally → Facebook Lead Ads
- Google Sheets → Company CRM
- Evolution API → WhatsApp Business API

The core automation logic is designed to remain mostly the same while replacing the external integrations.

Project Status

✅ Lead reception
✅ Duplicate detection
✅ Customer creation/update
✅ Sales assignment
✅ WhatsApp messaging
✅ Meeting booking
✅ Google Calendar integration
✅ Meeting confirmation
✅ Reminder automation

Status: Demo completed
