# AI News Summarizer - Automated Workflow
![Workflow Screenshot](AI%20Summarizer.png)

An automated workflow that fetches 50 news articles daily and delivers a summarized report via email.

### Workflow Flow:
Schedule Trigger -> RSS News (50 items) -> Data Aggregator -> AI Summarizer (Google Gemini) -> Gmail

### Tools Used:
- n8n for automation
- Google Gemini for prompt engineering & summarization
- RSS Feed & Gmail API
