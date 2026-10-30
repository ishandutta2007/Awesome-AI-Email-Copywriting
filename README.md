# Awesome-AI-Email-Copywriting

# Awesome-AI-Email-Copywriting

**Top AI Email Copywriting (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cold Outreach Generation, Email Coaching, Personalization at Scale & AI Reply Drafting*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Email Copywriting**. These tools enable sales teams, marketers, and founders to generate personalized cold emails, score and improve drafts, and automate follow-up sequences—from fully managed platforms with real-time coaching and prospect research to self-hosted generators and outbound agents that give teams complete control over their prompts, data, and sending infrastructure.



**Examples** include Lavender, Regie.ai, Warmer.ai, Smartwriter.ai, Lyne.ai, Copy.ai, Jasper, and HubSpot AI Email Writer (the category leaders in commercial space). **Note**: Flowrite and Hypotenuse AI were referenced in the original request, but current search results show Flowrite was acquired and shut down as a standalone product in January 2025, with its technology folded into MailMaestro .



**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, AI email generation, and open outbound infrastructure. **Critical note**: True open-source AI email copywriting—production-ready with prospect research, real-time coaching, and deliverability safeguards—is sparse. The projects below are **CLI generators**, **outbound pipeline agents**, or **email assistants** that require your own LLM API keys and sending infrastructure. None replicate Lavender's real-time coaching inside Gmail or Regie.ai's enterprise sales orchestration.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global AI email assistant and AI-powered sales outreach market is estimated at approximately **$2.5B to $4B** (expanding toward $15B+ by the early 2030s at an estimated 15–22% CAGR). The sector is **highly to moderately fragmented**—characterized by thousands of specialized AI writing and icebreaker micro-SaaS tools competing at the edge, alongside intense pressure from large horizontal platforms (such as HubSpot, Google Workspace, and Microsoft 365 Copilot) that natively embed generative email workflows.

## SaaS/Hosted Platforms

| Platform | Company Scale (Revenue / Valuation) | Pricing | Free Tier / Trial Limits | Key Focus & Use Case |
| :--- | :--- | :--- | :--- | :--- |
| **[HubSpot AI Email Writer](https://www.hubspot.com/)** | ~$13.5B Market Cap (~$3.13B ARR) | Free CRM tier; Starter from **$15/seat/mo** (annual) or $20/mo | **Free forever plan**: 2,000 email sends/month with HubSpot branding and basic AI content assistance | Native CRM-integrated generative email for marketing and sales teams |
| **[Jasper](https://www.jasper.ai/)** | ~$1.5B Valuation (~$131M raised, ~$100M+ ARR) | Pro tier from **$59/seat/mo** (annual) or $69/mo; Business custom | **7-day free trial** of Pro plan (credit card required upfront; full Pro feature access) | Enterprise marketing copy, brand voice governance, and multi-channel campaign generation |
| **[Copy.ai](https://www.copy.ai/)** | ~$100M+ Valuation (~$14M raised, ~$30M–$35M ARR) | Chat tier from **$24/mo** (annual) or $29/mo (up to 5 seats); Agents from $249/mo | **Free trial/grant**: 200 one-time test bonus credits upon sign-up (no perpetual free generation tier) | AI-native GTM workflows, sales copy, and multi-model chat |
| **[Regie.ai](https://www.regie.ai/)** | ~$65.6M Raised (~$15.5M ARR) | Pro tier from **$49/seat/mo**; Team from $150/mo; Enterprise AI SEP from $180/seat/mo | **Free plan**: 250 one-time credits with workspace access for Gmail/Outlook drafting | Prospect research, enterprise sales cadence orchestration, and cold sequence generation |
| **[Lavender](https://www.lavender.ai/)** | ~$14.2M Raised (~$11.9M ARR) | Starter from **$29/user/mo**; Pro $49/mo; Teams $69/mo | **Free forever plan**: Limited to 5 email coachings/month; 7-day free trial on paid plans | Real-time inbox email coaching, email scoring, and reply-rate optimization inside Gmail/Outlook |
| **[Warmer.ai](https://warmer.ai/)** | ~$10.4M Seed Valuation | Growth plan from **$79/mo** (750 credits/mo); Pro $149/mo; Scale $399/mo | **Free trial**: Small test credit allowance to generate sample lines (no credit card required upfront) | Automated lead list enrichment and personalized cold email intro/icebreaker generation |
| **[Hypotenuse AI](https://www.hypotenuse.ai/)** | ~$150K Raised (YC) (~$2.8M–$3M ARR) | Basic/Starter tier from **$19/mo** (annual) or $29/mo; Growth $59/mo | **7-day free trial**: Access to test templates and content generation (no credit card required) | AI content generation for e-commerce, product descriptions, and marketing emails |
| **[MailMaestro](https://www.maestrolabs.com/)** | ~$1.3M Raised (Seed) | Pro tier from **$12/seat/mo** (annual) or $15/mo; TeamsMaestro $17/seat/mo | **Free forever plan**: Capped at 3 AI requests/week with MailMaestro watermark | AI email drafting, thread summaries, and inbox triage for Outlook and Gmail (Flowrite successor) |
| **[Smartwriter.ai](https://www.smartwriter.ai/)** | Bootstrapped (~$300K ARR) | Basic plan from **$49/mo** (annual) or $59/mo (400 lead credits/mo); Popular $149/mo | **7-day free trial**: Full access to cold email and lead personalization tools (no credit card required) | Automated personalized intro lines using LinkedIn and web scraping data |
| **[Lyne.ai](https://lyne.ai/)** | Bootstrapped (PAYG model) | Pay-as-you-go from **$0.25/credit** ($0/mo base); Cold Email Custom $120/mo (2,000 credits) | **Free sign-up / PAYG tier**: $0/mo base access where users pay only per verified generated line (~$0.25/line) | High-volume first-line icebreaker generation from prospect profile scraping |


## Open-Source GitHub Projects



- **[CybrOutreach](https://github.com/M4ST3R-C0NTR0L/CybrOutreach)**

  **AI-powered cold email generator with personalized outreach** (license per repo) — **the most focused open-source tool for structured cold email generation**. **Features**: Generates personalized emails using AI models (OpenRouter, OpenAI, Anthropic); multiple templates (Intro, Follow-up, Break-up, Meeting Request); four tones (Professional, Casual, Aggressive, Friendly); **built on AIDA, PAS, and BAB copywriting frameworks**; batch processing from CSV for hundreds of leads; clipboard and file export . **Tech stack**: Python (PyPI package). **Deploy**: `pip install CybrOutreach`; CLI usage. **Trade-off**: **CLI-only, no prospect research**—you supply the name, company, and context; it does not scrape LinkedIn or enrich leads. No sending infrastructure; you copy or export emails manually. **Best for**: sales teams and founders wanting a structured, framework-driven cold email generator they can script and batch-process with their own LLM keys.



- **[free_outbound_agent](https://github.com/Dumebii/free_outbound_agent)**

  **Open-source AI-powered outbound email agent** (license per repo) — **the most complete open-source outbound pipeline** found in this research. **Features**: **Finds prospects on GitHub, Dev.to, and Product Hunt**; writes personalized emails with Claude or GPT-4; sends via any SMTP provider (Gmail, Zoho, or custom); **multi-step follow-up sequences** with configurable delays; daily sending limits and rate limiting; ICP segmentation with keyword matching; banned-words list to avoid spam triggers; LinkedIn pipeline for message generation (manual send) . **Tech stack**: Python; config-driven YAML; SMTP/Gmail/Zoho backends. **Deploy**: Self-hosted (Python pipeline scripts). **Trade-off**: **Requires significant configuration**—you define ICP segments, source queries, LLM provider, and email backend. Prospect sourcing is limited to GitHub, Dev.to, and Product Hunt—**not general B2B databases**. Email deliverability is your responsibility. **Best for**: developer-focused founders and growth teams wanting an end-to-end outbound pipeline that sources leads, writes personalized emails, and manages follow-ups—without SaaS per-seat fees.



- **[MAILFLOW](https://github.com/NeoNexAI/MAILFLOW-AI_MAILING)**

  **Open source AI email assistant** (AGPL-3.0) — **the most privacy-conscious open-source email drafting tool** for inbound and reply workflows. **Features**: Automatically classifies incoming emails into IMAP folders; **generates draft replies in your writing style**; supports **any LLM** (local Ollama, OpenAI, Anthropic, Gemini, vLLM, LM Studio, or any OpenAI-compatible endpoint); multi-tenant or single-tenant self-hosting; Gmail and Microsoft 365 OAuth2 support; drafts saved as IMAP Drafts (never auto-sent) . **Tech stack**: Next.js, Python (FastAPI), PostgreSQL, Redis, LiteLLM, Docker. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Reply drafting, not cold outreach**—it handles inbound email classification and reply generation, not prospect sourcing or cold sequences. Writing-style capture is on the roadmap, not yet implemented . **Best for**: teams wanting a self-hosted AI assistant that drafts replies to incoming emails using local or cloud LLMs, with full data sovereignty.



- **[WriteWise](https://github.com/tymepas/WriteWise_Project)**

  **AI-powered writing assistant** (license per repo) — **a lightweight reference for email polishing and evaluation**. **Features**: Email mode polishes rough text into professional emails with subject lines; job application email generation from postings; **AI evaluation with 1–10 scores** for personalization and quality; secret redaction before sending to OpenAI; multiple paraphrasing styles . **Tech stack**: React frontend, Python backend, OpenAI API. **Deploy**: Self-hosted (frontend + backend). **Trade-off**: **Not a cold outreach tool**—it polishes and evaluates existing text, not generate personalized sequences from prospect data. No CRM integration, no sending. **Best for**: developers wanting a reference implementation for AI email polishing with quality scoring and secret redaction.



- **[Jema.ai (jasper-alternative-gpt)](https://github.com/yuvalsuede/jasper-alternative-gpt)**

  **Open source Jasper alternative** (MIT) — **the most direct open-source analog to Jasper's template-based generation**. **Features**: Uses ChatGPT API to generate text from templates; template-based architecture where each task is a prompt template; extensible by adding new templates to the `TEMPLATES` list; deployable to Vercel Edge Functions . **Tech stack**: Next.js, TailwindCSS, OpenAI API. **Deploy**: Vercel or local (`npm install`, set `OPENAI_API_KEY`). **Trade-off**: **General-purpose, not email-specific**—it is a template engine for any text generation task. No email templates, no prospect research, no sending. Last updated over a year ago according to repository metadata . **Best for**: developers wanting a minimal, MIT-licensed starting point for a template-driven AI writing tool they can extend with email-specific templates.



### Additional Strong Open-Source Options



- **AISalesEmailGen (Basho Flow)** — Full-stack AI sales email generator (license per repo) with React frontend, Express backend, OpenAI GPT-4o, SendGrid delivery, HubSpot CRM sync, and multi-step sequences . **Note**: Requires OpenAI, SendGrid, and HubSpot accounts; more setup than CLI tools but more complete. **Best for**: teams wanting a self-hosted sales email platform with CRM integration.

- **Career Ops** — Open-source AI job search agent (~77k GitHub stars) that drafts tailored outreach for job applications . **Note**: **Job-search-specific**, not general cold email—it scores jobs against your CV and drafts application emails. **Best for**: individuals wanting AI-assisted job application outreach.



**Frameworks for building custom systems**: Combine **free_outbound_agent** for prospect sourcing and multi-step sequences with **CybrOutreach** for framework-driven email generation, **MAILFLOW** for reply drafting and inbox classification, and **Jema.ai** as a template-engine foundation—creating a complete open-source outbound stack. **None of these provide Lavender's real-time coaching inside Gmail or Regie.ai's enterprise sales orchestration**; those require commercial platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI email copywriting tools handling prospect data and outreach must comply with data protection regulations (GDPR, CCPA, CAN-SPAM, etc.) and implement appropriate consent and unsubscribe mechanisms. AI-generated emails should be reviewed for accuracy and compliance before sending.

- **The "real-time coaching" vs. "cold email generation" vs. "reply drafting" distinction is critical.** **Lavender** is a **real-time email coach**—it scores and improves drafts inside Gmail/Outlook, but does not send emails . **CybrOutreach** and **free_outbound_agent** are **cold outreach generators**—they create personalized emails from prospect data and (in the latter case) send them. **MAILFLOW** is a **reply drafting assistant**—it classifies incoming emails and drafts responses, not cold outreach . **Jema.ai** is a **general-purpose template engine**—not email-specific . **Choose based on whether you need coaching, generation, or reply management.**

- **Flowrite is discontinued.** Maestro Labs acquired Flowrite's email-writing business in January 2025 and folded it into MailMaestro. Flowrite.com redirects to Maestro Labs; new signups are closed . **Do not plan to adopt Flowrite**—use MailMaestro if you need its successor.

- **free_outbound_agent is the most complete open-source outbound pipeline** in this list, with prospect sourcing from GitHub/Dev.to/Product Hunt, multi-step sequences, and SMTP sending . **The trade-off**: it requires substantial configuration and is best suited for developer-focused outreach, not general B2B sales. Deliverability is entirely your responsibility.

- **CybrOutreach is the most structured cold email generator** for teams wanting proven copywriting frameworks (AIDA, PAS, BAB) with batch processing . **The trade-off**: no prospect research—you supply the context. It generates emails, it does not find leads.

- **Open-source AI email tools shift deliverability and compliance responsibility to you.** When you self-host and send via SMTP, you own domain warm-up, SPF/DKIM/DMARC configuration, bounce handling, and CAN-SPAM/GDPR compliance. **Commercial platforms like Lavender and Regie.ai absorb much of this burden.** Evaluate your team's capacity before self-hosting outbound infrastructure.

- **Pricing opacity varies.** Lavender publishes pricing (Free/Individual $29/Teams $49) . Warmer.ai has freemium tiers . MailMaestro publishes Free/Pro/Teams pricing . Regie.ai, Copy.ai (enterprise), Jasper, Smartwriter, Lyne, HubSpot, and Hypotenuse require sales contact or credit estimation. **Validate with direct vendor conversations against your send volume and feature needs.**

- Self-hosted open-source solutions require proper server setup, LLM API key management, email authentication configuration, and ongoing maintenance. **Prospect data and email content are sensitive**—ensure your deployment meets your organization's privacy and security standards before sending live outreach.



---



**Made for developers, sales teams, and organizations building transparent AI email copywriting solutions.**

Let's make AI Email Copywriting more open, data-driven, and deliverability-friendly.
