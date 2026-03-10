# PasteSafe

PasteSafe is a Chrome extension that prevents leaking sensitive data when pasting text into AI chats.

It detects patterns like:

- API keys
- emails
- phone numbers
- IBAN
- UUID
- URLs

If sensitive data is detected, it automatically masks the values before the text is inserted into the chat.

Example:

API_KEY → [API_KEY#1]

## Works with

- ChatGPT
- Claude
- Gemini

## Privacy

Everything runs **locally in the browser**.

No servers.  
No data collection.

## Install

Chrome Web Store:

https://chromewebstore.google.com/detail/pastesafe-%E2%80%94-ai-paste-sani/gpoiombmmaegnfijmcelgbkfbkelgdih?authuser=0&hl=en

## Why this exists

When using AI chats it’s easy to accidentally paste logs or configs containing sensitive data.

PasteSafe adds a simple safety layer before the text is sent.
