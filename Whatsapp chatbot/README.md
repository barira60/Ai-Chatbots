🍔 CraveHub Automation System

CraveHub is a smart food delivery automation system built using n8n, Google Sheets, and WhatsApp.
It manages customer orders, delivery tracking, and feedback automatically — reducing manual work for food businesses.

🤖 1. WhatsApp Bot

An AI-powered chatbot that interacts with customers through WhatsApp.
It shows the menu, takes orders, calculates totals, saves data to Google Sheets, and collects feedback automatically.

Key Features:

AI chat using Google Gemini (PaLM)

Menu and FAQ from Google Sheets

Auto order saving and confirmation

Feedback detection (⭐ or 1–5)

Personalized chat memory

🚚 2. Order Status Monitor

This workflow sends real-time WhatsApp updates when order status changes in Google Sheets.

Status Messages:

🧑‍🍳 Preparing → “Your order is being prepared.”

🚗 Out for Delivery → “Your order is on its way!”

✅ Delivered → “Your order has been delivered! Please rate your experience.”

Key Features:

Auto WhatsApp notifications

Google Sheets integration

Fully hands-free order tracking

🧠 Tech Stack

Tools: n8n • Google Sheets • WhatsApp API • LangChain • Google Gemini