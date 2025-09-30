# Personal Site AI Agent

A Gradio chat app that answers questions in the voice of a specific person using OpenAI, with tool calls to:
- Record user interest via email
- Log unknown questions for follow-up
Notifications are sent using Pushover. The agent uses a PDF resume (`me/linkedin.pdf`) and a short summary (`me/summary.txt`) as context.

## Features
- Chat UI powered by Gradio
- OpenAI responses with function/tool calls
- Pushover notifications for leads and unknown questions
- Loads persona context from local files

