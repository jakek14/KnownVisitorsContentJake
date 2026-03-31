# KnownVisitors Content Engine

## What This Repo Is
This is the content brain for KnownVisitors' social presence across X/Twitter, LinkedIn, and Meta (Facebook + Instagram), for both the founder (CEO) and company accounts. Every post lives here — from draft to published. The daily agent reads this repo to avoid repeating topics, angles, or phrasing across platforms and accounts.

## Repo Structure
```
x/
  founder/drafts/      — CEO's X/Twitter drafts
  founder/published/   — posted CEO X content
  founder/archive/     — rejected/old CEO X content
  company/drafts/      — KnownVisitors brand X drafts
  company/published/   — posted brand X content
  company/archive/     — rejected/old brand X content
linkedin/
  founder/drafts/      — CEO's LinkedIn drafts
  founder/published/   — posted CEO LinkedIn content
  founder/archive/     — rejected/old CEO LinkedIn content
  company/drafts/      — KnownVisitors company page drafts
  company/published/   — posted company LinkedIn content
  company/archive/     — rejected/old company LinkedIn content
meta/
  company/drafts/      — KnownVisitors brand Meta drafts (Facebook + Instagram)
  company/published/   — posted brand Meta content
  company/archive/     — rejected/old brand Meta content
```

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

---

## FOUNDER vs COMPANY PAGES

### Founder Pages (CEO's personal accounts)
- **Voice**: "I" — personal, founder-led, first person
- **Tone**: Talks like a sharp founder, direct, slightly provocative, real
- **KV mention ratio**: **80/20** — 80% pure value, 20% naturally mention KnownVisitors
- **Content focus**: All 12 pillars — personal takes, founder journey, SaaS advice, bootstrapping, raising money, vibe coding, free game, industry commentary, AND product awareness
- **KV mentions feel like**: "this is why I built KnownVisitors" / "this is exactly the problem we solve" — organic, referencing personal experience

### Company Pages (KnownVisitors brand accounts)
- **Voice**: "We" — brand voice, still human and direct, NOT corporate
- **Tone**: Authoritative but approachable — like a company that knows its space inside and out
- **KV mention ratio**: **60/40** — 60% pure value, 40% mention KnownVisitors or the product
- **Content focus**: Weighted toward product/proof/industry pillars — Problem Awareness, Reframes, Hot Takes, Proof/Results, Industry Commentary, Free Game. Less emphasis on personal founder pillars (Founder Journey, Bootstrapping, Raising Money).
- **KV mentions feel like**: "We built KnownVisitors because..." / "Our users see this every day" / "Here's how visitor identification changes the game" — brand authority, not hard pitch
- **Never say**: "excited to announce" / "we're thrilled" / corporate buzzwords

---

## Shared Rules (All 4 Pages)

### Truthfulness
- **Never fabricate stories or anecdotes.** No "I had coffee with a founder who..." or "One of our customers told us..." unless it actually happened.
- Use hypothetical framing instead: "Imagine a founder with $40k MRR..." or "Picture this..." or frame it as a general observation.
- Truthfulness is non-negotiable across ALL pages and platforms.

### Hooks
- **Hook first** — the opening line is everything on BOTH platforms. It must stop the scroll.
- Lead with a surprising stat, a bold claim, a contrarian take, or a pattern interrupt.
- Weak openers like "I was thinking about..." or "Here's something interesting..." kill reach.

### Hook Formulas That Work
Use these as inspiration, not templates. Rotate and adapt:
- **Stat bomb**: "92% of B2B buyers already have a vendor in mind."
- **Contrarian**: "SEO is rented traffic. Always was."
- **Curiosity gap**: "Most founders get this wrong about churn."
- **Pattern interrupt**: One surprising word or short phrase, then a line break.
- **Bold claim**: "Your website traffic is worthless if you can't identify it."
- **Story hook (hypothetical only)**: "Picture this: $40k MRR, profitable, growing 15% MoM — and every VC says 'come back later.'"

### Content Philosophy
Every post should live in the WORLD that KnownVisitors operates in — marketing, traffic, data, ads, retargeting, website optimization, SaaS growth, lead generation, privacy, analytics.

### Mentioning KnownVisitors
- **Founder pages**: ~80% pure value, ~20% mention KV. Check the last 5 posts — if any of the last 4 mentioned KV, do NOT mention it.
- **Company pages**: ~60% pure value, ~40% mention KV. Check the last 5 posts — if any of the last 2 mentioned KV, do NOT mention it (avoid back-to-back).
- When you DO mention KnownVisitors, the post should still be primarily valuable on its own.
- Track this with `mentions_kv: true|false` in frontmatter.

## Content Pillars (Rotate These)

### Core Product Pillars (All Pages)
1. **Problem Awareness** — make people feel the pain of anonymous traffic
2. **Reframes** — change how people think about traffic/marketing
3. **Hot Takes** — contrarian angles on marketing, ads, retargeting
4. **Proof/Results** — real stats when available (none yet)

### Founder & Business Pillars (Founder Pages Only)
5. **Founder Journey** — build in public, real experiences, wins and struggles
6. **SaaS Advice** — lessons learned about building, scaling, pricing, churn, metrics
7. **Bootstrapping** — the grind of building without (or before) funding, staying lean, making scrappy decisions
8. **Raising Money** — fundraising insights, investor dynamics, when/whether to raise, term sheets, cap tables
9. **Vibe Coding** — building with AI tools, using Claude/GPT to ship faster, the new wave of AI-assisted development

### Value-Add Pillars (All Pages)
10. **Free Game** — genuinely useful advice people can apply immediately (marketing tactics, growth hacks, tool recommendations, frameworks) — no pitch, just value
11. **Industry Commentary** — reacting to news, trends, drama in SaaS/e-commerce/marketing/tech
12. **Founder Takes** — opinions on startup culture, hustle culture, remote work, hiring, the realities of building a company

## Topic Tracking
Before writing a new post, ALWAYS:
1. Read all files in that page's `published/` and `drafts/` folders
2. Also check the OTHER pages' recent posts — avoid posting about the same topic across pages the same day
3. Check what pillar was used last (rotate)
4. Check what topics/angles were used recently (don't repeat within 2 weeks)
5. Find a FRESH angle tied to current events

### Duplicate Detection — READ THIS CAREFULLY
Two posts count as duplicates if they share the same CORE IDEA, even if they use different stats, different framing, or different wording. Examples of duplicates:
- "97% of visitors leave without converting" and "98% of traffic bounces" — SAME IDEA (anonymous traffic waste)
- "You don't know who's on your site" and "Visitors leave without filling out a form" — SAME IDEA (invisible visitors)
- "CAC is rising" and "Ad costs are up 60%" — SAME IDEA (acquisition getting expensive)

Before writing, identify the ONE SENTENCE core idea of your post. Then check if ANY recent post (last 2 weeks, across ALL pages) shares that core idea. If it does, pick a completely different topic — not a different stat on the same topic.

---

# X/TWITTER-SPECIFIC RULES

## X Founder Voice
- Talks like a person at a bar, not a brand on LinkedIn
- Short sentences. One idea per line. Line breaks between thoughts.
- No hashtags, no emojis, no "excited to announce"
- No product pitching — never say "check out our tool" in posts
- End with a strong last line (people screenshot the last line)
- Links go in replies, never in the main post

## X Company Voice
- Same directness as founder, but uses "we" instead of "I"
- Can be slightly more product-focused but still leads with value
- No hashtags, no emojis, no corporate speak
- End with a strong last line
- Links go in replies, never in the main post

## X Character Limits & Post Sizing
This account has X Basic — long-form posts up to 25,000 characters are supported.

- **Short** (target: ≤ 280 characters): Punchy one-liners, hot takes, bold claims. High engagement ceiling.
- **Medium** (target: 280–800 characters): A developed thought with a hook, supporting point, and a strong closing line.
- **Long** (target: 800–2,500 characters): Deep dives, step-by-step breakdowns, founder stories, detailed takes. Use line breaks generously — no walls of text. Think RetentionAdam-style long posts.
- **Thread** (3-7 tweets, each ≤ 280 characters): A chain of connected tweets for multi-point takes. Structure: hook tweet → 3-5 value tweets → closing tweet with a soft CTA. Each tweet in a thread MUST be ≤ 280 characters.
- **Question** (target: ≤ 280 characters): Engagement-focused. Ends with a genuine question that invites replies.

**Mix it up**: Don't post the same format twice in a row.

## X Engagement & Soft CTAs
Replies carry **13.5x more algorithmic weight** than likes on X.

- ~30% of posts should end with a **genuine question** or **soft CTA** that invites replies
- Good: "What's the worst marketing advice you've ever followed?" / "Curious — how are you handling this?"
- Good: "Bookmark this if you're dealing with the same thing."
- Bad: "Like if you agree, RT if you disagree" — engagement bait, X actively penalizes it
- Bad: "Comment YES for a free guide" — suppressed by the algorithm
- The other ~70% should end with a strong closing line — no CTA needed.

## X KV Link Replies
- **When a post mentions KV (`mentions_kv: true`)**: include a first reply with a short CTA + the knownvisitors.com link. The CTA comes first, then the link. Examples:
  - Founder: "See who's on your site right now — knownvisitors.com"
  - Founder: "Try it free, no demo required — knownvisitors.com"
  - Company: "Identify your anonymous visitors today — knownvisitors.com"
  - Company: "See it in action — knownvisitors.com"
- The link goes in the **reply**, never in the main post (X penalizes links by 30-50% reach).
- Add the reply text under a `## Reply` section in the draft file.

## X Draft File Format
Save to `x/founder/drafts/` or `x/company/drafts/` as `YYYY-MM-DD-HHMM-SS.md`

```markdown
---
date: YYYY-MM-DD
platform: x
page: [founder|company]
status: draft
pillar: [problem-awareness|reframe|hot-take|proof|founder-journey|saas-advice|bootstrapping|raising-money|vibe-coding|free-game|industry-commentary|founder-takes]
format: [short|medium|long|thread|question]
mentions_kv: [true|false]
source: "Brief description of the news/trend that inspired this"
source_url: "URL if applicable"
---

## Post

[The actual post text]

For threads, format as:

**Tweet 1**
[Hook tweet — ≤ 280 chars]

**Tweet 2**
[Value tweet — ≤ 280 chars]

...

**Tweet N**
[Closing tweet, optional soft CTA — ≤ 280 chars]

## Reply (only if mentions_kv: true)

[Short CTA + knownvisitors.com link]

## Context

[Why this topic was chosen, what's happening in the news]
```

---

# LINKEDIN-SPECIFIC RULES

## LinkedIn Founder Voice
- More professional than X, but still personal — NOT corporate
- Talks like a sharp founder at a conference
- Longer-form storytelling is expected and rewarded
- Can be more nuanced and detailed than X
- Still no corporate jargon, no "excited to announce," no buzzword soup
- Uses "I" voice

## LinkedIn Company Voice
- Authoritative and knowledgeable — the brand that knows this space
- Uses "we" voice
- Can lean more into product, data, and industry expertise
- Still human and direct — NOT a press release
- No buzzwords, no corporate fluff

## LinkedIn Character Limits & Post Sizing
LinkedIn allows up to 3,000 characters per post (~400-500 words).

- **Short** (target: ≤ 300 characters): Quick insight, bold claim, or hot take. Complete thought with no "see more" click needed.
- **Medium** (target: 800–1,100 characters): Developed thought with hook, supporting points, and a closing line. The engagement sweet spot.
- **Long** (target: 1,300–2,000 characters): Deep storytelling, step-by-step frameworks, detailed breakdowns. Best for authority-building. Use line breaks generously — short paragraphs (1-2 sentences each).
- **Question** (target: ≤ 300 characters): Engagement-focused. Ends with a genuine question that invites comments.

**Hard rules:**
- Every post MUST be ≤ 3,000 characters.
- The hook MUST be complete within the first 140 characters — that's where LinkedIn truncates on mobile before "see more."
- Use line breaks between every 1-2 sentences. Walls of text kill dwell time.

## LinkedIn Algorithm Rules

### What LinkedIn Rewards
- **Dwell time** is the #1 signal — more important than likes. Write content people spend time reading.
- **Substantive comments (10+ words)** carry 15x more weight than a like.
- **Author replying to comments** is a major engagement signal — reply to every comment.
- **First 60-90 minutes** after posting determine ~70% of total reach. Be available to engage.
- **Topical expertise** — LinkedIn tracks what topics you consistently post about. Stay in your lane (marketing, SaaS, lead gen, visitor identification).
- **Format rotation** — accounts using varied formats see 40%+ better follower growth.

### What LinkedIn Penalizes
- **External links** — posts with links get ~60% less reach. NEVER put a link in the main post.
- **"Link in comments" is dead** — LinkedIn detects and penalizes this as of 2026.
- **Engagement bait** — "Comment YES if you agree" is actively suppressed.

## How to Handle Links on LinkedIn
- Do NOT put links in the main post (~60% reach penalty).
- Do NOT put links in the first comment (LinkedIn penalizes this now).
- **For KV-mention posts**: reference knownvisitors.com by name in the post text (e.g., "That's why we built KnownVisitors") but do NOT hyperlink it. People can Google it. The brand mention is enough.
- If a link is absolutely necessary: publish the post without it, let it gain traction, then edit the post to add the link later.

## LinkedIn Engagement & Soft CTAs
Comments with 10+ words carry **15x more algorithmic weight** than likes.

- ~40% of LinkedIn posts should end with a **genuine question** or **soft CTA** that invites substantive comments
- Good: "What's the hardest part of scaling past $1M ARR?" / "How are you thinking about this?"
- Good: "If this resonates, I'd love to hear your experience."
- Bad: "Like if you agree" / "Comment YES for access" — actively suppressed
- The other ~60% should end with a strong, quotable closing line.
- **Always reply to comments on your posts** — especially in the first 60-90 minutes.

## LinkedIn Hashtags
- Use **3-5 relevant hashtags** at the bottom of the post
- Hashtags on LinkedIn are search/categorization tools, NOT viral discovery
- Pyramid strategy: 1 broad tag + 2-3 niche tags + 1 branded tag
- Example: #SaaS #LeadGeneration #WebsiteTraffic #MarketingStrategy #KnownVisitors
- Place hashtags at the very end of the post, after the closing line

## LinkedIn Draft File Format
Save to `linkedin/founder/drafts/` or `linkedin/company/drafts/` as `YYYY-MM-DD-HHMM-SS.md`

```markdown
---
date: YYYY-MM-DD
platform: linkedin
page: [founder|company]
status: draft
pillar: [problem-awareness|reframe|hot-take|proof|founder-journey|saas-advice|bootstrapping|raising-money|vibe-coding|free-game|industry-commentary|founder-takes]
format: [short|medium|long|question]
mentions_kv: [true|false]
source: "Brief description of the news/trend that inspired this"
source_url: "URL if applicable"
---

## Post

[The actual post text, ready to copy-paste to LinkedIn]

## Context

[Why this topic was chosen, what's happening in the news]
```

---

# META-SPECIFIC RULES (Facebook + Instagram — Company Page Only)

Meta posts are cross-posted: same post goes to both Facebook and Instagram. Every Meta post includes an image. The agent generates both the caption and a Nano Banana image prompt.

**Meta posts are less frequent than X and LinkedIn** — not every daily run needs a Meta post. Generate Meta posts only when specifically requested or when the content is highly visual and well-suited to the format.

## Meta Voice
- Uses "we" voice — this is the KnownVisitors brand account
- Authoritative but approachable — the brand that knows this space
- More visual storytelling — the image carries weight, caption complements it
- Can be shorter than LinkedIn — the image does half the work
- Still human, not corporate. No press releases, no buzzwords.
- B2B buyers on Meta are NOT in buying mode — build brand awareness and trust, don't hard-sell

## Meta Caption Sizing
- **Short** (target: ≤ 125 characters): Punchy line that pairs with a strong image. Fully visible on Instagram without truncation.
- **Medium** (target: 125–500 characters): Developed thought with hook and closing line. Hook lands before the fold, value after.
- **Long** (target: 500–1,000 characters): Deeper context, mini-story. Use line breaks generously.

**Hard rules:**
- Every Meta post MUST include an image prompt — no text-only posts.
- The hook MUST land within the first **125 characters** — that's where Instagram truncates on mobile before "...more."
- **No hashtags.** Instagram capped hashtags at 5 and removed hashtag-following in 2024. Hashtags are now near-useless for discovery. Use keyword-rich captions instead — caption SEO has replaced hashtags as the primary discovery mechanism.
- **No links in the post body.** Meta limits non-verified pages to 2 link posts per month. Even within that limit, link posts get crushed algorithmically — only 2% of Facebook's most-viewed posts include links. If a link is needed, put it in the first comment.

## Meta KV Mention Rules
- **60/40 ratio**: 60% pure value, 40% mention KnownVisitors
- Check last 5 meta/company posts — if last 2 mentioned KV, skip it

## Meta Algorithm Rules

### What Meta Rewards
- **Original content** — Meta formally penalizes reposted/unoriginal content. Accounts caught get classified as "non-recommendable."
- **Saves, shares, and DM sends** — weighted far higher than likes. Create "saveable" content: frameworks, checklists, step-by-step guides.
- **Engagement velocity in the first 30-60 minutes** — respond to every comment immediately.
- **Carousel/multi-image posts** — outperform single images (~10% engagement vs 7%). Swiping triggers extended time-on-post.
- **Keyword-rich captions** — Meta's algorithm reads your caption to match content to interested users. Include terms your ICP searches for (e.g., "website visitor identification," "lead generation," "anonymous traffic").
- **Consistent posting cadence** — activity bursts followed by silence get penalized.

### What Meta Penalizes
- **External links in post body** — massive reach reduction + 2-link monthly cap for non-verified pages
- **Engagement bait** — "Tag 3 friends!" is explicitly penalized
- **Over 5 hashtags on Instagram** — algorithmically suppressed
- **Repetitive/low-quality content** — flagged as noise
- **Identical cross-posts** — Meta's 2025 policy change penalizes "unoriginal" content, so identical posts across platforms can trigger reduced visibility

## Meta Engagement & CTAs
- **Specific CTAs outperform generic ones by 3x.** Always end with a concrete ask.
- Good: "Save this for your next QBR" / "Drop a question below — we'll answer every one"
- Bad: "Let me know what you think" / "Like if you agree"
- ~50% of posts should end with a specific CTA
- **Reply to every comment within 1 hour** — doubles comment count and creates algorithmic momentum

## Image Prompt Guidelines — KnownVisitors Brand Style

The image prompt goes into the `## Visual Prompt` section of the draft. It will be fed into Nano Banana to generate the image.

### Image Dimensions & Safe Zones
- **Aspect ratio**: 4:5 (portrait) — this is the optimal format for both Facebook and Instagram feed. Takes up maximum screen space on mobile.
- **Resolution**: 1080 x 1350 pixels
- **Instagram grid safe zone**: Instagram displays grid previews at 3:4. Keep the core visual within the center of the image so nothing important gets cropped in the grid view.
- **Text overlay safe zone**: Keep all text overlay within the center ~70% of the image. Leave the top 14%, bottom 35%, and sides 6% clear of critical text/visuals — Instagram overlays UI elements (profile icon, CTA buttons) in these areas.
- **Always include in the prompt**: "4:5 aspect ratio, 1080x1350 pixels, portrait orientation"

### KV Brand Rules for Image Prompts
Every image prompt MUST include these brand elements:
- **Color palette**: Black background, green (#27A848) accents, white highlights
- **Aesthetic**: Dark, modern, premium tech — think SaaS dashboard, developer tool landing page
- **Mood**: Confident, clean, minimal, high-contrast
- **Style direction**: Always include "dark tech aesthetic, black background, green accent lighting, minimal, high contrast, modern SaaS visual, 4:5 portrait aspect ratio"

### Clarity Rule — THE MOST IMPORTANT RULE
**A person scrolling their feed should instantly understand what the image is about WITHOUT reading the caption.** The image must be dead simple. One concept. One focal point. No multi-step visual stories.

### Keep It Simple — Lessons Learned
AI image generators (Nano Banana) produce unpredictable results with complex prompts. The more concepts you cram into one image, the worse it gets. What works:

**BEST approach — stat card style:**
- A bold number or stat as the visual centerpiece (e.g., a large "58%" glowing in green)
- Clean dark background with subtle gradient
- Text overlay does the talking — headline + subtitle
- This is the safest, most effective format. Opensend, RB2B, and top B2B brands use this style.

**ACCEPTABLE approach — single simple metaphor:**
- ONE recognizable object or scene — a laptop, a magnifying glass, a lock, a dashboard
- No multi-step visual stories (e.g., "Google results → arrow → website → contact card" is too complex)
- If you can't describe the image in one sentence, it's too complicated

### What to Avoid (never prompt for these)
- **Complex visual narratives** — multiple elements connected by arrows, flows, or sequences. AI generates these poorly and viewers can't parse them at a glance.
- **Abstract/vague visuals** — flowing data streams, network nodes, connection maps, geometric shapes, floating wireframes. These look like generic stock art and communicate nothing.
- **Text in the image** — Nano Banana garbles text. Text goes in the overlay, not the AI image.
- **Realistic human faces or photos** — use silhouettes or stylized figures instead
- **Different colored silhouettes** — all silhouettes must be the SAME color/shade (dark gray or green). Never render silhouettes in different skin tones or contrasting colors that could be interpreted as racial. Use glow effects, contact cards, or outlines to differentiate — NOT color differences on the figures themselves.
- **Off-center focal points** — the key visual must be centered in the image
- **Busy, cluttered compositions** — keep it clean and minimal. One object, not five.
- Bright/colorful palettes — stay dark and moody, on-brand
- Logos — don't ask AI to render the KV logo
- Important visual elements near the edges — they'll get cropped in grid view or covered by UI

### Text Overlay
The `## Text Overlay` section contains the headline/subtitle to be manually placed on top of the generated image. Keep it short and impactful:
- **Headline**: 3-8 words, bold claim or stat
- **Subtitle** (optional): One line of supporting context
- Text overlay should be in white or green on the dark background
- **Position the text in the center ~70% of the image** — avoid top 14%, bottom 35%, and sides 6% where Instagram overlays UI elements

## Meta Draft File Format
Save to `meta/company/drafts/` as `YYYY-MM-DD-HHMM-SS.md`

```markdown
---
date: YYYY-MM-DD
platform: meta
page: company
status: draft
pillar: [problem-awareness|reframe|hot-take|proof|saas-advice|free-game|industry-commentary]
format: [short|medium|long]
mentions_kv: [true|false]
source: "Brief description of the news/trend that inspired this"
source_url: "URL if applicable"
---

## Post

[Caption text for Facebook/Instagram. No hashtags. Use keyword-rich language for discovery.]

## Visual Prompt

[Nano Banana image prompt — describes the background visual. Include KV brand style direction. NO text in the image.]

## Text Overlay

Headline: [3-8 word headline to place on the image]
Subtitle: [Optional one-line subtitle]

## Context

[Why this topic was chosen, what's happening in the news]
```

---

# GENERAL WORKFLOW

### Creating Drafts
- Search the web for current news/trends in marketing, e-commerce, SaaS, privacy, ad tech, startup funding, AI/vibe coding, bootstrapping, and general business
- Check ALL page folders (`x/founder/`, `x/company/`, `linkedin/founder/`, `linkedin/company/`, `meta/company/`) to avoid repeating topics
- Write a post tied to something REAL happening right now
- Generate posts for the requested page(s) — different angles on the same topic, or different topics entirely
- Save to the appropriate platform/page folder

### When Approved
- Move from `drafts/` to `published/` within the platform/page folder
- Update status to `published`
- Add `published_date` to frontmatter

### When Rejected/Edited
- User can edit the file directly in GitHub
- Or tell the agent to revise — agent updates the draft in place
