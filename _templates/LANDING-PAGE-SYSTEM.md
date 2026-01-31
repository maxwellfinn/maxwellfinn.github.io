# Landing Page Creation System

This system allows you to create and deploy landing pages entirely through conversation with Claude. No code editing required - just describe what you want, and the page gets built and pushed to production.

## How It Works

1. **Tell me what you need** - Describe your landing page (product, offer, target audience)
2. **I select the template** - Based on your needs, I pick the best template type
3. **I customize it** - Fill in your content, colors, images, and CTAs
4. **I deploy it** - Create the directory, save the file, and push to GitHub Pages
5. **You get the URL** - Your page is live at `maxwellfinn.github.io/your-page-name/`

## Available Templates

### 1. Listicle (`listicle.html`)
Best for: Educational content, "X reasons why...", feature comparisons
- Numbered list format with images
- Stats and data points
- Quote blocks and testimonials
- Dark theme with gold accents (customizable)

### 2. Advertorial (`advertorial.html`)
Best for: Native advertising, editorial content, long-form sales copy
- Article/blog-style layout
- Byline and publication styling
- Problem/solution comparison cards
- Case studies and social proof
- FAQ sections
- Progress reading bar

### 3. VSL - Video Sales Letter (`vsl.html`)
Best for: Video-focused offers, webinar replays, product demos
- Hero section with video player
- Play button overlay
- Trust indicators
- Testimonial grid
- Clean, focused design

### 4. Simple Sales Page (`simple-sales.html`)
Best for: Direct offers, product launches, simple conversions
- Bold hero section
- Feature cards grid
- Pricing/offer card
- Minimal and fast-loading

## Quick Start Examples

### Example 1: Create an advertorial for a SaaS product
```
"Create an advertorial landing page for my AI writing tool called WriteGenius.
Target audience: content marketers. Main benefit: write 10x faster content.
Price: $49/month. CTA goes to writegenius.io"
```

### Example 2: Create a listicle for a community/membership
```
"Create a listicle landing page with 5 reasons to join my mastermind group
called 'Growth Circle'. It costs $500/month and we have 50 members who have
seen 2x revenue growth on average. I have testimonials from John (SaaS founder)
and Sarah (agency owner)."
```

### Example 3: Create a VSL page
```
"Create a video sales letter page for my course on Facebook Ads. The video
is at /my-video.mp4. Main promise: Learn to run profitable ads in 30 days.
Price: $997 one-time."
```

## Customization Options

When creating a landing page, you can specify:

**Branding:**
- Logo image path
- Brand name
- Brand URL
- Color scheme (dark/light, accent colors)

**Content:**
- Headlines and subheadlines
- Body copy and paragraphs
- Statistics and data points
- Testimonials (name, role, quote, result)
- Features and benefits
- FAQ items

**Media:**
- Hero background image
- Section images
- Video URLs (YouTube, Vimeo, or self-hosted)
- Logos and icons

**Conversion:**
- CTA button text
- CTA destination URL
- Urgency elements
- Guarantee text
- Pricing information

## Directory Structure

```
maxwellfinn.github.io/
├── _templates/           # Template files (don't edit these)
│   ├── listicle.html
│   ├── advertorial.html
│   ├── vsl.html
│   ├── simple-sales.html
│   └── LANDING-PAGE-SYSTEM.md
├── your-landing-page/    # Your custom landing pages
│   ├── index.html
│   └── images/
├── another-page/
│   ├── index.html
│   └── assets/
└── ...
```

## Existing Landing Pages

| Directory | Type | Brand/Product | Status |
|-----------|------|---------------|--------|
| ba-listicle | Listicle | Board of Advisors | Live |
| ba-sales-page | Sales Page | Board of Advisors | Live |
| board-of-advisors-vsl | VSL | Board of Advisors | Live |
| createassistants-advertorial | Advertorial | Create Assistants | Live |
| createassistants-listicle | Listicle | Create Assistants | Live |
| createassistants-vsl | VSL | Create Assistants | Live |
| duet-advertorial | Advertorial | Duet | Live |
| duet-calculator | Calculator | Duet | Live |
| human-reach-listicle | Listicle | Human Reach | Live |
| human-reach-quiz | Quiz | Human Reach | Live |
| minisocial-advertorial | Advertorial | Minisocial | Live |
| minisocial-listicle | Listicle | Minisocial | Live |
| nomad-lane | Multiple | Nomad Lane | Live |
| promissory-advertorial | Advertorial | Promissory | Live |
| promissory-vsl-funnel | VSL | Promissory | Live |
| the-handy | Multiple | The Handy | Live |
| multiman-services-* | Various | Multiman Services | Live |

## Color Schemes Reference

### Dark + Gold (Premium)
```css
--bg-dark: #0a0e1a;
--accent: #EAA34F;
```

### Dark + Orange (Modern)
```css
--bg-dark: #0a0a0a;
--accent: #ff5722;
```

### Dark + Blue (Corporate)
```css
--bg-dark: #0f172a;
--accent: #3b82f6;
```

### Dark + Green (Growth)
```css
--bg-dark: #0a0a0a;
--accent: #22c55e;
```

## Deployment Workflow

When you ask me to create a landing page:

1. I create a new directory: `/your-page-name/`
2. I generate the HTML from the template with your content
3. I save it as `/your-page-name/index.html`
4. I commit and push to GitHub
5. Your page is live at `https://maxwellfinn.github.io/your-page-name/`

Pages typically go live within 1-2 minutes after push.

## Need Changes?

Just tell me what to update:
- "Change the headline to..."
- "Add a new testimonial from..."
- "Update the CTA to point to..."
- "Change the color scheme to blue"

I'll make the edit and push the update immediately.
