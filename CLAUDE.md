# TrueFlow Marketing Website — CLAUDE.md
> This file is read automatically by Claude Code on every session.
> Do not delete it. Keep it updated as the project evolves.
> Last updated: July 2026

---

## What This Project Is

This is the TrueFlow public marketing website, a single-page landing
site that lives at gettrueflow.com. It is a separate project from the
web app (app.gettrueflow.com) and the WhatsApp bot. Its only job is to
explain the product, capture Founders Edition waitlist emails, and
convert visitors into signups.

This is NOT the web app dashboard. Do not add login flows, Supabase
calls, or product functionality here. Everything here is pure HTML,
CSS, and vanilla JavaScript in a single self-contained file.

---

## Company and Brand

Legal company:   True Financial Flow Ltd
Brand name:      TrueFlow
Pronounced:      True-Flow (like "True Flow" said together)
App Store name:  GetTrueFlow
Domain:          gettrueflow.com
Web app:         app.gettrueflow.com
Email:           gettrueflow@gmail.com
Social handles:  @gettrueflow on Instagram, X, TikTok
Tagline:         "Your true financial flow."

Never write: TrueFlio, Truelio, TrueFlow® (trademark conflict),
             trueflio, TRUEFLOW
Always write: TrueFlow (capital T, capital F, one word)

---

## What TrueFlow Actually Does

TrueFlow is an AI-powered financial assistant for African small
businesses, freelancers, and families. It tracks money in and money
out through three channels sharing one backend:

1. WhatsApp Bot — conversational AI, scan receipts by photo, forward
   client payment screenshots, set budgets and reminders by chat
2. Web App (app.gettrueflow.com) — full dashboard, client CRM,
   invoicing, Tax Hub, team management, Tello AI chat
3. Mobile App — on-the-go companion (coming after web app)

Two directions of money:
- MONEY OUT: receipts, expenses, budgets, bills, reminders
- MONEY IN: client payments, projects, invoices, income tracking

---

## Current Feature Status — CRITICAL FOR COPY ACCURACY

Use this to determine what to say is LIVE vs COMING SOON.
Never claim a coming soon feature is already working.

LIVE NOW (can say "available now", "start today"):
- Tello AI Chat on web app (app.gettrueflow.com/chat)
- Web dashboard: receipts, budgets, reminders, reports
- Client CRM: client folders, projects, income tracking
- Invoicing: generate and send PDF invoices
- Tax Hub: Track and Estimate (5 countries)
- Team management: staff, family member, accountant access
- Founders Edition waitlist at gettrueflow.com

COMING SOON (say "coming soon via WhatsApp", never "available"):
- WhatsApp receipt scanning via bot
- Smart Transfer Recognition (forward payment screenshots)
- WhatsApp budget and reminder commands
- WhatsApp client creation via conversation
- Mobile app (iOS and Android, listed as GetTrueFlow)

---

## Design Reference

Visual style reference: https://usexara.ai/
Take from Xara: full-width alternating feature sections with phone
mockups, dark background, bold two-line headlines, minimal nav,
single CTA repeated throughout, ALL CAPS eyebrow labels per section.
Do better than Xara: more sections, more features covered, a proper
features grid, Founders Edition framing, Tello AI highlighted as
available now, five-country Tax Hub, team access section.

---

## Brand Colours

| Name | Hex | Usage |
|------|-----|-------|
| Electric Violet | #6C63FF | Primary, CTAs, buttons, eyebrow labels |
| Mint Verify | #00D4AA | Tello, income, success, "Flow" in hero |
| Rich Black | #0A0A0F | Page background, dark surfaces |
| Cloud White | #F5F5F7 | Body text, card backgrounds |
| Alert Red | #FF6B6B | Urgency only |
| Warn Amber | #FFB545 | Budget warnings, coming soon badges |
| WhatsApp Green | #25D366 | WhatsApp channel badges only |

---

## Typography

Google Fonts (import both):
- Space Grotesk: headings, nav, buttons, eyebrow labels, numbers
- Inter: body copy, descriptions, form fields, footer

Font sizes:
- Hero headline: 72-96px, Space Grotesk 700
- Section headlines: 48-64px, Space Grotesk 700
- Eyebrow labels: 11px, Space Grotesk 600, letter-spacing 3px, uppercase
- Body copy: 16-18px, Inter 400, line-height 1.7
- Buttons: 14px, Space Grotesk 600

---

## Page Structure (Build in This Exact Order)

1.  Navigation
2.  Hero
3.  Trust badges row
4.  Feature section A: Receipt Capture
5.  Feature section B: Smart Transfer Recognition
6.  Feature section C: Client CRM
7.  Feature section D: Budgets and Reminders
8.  Feature section E: Tax Hub
9.  Feature section F: Tello AI Assistant
10. Everyday use cases (2x2 grid)
11. How it works (3 steps)
12. Team and family access
13. Pricing (3 cards, waitlist mode)
14. FAQ (7 questions)
15. Bottom CTA (Founders Edition email capture)
16. Footer

---

## Feature Section Specs

All six follow the Xara alternating layout pattern.
Each section: eyebrow | headline | body | CTA | mockup opposite side.

A. RECEIPT CAPTURE (content left, mockup right)
   Headline: "Scan any receipt. Instantly."
   Body: "Photo, screenshot, or WhatsApp forward. Tello reads the
   vendor, amount, date and category in seconds. No typing. No manual
   entry. Works for businesses, families and individuals."
   Status badge on mockup: COMING SOON VIA WHATSAPP (amber)

B. SMART TRANSFER RECOGNITION (mockup left, content right)
   Headline: "Forward it. We'll figure it out."
   Body: "When a client sends you payment proof on WhatsApp, forward
   it to TrueFlow. Our AI reads the bank transfer, identifies the
   client, and logs the income automatically. Works with GTBank,
   Access, Zenith, UBA, Opay, Palmpay, Moniepoint, Kuda and every
   major Nigerian bank."
   Status badge on mockup: COMING SOON VIA WHATSAPP (amber)

C. CLIENT CRM (content left, mockup right)
   Headline: "Every client. Every project. In one place."
   Body: "Create client folders, track project fees and deadlines,
   log incoming payments, and generate invoices. See your outstanding
   balance across all clients at a glance."
   Status badge on mockup: AVAILABLE NOW (teal)
   Mockup: web dashboard, not a phone

D. BUDGETS AND REMINDERS (mockup left, content right)
   Headline: "Know before you overspend."
   Body: "Set budgets per category and get alerts before you hit the
   limit. Remind yourself about VAT deadlines, salary days, supplier
   payments and project deliveries. Set it once and TrueFlow handles
   the rest."
   Status badge on mockup: COMING SOON VIA WHATSAPP (amber)

E. TAX HUB (content left, mockup right)
   Headline: "Track your tax. Estimate your liability."
   Body: "TrueFlow tracks VAT and tax from every transaction. The Tax
   Hub shows your estimated liability across Nigeria, Kenya, Ghana,
   USA, and the UK. Always an estimate, always paired with your
   accountant share link."
   Status badge on mockup: AVAILABLE NOW (teal)
   Mockup: web dashboard Tax Hub page

F. TELLO AI ASSISTANT (mockup left, content right)
   Headline: "Meet Tello. Available right now."
   Body: "Tello is TrueFlow's built-in AI assistant, live on the web
   app today. Ask about your spending, create a client, set a
   reminder, or get a budget breakdown. Tello knows your finances and
   answers in seconds. No WhatsApp needed to get started."
   Status badge on mockup: AVAILABLE NOW (teal)
   Mockup: web browser with Tello chat bubble open

---

## Pricing Plans

Three cards only. All buttons say "Join Founders Edition".
Note below cards: "Nigerian Naira pricing also available:
₦7,500/mo Starter, ₦15,000/mo Pro."

Free: $0 forever
- 10 receipts per month
- 1 user
- Tello AI Chat
- Basic dashboard

SME Starter: $19 per month [MOST POPULAR]
- Unlimited receipts
- 5 staff members
- 10 clients
- Inventory tracking
- Accountant share link

SME Pro: $39 per month
- Unlimited everything
- 15 staff members
- 50 clients
- Invoice generation
- Advanced analytics
- Tax Hub

---

## FAQ Questions and Answers

Q1. What is TrueFlow?
A: TrueFlow is an AI-powered financial assistant for African small
businesses, freelancers, and families. It tracks your expenses,
manages your client income, generates invoices, and helps you stay
on top of budgets and tax, all through a web dashboard and soon via
WhatsApp.

Q2. How does TrueFlow work?
A: You start by signing up at gettrueflow.com. From the web app you
can immediately start tracking expenses, managing clients, and
chatting with Tello, our AI assistant. WhatsApp scanning and Smart
Transfer Recognition are coming soon.

Q3. Is my financial data secure?
A: Yes. All data is encrypted in transit and at rest. TrueFlow uses
Supabase's enterprise-grade PostgreSQL database with row-level
security, meaning each user can only ever access their own data.

Q4. Do I need to download an app to start?
A: No. TrueFlow works in your browser at app.gettrueflow.com from
day one. A mobile app for iOS and Android (listed as GetTrueFlow) is
coming soon.

Q5. Can my staff or family members use it too?
A: Yes. You can invite staff to submit receipts and expenses, add
family members to a shared household budget, or share a read-only
link with your accountant. Each person gets exactly the access level
you choose.

Q6. What Nigerian banks does Smart Transfer Recognition support?
A: GTBank, Access Bank, Zenith Bank, UBA, First Bank, Opay,
Palmpay, Moniepoint, Kuda, and Stanbic IBTC. This feature is
coming soon via WhatsApp.

Q7. What is the Founders Edition?
A: Founders Edition is our early access programme for the first
users who help shape TrueFlow. Founders get lifetime discounted
pricing, a permanent Founding Member badge, a direct WhatsApp line
to the team, and first access to every new feature before public
release.

---

## Coming Soon Badge Style

Amber (coming soon via WhatsApp):
  background: rgba(255,181,69,0.15)
  border: 1px solid rgba(255,181,69,0.3)
  color: #FFB545
  font: 10px Space Grotesk 600 uppercase letter-spacing 1.5px
  text: "Coming soon via WhatsApp"
  position: bottom-left of mockup, overlaid

Teal (available now):
  background: rgba(0,212,170,0.15)
  border: 1px solid rgba(0,212,170,0.3)
  color: #00D4AA
  text: "Available now"

---

## Technical Rules

1. Single self-contained HTML file named gettrueflow-landing.html
2. All CSS and JavaScript inline, no external files
3. Only external resource: Google Fonts import link
4. No Supabase, no API calls, no authentication of any kind
5. Phone mockups: pure CSS and HTML, no image files
6. Dashboard mockups: CSS representations, not screenshots
7. All animations: CSS only, Intersection Observer for scroll fades
8. Mobile: alternating sections stack vertically under 768px
9. Email form uses joinWaitlist(emailId, successId, formId) pattern
10. Nav becomes solid #0A0A0F on scroll via scroll event listener

---

## Copy Rules

- No dashes in user-facing copy
- Tone: warm, direct, honest, like a smart friend
- Nigerian context: Nigerian names, Naira amounts, Nigerian banks
- Never overclaim: coming soon features always say "coming soon"
- "Flow" in the hero headline is always in Mint #00D4AA
- "Founders Edition" always capitalised, always both words
- Footer: "True Financial Flow Ltd" not "TrueFlow Ltd"
- All plan buttons: "Join Founders Edition" not "Get started"

---

## Claude Code Instructions

1. Always read this CLAUDE.md before touching any file
2. Deliverable: gettrueflow-landing.html (single file)
3. Check coming soon badges appear on sections A, B, D only
4. Check available now badges appear on sections C, E, F only
5. Verify all CTA buttons say "Join Founders Edition"
6. Confirm footer says "True Financial Flow Ltd"
7. Confirm no TrueFlio or trueflio anywhere in the file
8. Test the email form joinWaitlist function works on submit
