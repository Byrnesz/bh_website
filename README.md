# Bridging Hearts Bereavement Support Group
## Website Prototype — Session Bundle
**Date:** March 11, 2026  
**Prepared by:** Claude (Anthropic) in collaboration with Mike

---

## Contents of This Bundle

| File | Description |
|------|-------------|
| `BridgingHearts_Website.html` | Full multi-page website prototype |
| `README.md` | This instruction document |

---

## About the Prototype

This is a fully functional single-file HTML prototype for the Bridging Hearts Bereavement Support Group website. It was built from the design criteria, copy, and SEO strategy developed in a prior ChatGPT session (sourced from your Google Drive document) and refined interactively in this Claude session.

### Pages Included
1. **Home** — Hero section, trust strip, welcome/promise, three pillars, support groups highlight, testimonials, donation impact tiers
2. **About** — Organization story, mission statement, core values
3. **Support Groups** — What to expect, who can join, open invitation
4. **Resources** — Six topic cards including the new *Group Activities & Events* card
5. **Get Involved** — Volunteer, partner, share your story, grant-maker section
6. **Donate** — Gift amount selector, donor form, impact breakdown
7. **Contact** — Message form, contact info, newsletter sign-up

---

## How to Open the Prototype

1. **Double-click** `BridgingHearts_Website.html` — it will open in your default web browser
2. No internet connection is required *except* to load the Google Fonts (Cormorant Garamond + Nunito) — the site will still work offline but will fall back to system fonts
3. All navigation is fully functional — click any tab or button to move between pages

---

## Design Specifications

### Color Palette
| Name | Hex | Usage |
|------|-----|-------|
| Teal | `#3a7a74` | Primary brand, buttons, headings |
| Teal Light | `#5a9e97` | Hover states |
| Teal Pale | `#eaf4f3` | Backgrounds, highlights |
| Rose | `#c07b7b` | Accent, donate CTA, sticky button |
| Gold | `#c9a84c` | Impact numbers, accents |
| Cream | `#faf8f4` | Page background |
| Ink | `#2a2420` | Body text |

### Typography
- **Headings:** Cormorant Garamond (serif) — elegant, warm, trustworthy
- **Body:** Nunito (sans-serif) — friendly, readable, approachable

### Logo Mark
Custom SVG heart-bridge logo embedded directly in the HTML — no external image file needed.

---

## Placeholder Content to Replace

The following items are marked with placeholder text and need your real details before going live:

| Location | Placeholder | Replace With |
|----------|-------------|-------------|
| Footer & Contact page | `info@bridgingheartsnh.org` | Your real email address |
| Contact page | Phone: "Available upon request" | Your phone number (if desired) |
| Support Groups page | Meeting schedule TBD | Actual days/times/locations |
| Support Groups page | In-person/virtual options | Confirm format |
| Support Groups page | "Free or donation-based" | Confirm pricing model |
| Donate page | Donation form | Connect to real payment processor (e.g., Stripe, PayPal, Zeffy) |
| Contact page | Contact form | Connect to a form handler (e.g., Formspree, EmailJS) |
| Testimonials | Anonymous quotes | Real (anonymized) participant quotes when available |
| About page | Org origin story | Your personal founding narrative |
| Footer | Social media buttons (f, in, tw) | Real social media links |

---

## The "Together & Connected" Button

On the **Resources page**, the *Group Activities & Events* card contains a **Together & Connected →** button that currently shows a placeholder alert. This is intentionally left as a stub for a future page to be built.

**To activate it when ready:** A new "Together & Connected" page needs to be added to the site following the same pattern as existing pages. Let Claude know when you're ready to build it.

---

## Resource Card: Group Activities & Events

**Final approved text (Option C, agreed March 11, 2026):**

> *Science tells us that informal connection is powerful medicine. When group participants gather outside structured sessions, the bonds that form can meaningfully support both emotional and physical wellbeing.*

This replaced earlier draft text based on a review-and-suggest workflow where three options were presented before implementation.

---

## SEO Notes

Meta titles and descriptions are embedded in the `<head>` of the HTML file for the home page. For a live multi-page website, each page will need its own HTML file with unique meta tags as outlined in the SEO strategy document from your Google Drive session history.

**Primary keywords targeted:**
- grief support group
- bereavement support
- support after losing a loved one
- grief support groups near me (add your NH region)

---

## Next Steps (From Session)

- [ ] Fill in all placeholder content (see table above)
- [ ] Build out the **Together & Connected** page
- [ ] Connect donation form to a payment processor
- [ ] Connect contact form to an email handler
- [ ] Add real testimonials (anonymized) as they become available
- [ ] Add NH regional location keywords for local SEO
- [ ] Set up Google Business Profile
- [ ] Organize project files into a Google Drive folder (planned)
- [ ] Consider pushing files to GitHub repository (connector available)

---

## Session History Summary

This prototype was built and refined across the following steps in this Claude session:

1. Google Drive document retrieved — containing full ChatGPT session with website goals, sitemap, page-by-page copy, visual theme, SEO strategy, meta titles/descriptions, on-page SEO checklist, DIY SEO audit template, and logo concept directions
2. Full 7-page prototype built from those specifications
3. Console error fixed (`showPage is not defined`) — function moved to `window` scope
4. Resource card **"Helping Grieving Children"** replaced with **"Group Activities & Events"** per Mike's request
5. New card text reviewed via suggest-first workflow — Option C selected and implemented

---

*Bridging Hearts Bereavement Support Group — "We need not walk alone."*
