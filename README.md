# Doctor Appointment Automation

An automated doctor appointment booking and payment confirmation system built with n8n, Google Sheets, Stripe, Gmail, and Google Calendar.

## Workflows

### 1. Doctor Appointment Booking and Payment

An automated booking workflow that collects patient details, validates the request, checks appointment slot availability, stores bookings in Google Sheets, creates a Stripe Checkout session, and emails the payment link through Gmail.

📁 [View Booking and Payment Workflow](./01-doctor-appointment-booking-payment/)

### 2. Doctor Appointment Payment Confirmation

A Stripe webhook workflow that checks successful payment events, updates the matching booking status in Google Sheets, creates a Google Calendar event, and sends an appointment confirmation email through Gmail.

📁 [View Payment Confirmation Workflow](./02-doctor-appointment-payment-confirmation/)

## Technologies Used

- n8n
- Google Sheets
- Stripe Checkout & Webhooks
- Google Calendar
- Gmail
- JavaScript
