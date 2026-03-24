# KnownVisitors Content Engine

## What This Repo Is
This is the content brain for KnownVisitors' X/Twitter presence. Every post lives here — from draft to published. The daily agent reads this repo to avoid repeating topics, angles, or phrasing.

## About KnownVisitors
- **Product**: Website visitor identification tool — identifies anonymous website visitors and provides name, email, phone, company, location. No forms, no popups.
- **Key differentiators**:
  1. Data ownership — users get their data, own it, do whatever they want with it
  2. Compliance-first — every record scrubbed (email verification, DNC, TCPA, CAN-SPAM, GDPR, CCPA) before delivery
  3. No lock-in — no forced workflows, use it your way
  4. Clean data — verified contacts, not a firehose of garbage
- **ICP**: Anyone with a website looking to retarget — e-commerce, SaaS, agencies, local businesses
- **Website**: knownvisitors.com
- **Competitors**: RB2B, Clearbit, Warmly, Leadpipe, Customers.ai, 6sense, Leadfeeder

## About the Voice (Jake)
- Jake has been involved with KnownVisitors since the beginning
- Founder-led voice — direct, slightly provocative, real, no corporate speak
- Talks like a person at a bar, not a brand on LinkedIn
- Confident but not arrogant — sharing insights, not selling

## Voice Rules
- Use "I" not "we" — personal founder voice
- Short sentences. One idea per line. Line breaks between thoughts.
- No hashtags, no emojis, no "excited to announce"
- No product pitching — never say "KnownVisitors" or "check out our tool" in posts
- End with a strong last line (people screenshot the last line)
- Be slightly provocative — challenge norms, call out BS
- Be relatable — reference real situations business owners face
- Links go in replies, never in the main post

## Content Pillars (Rotate These)

### Core Product Pillars
1. **Problem Awareness** — make people feel the pain of anonymous traffic
2. **Reframes** — change how people think about traffic/marketing
3. **Hot Takes** — contrarian angles on marketing, ads, retargeting
4. **Proof/Results** — real stats when available (none yet)

### Founder & Business Pillars
5. **Founder Journey** — build in public, real experiences, wins and struggles
6. **SaaS Advice** — lessons learned about building, scaling, pricing, churn, metrics
7. **Bootstrapping** — the grind of building without (or before) funding, staying lean, making scrappy decisions
8. **Raising Money** — fundraising insights, investor dynamics, when/whether to raise, term sheets, cap tables
9. **Vibe Coding** — building with AI tools, using Claude/GPT to ship faster, the new wave of AI-assisted development

### Value-Add Pillars
10. **Free Game** — genuinely useful advice people can apply immediately (marketing tactics, growth hacks, tool recommendations, frameworks) — no pitch, just value
11. **Industry Commentary** — reacting to news, trends, drama in SaaS/e-commerce/marketing/tech
12. **Founder Takes** — opinions on startup culture, hustle culture, remote work, hiring, the realities of building a company

## How Posts Work

### Creating a Draft
- Search the web for current news/trends in marketing, e-commerce, SaaS, privacy, ad tech, startup funding, AI/vibe coding, bootstrapping, and general business
- Check `published/` and `drafts/` to avoid repeating topics or angles
- Write a post tied to something REAL happening right now
- Save to `drafts/` as `YYYY-MM-DD.md`

### Draft File Format
```markdown
---
date: YYYY-MM-DD
status: draft
pillar: [problem-awareness|reframe|hot-take|proof|founder-journey|saas-advice|bootstrapping|raising-money|vibe-coding|free-game|industry-commentary|founder-takes]
source: "Brief description of the news/trend that inspired this"
source_url: "URL if applicable"
---

## Post

[The actual post text, ready to copy-paste to X]

## Context

[Why this topic was chosen, what's happening in the news]
```

### When Approved
- Move from `drafts/` to `published/`
- Update status to `published`
- Add `published_date` to frontmatter

### When Rejected/Edited
- User can edit the file directly in GitHub
- Or tell the agent to revise — agent updates the draft in place

## Topic Tracking
Before writing a new post, ALWAYS:
1. Read all files in `published/` and `drafts/`
2. Check what pillar was used last (rotate)
3. Check what topics/angles were used recently (don't repeat within 2 weeks)
4. Find a FRESH angle tied to current events
