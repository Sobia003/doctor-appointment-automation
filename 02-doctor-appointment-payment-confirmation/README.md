# Doctor Appointment Payment Confirmation

## Overview
An automated payment confirmation workflow built with n8n. It receives Stripe payment events, finds the matching appointment booking, updates its payment status in Google Sheets, creates a Google Calendar event, and sends a confirmation email through Gmail.

## Features
- Stripe payment webhook
- Payment status checking
- Booking lookup in Google Sheets
- Automatic booking status update
- Google Calendar event creation
- Appointment confirmation email

## Workflow
1. Stripe sends a payment event to the webhook.
2. The workflow checks the payment status and booking reference.
3. It finds the matching booking in Google Sheets.
4. The booking status is updated to Paid.
5. A Google Calendar event is created.
6. Gmail sends the appointment confirmation email.

## Technologies
- n8n
- Stripe Webhooks
- Google Sheets
- Google Calendar
- Gmail

## Setup Notes
Configure your own Stripe, Google Sheets, Google Calendar, and Gmail credentials after importing the workflow. Replace the placeholder IDs with your own values.
