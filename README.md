# 📰 Personalized News Delivery Agent

An AI-powered, automated agent built with **n8n** that fetches news from the internet, analyzes it, and sends personalized email digests to users based on their interests — without requiring any manual input.

## 🚀 Features

- 🔎 Fetches the latest news articles from News API
- 🧠 Matches articles to user-defined interests from Google Sheets
- ✉️ Sends personalized daily email digests (top 5 relevant articles per user)
- 🔁 Fully autonomous and runs on a scheduled workflow
- 📄 HTML-formatted email content for better readability

## 🧠 Use Case

 Helps busy users stay informed by delivering only the most relevant news, based on their interests, directly to their inbox — saving time and reducing information overload.

## 📁 Tech Stack

- **n8n** – No-code/low-code automation platform
- **NewsAPI** – For fetching the latest news headlines
- **Google Sheets** – To store user emails and their interests
- **Gmail / Email Node** – To send HTML-formatted email digests

## 🛠️ How It Works

1. NewsAPI node fetches current news articles.
2. Google Sheets node pulls a list of users and their interests.
3. A Code node filters top 5 articles for each user based on keyword matching.
4. HTML emails are dynamically generated per user.
5. Emails are sent out via the Email node (e.g. Gmail or SMTP).
6. Entire workflow runs on schedule — no human input required.

## 🔄 Workflow

![Screenshot 2025-06-21 203238](https://github.com/user-attachments/assets/4f137277-b815-4989-96f8-bbe316cc73b7)


## ✅ Future Scope

- Add GPT-based summaries
- Multi-platform delivery (Telegram, Slack, etc.)
- User preference dashboard
- Multi-language support
- Smart personalization using feedback loop


