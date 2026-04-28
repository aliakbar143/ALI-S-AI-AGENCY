# NexaAI — Landing Page

## What This Is
A one-page AI agency website for **NexaAI**. The goal is to attract businesses and get them to reach out via WhatsApp, Instagram, or email about AI services.

## Services Offered
1. **WhatsApp Automation** — automating customer conversations and lead qualification on WhatsApp
2. **AI Chatbots for Websites** — custom AI assistants trained and embedded into business websites
3. **Content Creation & AI Ads** — AI-generated video ads and content using Arcads.AI

## Tech Stack
- Pure **HTML5 + CSS3 + Vanilla JavaScript** — no frameworks, no build tools
- Static site — deployable by dragging the folder into Netlify

## Design Rules
- **Background:** `#0a0a0f` (near black)
- **Primary accent:** `#6c63ff` (electric purple)
- **Secondary accent:** `#00f0ff` (cyan)
- **Text:** `#f0f0f0`
- **Muted text:** `#888`
- Glassmorphism cards: `backdrop-filter: blur()` + semi-transparent bg + subtle border
- 3D card tilt on hover via JS mouse tracking
- Animated gradient orbs / particle canvas in hero background
- Neon glow on text and cards
- Fully responsive — mobile-first

## Honesty Rules (Critical)
- **NO fake testimonials** — we are a brand new agency, don't add reviews we don't have
- **NO fake pricing** — don't add a pricing section unless explicitly asked
- **NO inflated stats or fake social proof**
- Keep every claim real and honest

## Contact Placeholders
Replace these before publishing:
- `[WHATSAPP_NUMBER]` → full number with country code (e.g. `+255712345678`)
- `[@INSTAGRAM_HANDLE]` → Instagram username without @ (e.g. `nexaai.official`)
- `[EMAIL_ADDRESS]` → business email (e.g. `hello@nexaai.com`)

WhatsApp link format: `https://wa.me/[WHATSAPP_NUMBER]`
Instagram link format: `https://instagram.com/[@INSTAGRAM_HANDLE]`
Email link format: `mailto:[EMAIL_ADDRESS]`

## File Structure
```
/
├── CLAUDE.md
├── index.html
├── css/
│   └── style.css
└── js/
    └── main.js
```

## Sections (in order)
1. **Hero** — headline, sub-headline, WhatsApp CTA + View Services scroll button, animated background
2. **Services** — 3 glassmorphism cards with 3D tilt hover
3. **Why NexaAI** — short honest pitch, 3 differentiators (no fake stats)
4. **Contact** — 3 large buttons: WhatsApp, Instagram, Email
5. **Footer** — brand name + copyright + contact icons

## Deployment
1. Go to netlify.com
2. Click "Deploy manually"
3. Drag the entire project folder onto Netlify
4. Done — get a free `.netlify.app` URL

## What NOT to Add (unless asked)
- Pricing tables
- Testimonials or reviews
- Blog section
- Team/about page
- Any external JS libraries (keep it vanilla)
- Animations that require npm packages
