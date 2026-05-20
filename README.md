# SEO Blog Skill — README

A guided, step-by-step blog creation skill for Claude.
Uses a Formula + Prompt system with automatic engagement hook selection from the Hook Playbook.

---

## What This Skill Does

This skill activates whenever you want to create an SEO-optimized blog post. It walks you through every decision — formula, prompt style, keywords, audience, tone — and then generates a fully structured blog with the right hook automatically applied.

---

## How to Trigger

Type any of the following:

- `/seo-blog`
- `/seo-blog [your topic]`
- "Create a blog"
- "Write a blog post"
- "Generate blog content"
- "Write SEO blog"

---

## Step-by-Step Flow

### Step 1 — Blog Title
You'll be asked for the title or topic of your post.

### Step 2 — Choose a Formula

| Formula | Name | Best For |
|---|---|---|
| **1** | Pillar + Cluster Strategy | Building a full content strategy, long-term Google ranking |
| **2** | Trust & Authority Booster | Making content look professional and trustworthy |
| **3** | Fast Ranking with Easy Keywords | Quick Google rankings for new blogs (21–35 days) |

**Formula 1 — Pillar + Cluster Strategy**
Write one big Pillar Post (3,000–4,000 words) + 15–20 small Cluster Posts, each linked back to the main article. Update every 2–3 months.

**Formula 2 — Trust & Authority Booster**
Add TL;DR summary, Author Bio, 5–8 FAQs, 3–5 trusted external links, and a "Last Updated" date.

**Formula 3 — Fast Ranking with Easy Keywords**
Target long-tail keywords, use "vs" and "Alternative" queries, build 3–5 backlinks within a month.

---

### Step 3 — Choose a Prompt Style

| Prompt | Style | Length | Best For |
|---|---|---|---|
| **1** | Basic SEO Blog | ~650 words | Simple, readable blog posts |
| **2** | Full SEO Package | ~650 words | Complete blog + social media kit |
| **3** | Deep Authority Blog | 2,000+ words | Long-form Google Page 1 ranking |
| **4** | Pillar + Cluster Content | 1,500–2,000 words | Topical authority and domain ranking |
| **5** | Conversion Blog | Flexible | Blogs that rank AND generate leads/sales |

---

### Step 4 — Blog Details Collected (One Question at a Time)

1. **Primary Keyword** — The main keyword you want to rank for
2. **Secondary Keywords** — Supporting keywords (or skip)
3. **Target Audience** — Who you're writing for
4. **Location** — City/region target, or global
5. **Organization / Brand Name** — Your business or brand
6. **Word Count** *(Prompts 1 & 2 only)* — Default is 650 words
7. **Tone** — Professional, Friendly, or Inspiring
8. **Call-to-Action** — What you want readers to do at the end

---

### Step 5 — Hook Auto-Selected (No Input Needed)

The best hook type is automatically chosen based on your prompt. You don't need to pick — it's applied behind the scenes.

| Prompt | Auto Hook Applied | Why |
|---|---|---|
| Prompt 1 | Value / List Hook | Promises structured value immediately |
| Prompt 2 | Credibility Hook | Establishes authority and trust up front |
| Prompt 3 | Curiosity Hook | Opens a knowledge gap, pulls reader in |
| Prompt 4 | Counter-Narrative Hook | Challenges a belief, sparks engagement |
| Prompt 5 | Fear Hook or Question Hook | Activates pain point, drives urgency |

---

### Step 6 — Blog Generated

The blog is written using your chosen Formula + Prompt + Hook combination, following all content quality rules.

---

### Step 7 — Summary Delivered

After generation, you'll receive:
- Formula used
- Prompt used
- Hook type applied (with reason)
- Primary keyword
- Word count

---

## Quick Reference — Formula × Prompt × Hook

| Goal | Formula | Prompt | Auto Hook |
|---|---|---|---|
| Quick 650-word SEO blog | Formula 2 | Prompt 1 | Value / List Hook |
| Full blog with social media kit | Formula 2 | Prompt 2 | Credibility Hook |
| Long-form Google ranking article | Formula 1 | Prompt 3 | Curiosity Hook |
| Build topical authority | Formula 1 | Prompt 4 | Counter-Narrative Hook |
| Blog that generates leads | Formula 3 | Prompt 5 | Fear / Question Hook |

---

## Content Quality Rules

- Plain, simple English — no jargon
- Short paragraphs (2–4 lines max)
- Natural keyword placement — never stuffed
- AI detection target: under 10% (humanized writing)
- At least one real-world example or story per blog
- Every blog ends with a clear call-to-action
- Hook is always 1–2 lines — specific, not vague
- **Words never used:** leverage, seamless, transform, unlock, innovative, synergy, disrupt

---

## Skill File Location

```
/mnt/skills/user/seo-blog/SKILL.md
```

---

*Built for Claude · SEO Blog Skill v1*
