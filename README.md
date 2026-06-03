# MY Personal AI AGENT — Customer Feedback Scorer

> An AI agent that classifies customer feedback in seconds — built to automate the work I had to do often and with less time.

---

## The problem

Our team always wondered what our customers think before and after evey campaign. We used to wait for NPS survey results to come out every quarter and it was broad. 
We also could not understand what our customers felt about our campaigns, so I created this agent to get the sentiment based on data from CRM - call logs, case comments, comments on social media, short surveys after a campaign etc., 

This saved so much guesswork, and if we were to do it manually every month, it would take 8 hours of effort to munge the data and present it. This agent reduces that to a few minute to copy paste the data and get the output live in pur brainstorming sessions.

P.S: I have recreated it to reflect only the CX comments to add to my profile. Did not include the marketing feedback part as it may be relevant to our company terms. 


## What this does

Paste any feedback — from customers, clients, campaign reviews, brand audits, social listening exports — and the AI instantly classifies each item:

- **Sentiment** — Positive / Negative / Neutral
- **Category** — Campaign, Content, Brand, Channel, Audience, Tone
- **Urgency** — High / Medium / Low
- **Strategic recommendation** — specific next action, not generic advice

Also accepts CSV uploads directly — useful for analysing bulk exports from survey tools, CRM systems, or social listening platforms.

## Live demo

`yourname.github.io/brand-pulse`

## Built with

- HTML + CSS + JavaScript — no frameworks, no build step
- [OpenRouter API](https://openrouter.ai) — routes to best available AI model
- Prompt engineering — system prompt tuned to think like a strategist

## What I learned building this

- How to structure an AI system prompt to return consistent and reliable outcome
- Why browsers block direct API calls (CORS) and how a proxy solves it
- How to parse and display API responses dynamically in a UI
- How to quickly build and ship  an MVP and keep things moving 

## Sample inputs to try

Copy and paste these into the tool:

```
I love your premium product. Worth my money.
I had a bad experience with one of the agents who dealt with my delays, No proper response.
They handled my goods very poorly, It was damaged and when reported no one took responsibility.
The premium product is lifesaver. 
I had good experience - I have premium. 
Customer service was very rude, especially went unresponsive when I mentioned I dont have premium . this is very unethical 

```

Or upload a CSV with a `feedback` column — the tool reads it directly.

## How to run locally

1. Download `index.html`
2. Get a free API key at [openrouter.ai](https://openrouter.ai)
3. Paste your key on the console, it wont be saved and used directly from your browser only!
4. Double-click the file — opens in any browser
5. No install, no terminal, no server needed

## Practice datasets (public CSVs you can test with)

- [Amazon product reviews — Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- [Twitter sentiment dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- Any brand/NPS survey export from your own practice

---

## About

[PERSONALISE THIS — 2-3 sentences about you]

Built by Sruthi S — Lead Data Analyst. I come from data background (SQL, Python, sklearn, model evaluation, end-to-end data product building, data visualizations etc) worked across domains like, pharma, learning management systems, learning & development, sales, marketing, pricing and supplychain, I built this to learn how to productionise AI applications and work with LLM APIs end-to-end while solving for a real problem at work. 

[LinkedIn](https://linkedin.com/in/sruthi-s-sivakumar)
