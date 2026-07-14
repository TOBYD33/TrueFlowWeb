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
Tagline primary:  "Your true financial flow."
Tagline personal: "The AI that remembers so you don't have to."
Tagline universal: "Your money. Your clients. Your life. One AI."

Never write: TrueFlio, Truelio, trueflio, TRUEFLOW, true flow (two words)
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

> 🔔 MAJOR UPDATE: WhatsApp is now LIVE and CONFIRMED WORKING. The
> narrative has flipped from earlier versions of this document.
> WhatsApp is now the PRIMARY hero of the landing page (target 80%
> of page emphasis), Tello/web app is now secondary, supporting
> content (target 20% of page emphasis). Do not use old "coming soon
> via WhatsApp" language anywhere, that period is over.

Use this to determine what to say is LIVE vs COMING SOON.
Never claim a coming soon feature is already working.

LIVE NOW (can say "available now", "start today", "try it now"):
- WhatsApp bot: message +2349020377046, real conversational AI
- Receipt scanning via WhatsApp photo
- Budget creation and tracking via WhatsApp chat
- Reminders via WhatsApp chat (bills, deadlines, trip planning,
  personal reminders, all confirmed working in real conversations)
- Tello AI Chat on web app (app.gettrueflow.com/chat), now secondary
  to WhatsApp in page emphasis, but still real and live
- Web dashboard: receipts, budgets, reminders, reports
- Client CRM: client folders, projects, income tracking
- Invoicing: generate and send PDF invoices
- Tax Hub: Track and Estimate (5 countries)
- Team management: staff, family member, accountant access
- Ambassador program, testing in Nigeria, Ghana, Kenya, USA

COMING SOON (still accurate to flag as upcoming):
- Smart Transfer Recognition (forward payment screenshots to
  automatically match and log client payments), this is a more
  advanced WhatsApp capability still in progress, distinct from
  basic receipt scanning which IS live
- Business card scanning for lead capture
- Mobile app (iOS and Android, listed as GetTrueFlow)

---

## Design Reference

Visual style reference: https://usexara.ai/
Take from Xara: full-width alternating feature sections with phone
mockups showing REAL WhatsApp conversation screenshots or realistic
mockups, since the actual product now works and can be shown
authentically, not as a hypothetical
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

## Logo — Current Status

TEMPORARY LOGO IN USE: gradient orb, off-center radial glow,
Electric Violet core blending into Mint Verify edge. File:
trueflow_logo_concept3_offcenter.png, transparent background,
1024x1024px. Use this exact file for the nav logo mark, favicon,
and any og:image or social preview image on this page. This is a
placeholder for early Founders Edition launch, not the final brand
mark. Do not build a new logo treatment, use the provided PNG as is
until a final vectorized logo replaces it.

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
7. Confirm no TrueFlow or trueflow anywhere in the file
8. Test the email form joinWaitlist function works on submit

---

## Andrea Aid — Cause Partnership Section

### What Andrea Is

Andrea (andreaaid.com) is a verified medical fundraising platform
connecting Nigerian hospitals with donors to fund life-saving medical
treatments for patients who cannot afford care. 100% verified
hospitals. Transparent donations. Real-time updates.

Tagline: "Connecting verified hospitals with caring donors to provide
life-saving medical treatments."

Empowered by: HRASA
Social: @andreaaidint on Instagram, Facebook, TikTok, LinkedIn
Live platform: andreaaid.com/cases (browse active patient cases)

### The 2% Commitment

2% of every TrueFlow subscription goes to Andrea every month.
This comes from TrueFlow's own revenue. The user is NEVER charged
extra. A user paying ₦7,500 pays exactly ₦7,500. TrueFlow routes
₦150 internally to Andrea.

Never describe this as an "extra charge" or "added fee".
Always describe it as "2% of your subscription goes to Andrea"
or "we give 2% to Andrea from every subscription."

### Where Andrea Appears on the Landing Page

Andrea appears in THREE places on the landing page:

PLACE 1: Hero section, small badge below the main CTA
  "Every subscription funds life-saving medical care via Andrea"
  In small teal text with a heart icon, directly below the
  "Join Founders Edition" button.

PLACE 2: Dedicated full-width section (position: after pricing,
before FAQ)
  This is the main Andrea section. See copy below.

PLACE 3: Footer, one line with Andrea logo link
  "2% of every subscription funds Andrea medical cases"
  with a link to andreaaid.com

### Andrea Section Full Copy and Layout

Section label: ANDREA AID PARTNERSHIP
Headline: "Every subscription helps save a life."

Body copy:
"2% of every TrueFlow subscription goes directly to Andrea,
a verified medical fundraising platform connecting Nigerian
hospitals with the funding needed to treat patients who
cannot afford care.

When you manage your finances on TrueFlow, you are also
helping a mother afford her surgery, a child receive the
treatment they need, or a family avoid losing everything
to a hospital bill.

One platform. Two missions. Your finances and someone else's
life, connected."

Community counter (live number from Supabase, updated monthly):
"TrueFlow users have contributed ₦[X] to Andrea"
Displayed as a large number in Mint Verify #00D4AA

Three bullet points with teal checkmarks:
  100% verified Nigerian hospitals
  Transparent, real-time donation tracking
  Every naira goes directly to patient care

Two buttons side by side:
  Primary: "Browse patient cases" → andreaaid.com/cases
  Secondary: "Learn about Andrea" → andreaaid.com

Andrea logo or name shown clearly in this section.

### What This Section Should NOT Do

Do not make specific claims about amounts raised by Andrea
(their site shows 0 as a placeholder, do not cite that)
Do not claim Andrea is "Nigeria's largest" or any superlative
Do not show a fake counter, the counter must be real or show
"Growing every month" as a placeholder until real data exists
Do not describe this as a donation the USER makes, it is a
commitment TrueFlow makes from its own revenue

### Founders Edition Connection

The Andrea partnership is one of the four Founders Edition benefits.
In the Founders Edition section, add:

"First visibility into the TrueFlow community Andrea contribution
 total before it becomes public"

as the fifth benefit bullet after the existing four.

### Andrea Section Visual Style

Background: slightly lighter than the page background, use #111118
to create a subtle section break without a harsh dividing line
Andrea's brand colour is teal #0d9488, which is close to TrueFlow's
Mint Verify #00D4AA. Use #00D4AA for consistency with TrueFlow's
palette, not Andrea's exact hex.
The section should feel warm and human, not corporate, use slightly
larger line height (1.9) for the body copy in this section
The community counter number should be the largest text element in
the section, even larger than the headline, since it is the most
tangible proof of impact

### /andrea-aid Page

Build a simple public page at gettrueflow.com/andrea-aid (a separate
section within the single HTML file, hidden by default, shown when
the URL hash is #andrea-aid, or as a separate linked page if the
build goes multi-page):

Content:
  TrueFlow + Andrea logos side by side
  "The TrueFlow x Andrea Partnership"
  Full explanation of the 2% model
  Community contribution total counter
  How the money is used (Andrea's verified hospital model)
  Link to browse active cases at andreaaid.com/cases
  Andrea social handles @andreaaidint

### Claude Code Instructions for Andrea Section

1. The Andrea section sits AFTER the pricing section and BEFORE
   the FAQ section in the page order
2. The community counter shows a real number if available from
   Supabase, or a placeholder "Growing every month" if not
3. The "Browse patient cases" button links to andreaaid.com/cases
4. The "Learn about Andrea" button links to andreaaid.com
5. The Andrea section uses the same alternating content and
   visual layout pattern as the feature sections, with the Andrea
   visual or counter on one side and the copy on the other
6. Never show ₦0 as the community counter, use the placeholder
   text instead if real data is not yet available
7. The small badge in the hero section sits directly below the
   main CTA button, not beside it

---

## Updated Positioning and Hero Copy

### The Anchor Line

"If your work, family, and personal data are in 15 places,
you only need to check 14 to forget something."

This single line defines TrueFlow's brand voice and positioning.
Every headline, caption, and section of this landing page should
connect back to this feeling. It is the reason TrueFlow exists.

### Updated Hero Section Copy

Replace the existing hero subheadline with this priority order.
Use Option A as the primary hero headline on the redesigned page.

HERO HEADLINE OPTION A (primary, most powerful):
  "Your work, family, and personal data
   are in 15 places.

   TrueFlow is the one that remembers
   all of them."

HERO HEADLINE OPTION B (the bold version):
  "You only need to check 14 places
   to forget something.

   We built the 15th."

HERO SUBHEADLINE (use below whichever headline is chosen):
  "TrueFlow is your personal AI for money, reminders, and clients.
   For individuals, families, and businesses.
   All by chatting with Tello on WhatsApp."

HERO BADGE (small, above the headline):
  "The AI that remembers so you don't have to"

HERO FORM NOTE (below the email input):
  "Free to start. No credit card. For you, your family,
   and your business."

### Updated FAQ Answers — Wider Positioning

Q1. What is TrueFlow?
Updated answer:
"TrueFlow is your personal AI assistant for everything that
matters: your money, your reminders, your clients, and your
deadlines. Instead of keeping track of 15 different places,
you just chat with Tello on WhatsApp or on the web app and
TrueFlow remembers everything for you. For individuals,
families, freelancers, and small businesses."

Q2. How does TrueFlow work?
Updated answer:
"Sign up at gettrueflow.com and join the Founders Edition.
You can immediately start chatting with Tello, our AI
assistant, on the web app. Tell Tello to track a payment,
set a reminder, create a client folder, or check your budget.
WhatsApp chat is coming soon. No forms to fill in. No
spreadsheets. Just conversation."

### Updated Everyday Use Cases Section

Replace the four cards with this updated copy that leads
with feeling not category:

Card 1: "Never lose a receipt again"
"Scan it the moment you get it. Tello reads the vendor,
amount, and date automatically. Your accountant gets the
report whenever they need it."
Detail: "Amaka · Lagos Island market trader"

Card 2: "Chase payments without the awkward calls"
"Forward the client's payment proof to TrueFlow. Tello
identifies who paid, how much, and logs it against their
project. No more mental math."
Detail: "Ibrahim · Freelance designer, Abuja"

Card 3: "One budget for the whole family"
"Add your spouse. Track household spending together.
Set limits for groceries, school fees, and transport.
Tello alerts you before anyone goes over."
Detail: "Marcus and Jennifer · Port Harcourt"

Card 4: "Never miss a deadline that matters"
"VAT. Salaries. Project deliveries. Supplier payments.
Tell Tello once and it reminds you before it is too late.
Works for birthdays too."
Detail: "Tunde · Agency owner, Lekki"

### Updated Trust Badges Row

Replace existing badges with these five that match
the wider personal positioning:

  "For individuals, families and businesses"
  "5 Countries supported"
  "One conversation, every answer"
  "Free to start"
  "Founders Edition open"

### Voice Test for Every Line on This Page

Before finalising any copy ask:
Would a Lagos market trader forward this to a friend
on WhatsApp and say "this is me"?
If yes: approved.
If no: rewrite it.

### Copy Rules for This Page

Never write: "AI financial assistant for African small
businesses" as the opening or hero line.

Never lead the page with business-only language.
The individual and family audience must feel included
from the very first sentence they read.

Always lead with the feeling.
The feeling is: "I will never lose track of anything
important again."
The features (receipts, clients, budgets, reminders)
are discovered after the feeling lands.

---

## Landing Page Rewrite — WhatsApp-First Narrative (Current Version)

### Why This Section Supersedes Earlier Hero/CTA Content

WhatsApp is now confirmed live and working. This section replaces
any earlier hero copy, CTA button text, and feature emphasis
elsewhere in this document that still reflects the old "coming soon"
framing or the "Join Founders Edition" CTA. The Ambassador program
still exists and is still mentioned, but it is no longer the primary
CTA button, trying the actual working product now is.

### The Primary CTA Change

Replace "Join Founders Edition" as the main button everywhere it
appears with:

```
Button text: "Try it out 👇"
Link: https://api.whatsapp.com/send?phone=2349020377046&text=Hi
```

This is the single most important change on the page. The main
action is no longer "join a waitlist for something not ready yet",
it is "message this number right now and watch it actually work."
This button appears in the nav, the hero, and the bottom CTA
section, exactly as the old "Join Founders Edition" button did in
those same positions, just with new text and a real, working
destination instead of a waitlist form.

The Ambassador application (the Google Form or equivalent from
earlier work) remains linked as a SECONDARY action, for the people
who try WhatsApp, love it, and want to go deeper as an early
Ambassador with the benefits already documented (lifetime pricing,
founding badge, direct line to the team). It is no longer the ONLY
path in, trying WhatsApp needs zero form, zero waiting, zero
commitment.

### Approved One-Liner Headlines (Rotate/Test These)

These are all approved, pulled directly from real work already done
in this brand. Use as hero headline options, section headlines, or
social captions as appropriate:

```
"Stress less. Flow more."

"Think more. Remember less."

"Money, clients, birthdays & bills, remembered by TrueFlow."

"Your money, clients & reminders, remembered by TrueFlow."

"If your work, family, and personal data are in 15 places,
 you only need to check 14 to forget something."
```

### The Hero, Rewritten

```
Small badge above headline:
  "🟢 WhatsApp is live. Message us right now."

Headline (primary):
  "Stress less.
   Flow more."

Subheadline:
  "Money, clients, birthdays & bills, remembered by TrueFlow.
   No app to download. No forms to fill. Just message us on
   WhatsApp and watch it work."

Primary button: "Try it out 👇" → wa.me link
Secondary, smaller link below: "or apply to be an early
  Ambassador" → Ambassador form

Small trust line below buttons:
  "🇳🇬 🇬🇭 🇰🇪 🇺🇸 — testing live in Nigeria, Ghana, Kenya,
   and the USA"
```

### One-Liners That Speak to Each Audience (Use Across Sections)

Family:
  "Never forget mum's birthday, school fees, or the light bill,
   ever again."

Individual:
  "Your money, your reminders, your life. Sorted in one chat."

Business owner:
  "Chase less. Get paid faster. Know your numbers, always."

### Feature Section Rebalance, 80/20 Split

Rebuild the six alternating feature sections from the earlier
website spec with this new emphasis. Sections should now show REAL
WhatsApp conversation mockups (styled after actual confirmed working
screenshots, receipts scanned, reminders confirmed, budgets set),
not hypothetical "coming soon" phone mockups.

```
80% of page emphasis, WhatsApp features, ALL marked
"Available now" with the teal badge, not amber
"coming soon" anymore:

Section A, RECEIPT CAPTURE
  "Scan any receipt. Instantly."
  Real WhatsApp-style mockup showing a receipt photo 
  sent and Tello's extracted data reply
  Badge: teal "Available now on WhatsApp"

Section B, REMINDERS THAT ACTUALLY REMIND
  "Tell it once. Never forget again."
  Mockup showing a reminder request and confirmation, 
  like the real "Pack travel bag" example
  Badge: teal "Available now on WhatsApp"

Section C, BUDGETS BY CHAT
  "Say the number. We'll track it."
  Mockup showing a budget being set in plain language
  Badge: teal "Available now on WhatsApp"

Section D, SMART TRANSFER RECOGNITION
  "Forward it. We'll figure it out."
  Badge: amber "Coming soon", this one specific 
  capability is genuinely still in progress

20% of page emphasis, Tello/web app, still real, 
just less prominent:

Section E, CLIENT CRM (web)
  "Every client. Every project. In one place."
  Badge: teal "Available now on web"

Section F, MEET TELLO (web, minimized)
  "Prefer typing on a screen? Tello's on the web too."
  Shorter section than the others, clearly positioned 
  as the alternative, not the main event
  Badge: teal "Available now on web"
```

### Social/Buzzword Language Bank

Use naturally throughout copy, captions, and section transitions,
do not force all of these into one place:

```
"It just works."
"No app. No forms. Just WhatsApp."
"The AI that actually remembers."
"Real. Live. Working right now."
"Try it before you believe it."
"Zero setup. One message."
"This isn't a demo, it's the real thing."
```

### FAQ Update

Update Q2 ("How does TrueFlow work?") to reflect WhatsApp as the
primary, immediate path:

```
Q2. How does TrueFlow work?
A: Message +2349020377046 on WhatsApp right now, no signup,
no download, no form. Say hi, and TrueFlow starts helping
immediately, scan a receipt, set a budget, ask for a reminder.
Want the fuller dashboard experience too? It's also on the web
at app.gettrueflow.com.
```

### Business Rules for This Rewrite

1. Every WhatsApp-related feature already confirmed working
   (receipts, budgets, reminders) must use the teal "Available now"
   badge, never amber "coming soon", the old framing is retired
2. Smart Transfer Recognition remains the one WhatsApp feature still
   genuinely marked "coming soon", since it is not yet confirmed
   working, do not accidentally flip this one too
3. "Try it out" replaces "Join Founders Edition" as the primary CTA
   everywhere, linking directly to the wa.me message link
4. The Ambassador program and its application form remain real and
   linked, but as a secondary path, not the primary CTA
5. Feature section content and visual emphasis should read as
   roughly 80% WhatsApp-focused, 20% Tello/web-focused, reflected in
   both the number of sections dedicated to each and the length/
   prominence of each section
6. Phone mockups should be styled to look like real, working WhatsApp
   conversations (matching the actual confirmed bot behavior already
   tested), not generic placeholder chat bubbles
