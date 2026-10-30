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
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Lavender](https://www.lavender.ai/)**
  **Real-time AI email coach** that scores and improves outbound emails before you send, with personalization suggestions and team benchmarking. Integrates directly into Gmail and Outlook . **Pricing**: Free tier available; Individual $29/month; Teams $49/user/month . **Free tier**: Yes, limited coaching. **Best for**: sales reps and founders wanting measurable reply-rate improvement without leaving their email client—**note**: it coaches, it does not send emails for you .

- **[Regie.ai](https://www.regie.ai/)**
  **AI sales content generation platform** with prospect research and personalized outreach sequences. **Pricing**: Quote-only; enterprise contracts. **Free tier**: None. **Best for**: sales teams wanting AI-generated sequences grounded in prospect data at scale.

- **[Warmer.ai](https://warmer.ai/)**
  **AI prospect research and personalization tool** that enriches lead lists and drafts personalized outreach. **Pricing**: Freemium; paid tiers from $79 to $399 according to third-party listings . **Free tier**: Yes, limited usage. **Best for**: sales teams wanting automated prospect research feeding into personalized email drafts.

- **[Copy.ai](https://www.copy.ai/)**
  **AI copywriting platform** with email generation templates and workflow automation. **Pricing**: Free tier; paid plans per user. **Free tier**: Yes, limited credits. **Best for**: marketers wanting a general-purpose AI writer with email-specific templates.

- **[Jasper](https://www.jasper.ai/)**
  **Enterprise AI marketing platform** with email campaign generation and brand voice controls. **Pricing**: Quote-only; tiered by seats and features. **Free tier**: Trial available. **Best for**: marketing teams wanting brand-consistent email copy at scale.

- **[Smartwriter.ai](https://www.smartwriter.ai/)**
  **AI cold email personalization** with prospect research from LinkedIn and web sources. **Pricing**: Quote-only; tiered by credits. **Free tier**: Trial available. **Best for**: outbound teams wanting research-backed personalization without manual prospect digging.

- **[Lyne.ai](https://www.lyne.ai/)**
  **AI email personalization** with first-line generation and prospect research. **Pricing**: Quote-only; credit-based. **Free tier**: Trial available. **Best for**: cold emailers wanting AI-generated opening lines based on prospect activity.

- **[HubSpot AI Email Writer](https://www.hubspot.com/)**
  **Native AI email generation** within HubSpot's CRM and marketing tools. **Pricing**: Included with HubSpot paid tiers; quote-based. **Free tier**: Limited. **Best for**: HubSpot users wanting AI email drafts without leaving their CRM.

- **[MailMaestro](https://www.maestrolabs.com/)** (Flowrite successor)
  **AI email assistant** that replaced Flowrite after Maestro Labs acquired its email-writing business in January 2025. Adds inbox triage, thread summaries, and meeting notes on top of email generation . **Pricing**: Free plan available; Pro from $12/seat/month (annual) or $15 monthly; TeamsMaestro $17/seat/month . **Free tier**: Yes. **Best for**: former Flowrite users or anyone wanting AI email generation with inbox management in Gmail/Outlook.

- **[Hypotenuse AI](https://www.hypotenuse.ai/)**
  **AI content generation** including email copy and marketing content. **Pricing**: Quote-only; tiered by credits. **Free tier**: Trial available. **Best for**: content teams wanting AI-generated email copy alongside broader marketing content.

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
