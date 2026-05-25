# Adonis Omsorg — Digital Presence & AI Integration

**Engagement:** February 2024 – June 2025 (part-time)  
**Sector:** Elderly care, Stockholm  
**Stack:** WordPress, Google Business Profile, Google Ads, OpenAI Assistants API, Make.com, DALL-E, LinkedIn

---

## Context

Adonis Omsorg provides elderly care in Stockholm in a market where publicly funded care recipients actively choose their own provider. The decision is typically made by the pensioner or their adult children, with Google Maps, organic search, and professional appearance serving as primary trust signals. The company needed a digital presence that could convert passive discovery into inbound calls, the key conversion event, as internal experience showed that a direct conversation was a strong predictor of client acquisition.

All work was delivered on minimal budget.

---

## Scope of Work

### Brand Guidelines & Identity
- Developed the company's brand guidelines from scratch: visual identity, tone of voice, value proposition, and service positioning
- Guidelines clarified the company's local market identity and provided a consistent reference for all subsequent digital output including website copy, Google profile, LinkedIn, and ad creative

### Website Management & SEO
- Inherited and restructured an existing WordPress site (Twenty-series theme) according to SEO best practices
- Integrated Google Analytics and Google Tag Manager for traffic and conversion tracking

### Security Hardening
- Configured Wordfence (free tier) with the following controls:
  - MFA on admin accounts
  - Login attempt limits and lockout thresholds
  - CAPTCHA on login and contact forms
  - xmlrpc.php disabled to block a common remote exploitation vector
  - File editing disabled from within the WordPress dashboard
  - WordPress version number hidden
  - Strong password policies enforced
  - Email alerts configured for failed logins and file changes
  - Scheduled malware and file integrity scans
  - Built-in Wordfence blocklist active for known malicious IP ranges

### Google Business Profile
- Built out and actively managed the company's Google Maps presence
- Sourced, took, and curated original photography of staff and office premises
- Profile reached the highest review rating and largest review volume among comparable local providers, a material factor given the target demographic's reliance on Maps for local service discovery

### Google Ads
- Managed paid search campaigns end-to-end: keyword research, bid strategy, ad copy, and performance monitoring
- Combined organic SEO and paid traffic contributed to measurable inbound call volume and client acquisition

### AI Chatbot (OpenAI Assistants API)
- Integrated an OpenAI Assistants API powered chatbot via WordPress plugin
- Fed the assistant company information and a defined persona
- Implemented a chat-initiation disclosure in line with internal data handling policy
- The chatbot was explicitly configured to collect and forward no user data, a deliberate decision to protect user integrity and avoid handling sensitive personal information
- Contact form on the site included an explicit GDPR consent requirement prior to submission

### Automated Content Production (Make.com + DALL-E)
- Built a Make.com automation flow triggered by new row entries in a Google Sheets content calendar
- Flow generated post copy and images via DALL-E; prompts and outputs routed through the sheet for review
- Output was used for LinkedIn content, reducing production time while maintaining editorial control

### LinkedIn Page Management
- Restructured and actively managed the company's LinkedIn presence
- Candidate pipeline for open positions grew from near-zero to exceeding hiring capacity
- LinkedIn activity also served a stakeholder function, demonstrating operational professionalism to municipal officials who allocate clients who do not make an active provider choice

---

## Key Outcomes

| Area | Outcome |
|---|---|
| Brand & Identity | Developed brand guidelines adopted as foundation for all digital and marketing output |
| Google Maps | Highest-rated and most-reviewed provider in local comparison set |
| Inbound leads | Measurable increase in calls; direct contribution to client acquisition |
| Recruitment | Candidate pipeline exceeded hiring capacity |
| Stakeholder signaling | Active digital presence supported municipal relationship and passive client allocation |

---

## Lessons Learned

- In high-trust, relationship-dependent services, digital presence functions primarily as a warm-up channel and the conversion metric is a phone call, not a form submission
- Automation via Make.com and DALL-E enabled consistent content output without dedicated resource allocation, viable for small operations with no social media staff
- Wordfence free tier is sufficient for low-risk WordPress deployments when properly configured; the default install state is not adequate
- xmlrpc.php should be disabled as a baseline step on any WordPress deployment; it is a persistent and commonly exploited attack vector

---

## Security Notes

- Wordfence configured with authentication controls, firewall rules, file scanning, login limits, CAPTCHA, and scheduled scanning
- xmlrpc.php disabled; file editing via dashboard disabled; version number hidden
- Strong password policies enforced; MFA introduced on admin accounts
- Built-in Wordfence IP blocklist active
- Chatbot explicitly configured with no data collection or forwarding, protecting user integrity from the outset
- GDPR-compliant contact form with explicit consent gate
