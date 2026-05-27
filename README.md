# AI YouTube Video Generator — Validation Landing Page

## What This Is

A static marketing landing page to validate demand for an AI-powered YouTube video generation service. This is a one-week market test, not a full product build.

The goal is to get paying customers before investing time in a full application.

## What the Product Does

Generates full-length (10-20 minute) niche finance explainer YouTube videos using AI. Each video includes:
- AI-written script (conversational, story-driven finance content)
- Cartoon-style visuals in a consistent art style
- A main character that appears throughout the video
- Professional AI voiceover
- Auto-generated captions
- Final 1080p MP4 delivered via download link

Videos take 1.5-3 hours to generate. Cost to the customer: $5 for the first video, $15 per video after that.

## What This Repo Contains

A single static HTML page only. No backend. No database. No authentication.

All dynamic functionality is handled by third-party links:
- Payment via Stripe payment link (external URL)
- Order submission via Tally form (external URL)
- Video fulfillment is manual — owner triggers the pipeline and emails the download link

## Page Structure

The page should have these sections in order:

1. **Hero** — headline, subheadline, CTA button
2. **Sample Video** — embedded YouTube video showing a real pipeline output
3. **How It Works** — three simple steps
4. **What You Get** — short feature list
5. **Pricing** — $5 first video, $15 per video after
6. **FAQ** — addresses the most common objections
7. **Final CTA** — repeat the order button

## Content

### Headline
"Get a Full-Length AI YouTube Video for $5"

### Subheadline
"10-20 minute finance explainer videos with custom visuals, voiceover, and captions — ready in under 3 hours."

### How It Works
1. Tell us your video topic
2. We generate your script, visuals, and voiceover
3. Download your finished 1080p video

### What You Get
- 10-20 minute finished YouTube video
- AI voiceover with consistent character
- Cartoon-style visuals matched to your script
- Auto-generated captions
- 1080p MP4 ready to upload

### Pricing
- First video: $5
- After that: $15 per video
- No subscription required

### FAQ
**How long does it take?**
Videos are ready within 1.5-3 hours of ordering.

**What topics can I request?**
Currently optimised for personal finance and money psychology topics. Examples: "Why most people never build wealth", "The truth about passive income", "How to stop lifestyle inflation."

**What do I do after paying?**
After payment you'll be redirected to a short form where you submit your topic. We'll email you when your video is ready with a download link.

**Can I see a sample first?**
Yes — watch the video above. That is a real output from our pipeline.

**What if I'm not happy with the result?**
First video is guaranteed — if you're not satisfied we'll refund your $5, no questions asked.

## Placeholder Values to Replace Before Launch

The following values need to be filled in before the page goes live:

- `YOUR_YOUTUBE_VIDEO_ID` — the YouTube video ID of your sample video (e.g. `dQw4w9WgXcQ`)
- `YOUR_STRIPE_PAYMENT_LINK` — the full URL of your Stripe payment link
- `YOUR_EMAIL_ADDRESS` — your contact email shown in the footer

## Deployment

This is a static HTML file. Deploy to GitHub Pages:

1. Push this repo to GitHub
2. Go to repo Settings → Pages
3. Set source to main branch, root folder
4. Site will be live at `https://yourusername.github.io/reponame`

## Success Criteria for This Test

**Target:** 3 paying customers from strangers (not people you know personally) within 7 days of launch.

If this target is met: proceed to build the full web application with auth, automated pipeline triggering, and payment processing.

If this target is not met: review messaging, sample video quality, and distribution channels before investing further in development.

## Distribution Plan

Post in these communities after launch:
- r/NewTubers
- r/YouTubeCreators  
- r/passive_income
- r/facelessyoutube
- Facebook groups for faceless YouTube creators
- Relevant Discord servers for content creators

## Tech Stack

- Pure HTML, CSS, JavaScript — no frameworks
- No dependencies
- No build step required
- GitHub Pages compatible