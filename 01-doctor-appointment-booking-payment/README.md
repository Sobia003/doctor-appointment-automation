# Doctor Appointment Booking and Payment

## Overview
An automated appointment booking workflow built with n8n. It collects patient details, checks appointment slot availability, stores booking information in Google Sheets, creates a Stripe Checkout payment session, and emails the payment link through Gmail.

## Features
- Patient appointment form
- Patient information validation
- Appointment slot availability checking
- Booking records in Google Sheets
- Stripe Checkout payment link generation
- Automated payment email notifications
- Pending payment status tracking

## Workflow
1. Patient submits the appointment form.
2. Patient information is validated.
3. The workflow checks whether the selected appointment slot is available.
4. Booking details are stored in Google Sheets with Pending Payment status.
5. A Stripe Checkout session is created.
6. Gmail sends the payment link to the patient.

## Technologies
- n8n
- Google Sheets
- Stripe Checkout
- Gmail
- JavaScript
- Webhooks and API Integration

## Setup Notes
Configure your own Google Sheets, Stripe, and Gmail credentials after importing the workflow. Replace the placeholder Stripe secret key and Google Sheets ID with your own values.
