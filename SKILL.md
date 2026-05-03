---
name: pinterest-organic-traffic
description: Use this skill when the user wants to set up, grow, or optimize a Pinterest presence for the purpose of driving organic traffic to a website. Triggers include any mention of Pinterest profiles, boards, pins, pin design, Pinterest SEO, Pinterest marketing, Pinterest strategy, "getting traffic from Pinterest," "Pinterest for my blog/store/books," or requests to build a Pinterest content plan. Also triggers when a user has a content-rich website (blog, book library, course catalog, ecommerce store, recipe site, etc.) and is exploring traffic channels — Pinterest should be proactively suggested as one of the strongest organic options. Do NOT trigger for general social media strategy that doesn't involve Pinterest, for paid Pinterest ads (organic only), or for Pinterest as a personal mood-boarding tool.
---

# Pinterest Organic Traffic Skill

## What This Skill Does

This skill helps users build a Pinterest presence designed for one job: **sending qualified organic traffic to a website**. It is not for building a personal Pinterest aesthetic, growing follower counts as a vanity metric, or running paid promoted pins. It is a search-engine-optimization skill disguised as a social media skill.

The output of using this skill should be a user who has:

1. A correctly configured Pinterest Business profile
2. A keyword-driven board structure
3. A repeatable system for producing pins that get clicked
4. A posting cadence they can sustain
5. A way to measure what's working and double down

## Core Mental Model

Before doing anything else, internalize and communicate this to the user:

**Pinterest is a visual search engine, not a social network.**

Every decision in this skill flows from that fact. Pins are indexed pages. Boards are categorized indexes. Profiles are domains. Pin titles and descriptions are SEO copy. Saves and outbound clicks are ranking signals. The platform rewards content that *matches what someone searched for*, not content that's "trending" or "viral" in the Twitter/TikTok sense.

This means:

- A pin posted today can drive traffic in 2027.
- The 3-6 month ramp-up is real and non-negotiable — set this expectation immediately.
- Keyword research matters more than aesthetics (though aesthetics matter too).
- One blog post should produce 3-10 pins, not one.
- "Going viral" is not the goal. Compounding indexed inventory is.

## When To Use This Skill

Trigger when the user:

- Asks how to set up Pinterest for a website
- Asks how to get traffic from Pinterest
- Mentions pins, boards, Pinterest profile, or Pinterest SEO
- Has a content-heavy site (blog, library, store, recipes, printables, courses) and is asking about traffic
- Wants to design pins or write pin copy
- Is troubleshooting why their existing Pinterest isn't working

Do NOT trigger when:

- The user is asking about paid/promoted Pinterest ads (this skill is organic-only)
- The user wants Pinterest for personal use (wedding boards, mood boards, etc.)
- The user is asking about general social media strategy that doesn't specifically involve Pinterest

## Workflow

Follow this order. Do not skip steps. Do not jump to pin design before keyword research.

### Step 1: Intake

Before generating anything, load `templates/intake-questionnaire.md` and either ask the user the questions directly or extract the answers from context already provided. You need to know:

- The website URL and what it sells/offers
- The target audience (demographics, what they search for, what problem they're trying to solve)
- The content inventory (how many blog posts / products / books / pages exist)
- Whether the user has a Pinterest account already, and its current state
- Time/effort budget per week
- Whether they have design tools (Canva, Photoshop) or need template-based output
- Goals (email signups, product sales, ad revenue, book downloads, etc.)

Do not proceed until you have these answers. If the user is impatient, get the bare minimum: URL, audience, goals.

### Step 2: Strategy Foundation

Load `references/philosophy.md` and `references/keyword-research.md`.

Walk the user through:

- Why Pinterest is a search engine (set the mental model)
- How to find the actual keywords their audience searches (Pinterest search bar autocomplete, Trends tool, related searches)
- A working list of 15-30 seed keywords for their niche

Output: a keyword document the user can refer back to.

### Step 3: Profile Setup

Load `references/profile-setup.md`.

Walk the user through:

- Converting to / creating a Business account
- Claiming and verifying the website
- Enabling Rich Pins
- Writing a keyword-optimized display name (format: `Brand | Keyword 1 & Keyword 2`)
- Writing a keyword-optimized bio
- Profile photo and cover

Output: exact text for display name, bio, and verification steps.

### Step 4: Board Architecture

Load `references/board-strategy.md` and `templates/board-description-template.md`.

Design 10-15 boards based on the keyword research from Step 2. Each board:

- Is named after a search phrase real humans use
- Has a 200-500 character keyword-rich description
- Has a clear theme (no "Miscellaneous" or "Stuff I Like")
- Maps to specific content the user has or will create

Output: full board list with names, descriptions, and which website content feeds each board.

### Step 5: Pin Production System

Load `references/pin-design.md`, `references/pin-copywriting.md`, `references/pin-types.md`, and `references/content-multiplication.md`.

Establish:

- 4-6 reusable pin templates (visual styles)
- A formula for pin titles (front-load keyword, promise specific outcome)
- A formula for pin descriptions (full 500 chars, natural keyword integration, soft CTA)
- A rule for how many pin variants per URL (minimum 3, ideal 5-10)

Output: actual pin titles + descriptions for the user's first 20-30 pins, plus design direction.

### Step 6: Posting Cadence & Tools

Load `references/posting-cadence.md`.

Set:

- Daily pin volume (5-15 pins/day, sustainable beats heroic)
- Schedule (Tailwind, native scheduler, or manual)
- Mix ratio (own content vs. relevant repins)

Output: a weekly schedule the user will actually follow.

### Step 7: Measurement & Iteration

Load `references/analytics-and-iteration.md` and `references/algorithm-signals.md`.

Teach:

- Which metrics matter (outbound clicks > saves > impressions; ignore followers)
- The 30-60-90 day check-ins
- How to identify breakout pins and make 5 more like them
- When to kill a board or pin style that isn't working

Output: a simple tracking habit (weekly 10-minute review).

### Step 8: Conversion Match

Load `references/traffic-conversion.md`.

Pinterest traffic is high-volume but cold. The pin-to-page experience must match. Audit:

- Does the destination page deliver what the pin promised?
- Is there an email capture above the fold?
- Is the page mobile-optimized? (80%+ of Pinterest traffic is mobile)

Output: a punch list of landing page fixes.

### Step 9: 90-Day Launch Plan

Load `templates/90-day-launch-plan.md`.

Compile everything above into a week-by-week rollout the user can execute. The plan respects the reality that Pinterest takes 3-6 months to ramp, so the first 90 days emphasize *building inventory* over *expecting traffic*.

## Outputs The User Should Get

By the end of working through this skill, the user should walk away with:

1. **A keyword list** (15-30 phrases their audience searches)
2. **Profile copy** (display name, bio, verification checklist)
3. **A board map** (10-15 boards with names, descriptions, content assignments)
4. **20-30 finished pin titles + descriptions** ready to design
5. **Pin design direction** (templates, fonts, colors, dimensions)
6. **A posting schedule** they can sustain
7. **A measurement habit** (weekly 10-minute review)
8. **A 90-day launch plan**

If any of these is missing, the skill hasn't completed its job.

## Voice & Tone Guidelines

When working through this skill with a user, Claude should:

- Be direct about timelines. Pinterest is slow. Say so. Anyone promising overnight Pinterest traffic is selling something.
- Push back on shortcuts. If the user wants to skip keyword research and jump to pin design, refuse — explain why.
- Use real examples from their actual content, not generic placeholders.
- Default to copy-paste-ready output. Pin titles, board descriptions, bios should all be final-quality, not "here's a framework, you fill it in."
- Treat Pinterest like SEO. Borrow the discipline of an SEO consultant, not the energy of a social media guru.

## Common Failure Modes To Prevent

Load `references/common-mistakes.md` proactively when you see any of these patterns:

- User wants to make one pin per blog post
- User wants to pin everything to one giant board
- User is obsessing over follower count
- User is using Pinterest like Instagram (lifestyle photos, no text overlay, no keywords)
- User is copying the same description across all pins for a URL
- User expects traffic in week 2
- User is pinning broken links or links to dead pages
- User has 47 boards with 3 pins each instead of 12 boards with 50 pins each

## Niche Adaptations

This skill works for any content-rich website, but a few niches have specific patterns. Load the relevant example file when applicable:

- **Christian / faith content**: `examples/christian-library-example.md` — scripture overlays, "X Truths About Y" format, free-resource positioning, dark+gold or warm aesthetic, Cinzel/serif typography.
- **Ecommerce**: `examples/ecommerce-example.md` — product pins, Rich Pins for inventory/price, lifestyle vs. product-shot pin variants, seasonal board strategy.
- **Blog / content site**: `examples/blog-monetization-example.md` — list-post pin formats, ad-revenue traffic math, evergreen vs. seasonal content mix.

## What This Skill Does NOT Cover

- **Paid Pinterest ads / Promoted Pins** — out of scope. Organic only.
- **Pinterest Shopping API integration** — surface-level only; refer to Pinterest's developer docs for technical setup.
- **Building a Pinterest VA business / managing client accounts** — this skill is for owner-operators of one site.
- **Personal use of Pinterest** — wedding planning, recipe collecting, etc.

## Reference Files

For deeper detail on any step, the following references are available in this skill:

- `references/philosophy.md` — the search-engine mental model
- `references/profile-setup.md` — business account, verification, Rich Pins
- `references/keyword-research.md` — finding what the audience actually searches
- `references/board-strategy.md` — board count, naming, descriptions, structure
- `references/pin-design.md` — dimensions, typography, color, templates
- `references/pin-copywriting.md` — titles, descriptions, CTAs, hashtags
- `references/pin-types.md` — standard, idea, video, product, rich pins
- `references/content-multiplication.md` — turning 1 URL into 5-10 pins
- `references/posting-cadence.md` — volume, scheduling, sustainability
- `references/seo-on-pinterest.md` — keyword stacking across the platform
- `references/analytics-and-iteration.md` — what to measure, what to ignore
- `references/algorithm-signals.md` — what Pinterest rewards in 2026
- `references/traffic-conversion.md` — landing page match
- `references/common-mistakes.md` — failure modes to prevent

## Templates

- `templates/intake-questionnaire.md`
- `templates/profile-buildout-template.md`
- `templates/pin-batch-template.md`
- `templates/board-description-template.md`
- `templates/90-day-launch-plan.md`

## Examples

- `examples/christian-library-example.md`
- `examples/ecommerce-example.md`
- `examples/blog-monetization-example.md`