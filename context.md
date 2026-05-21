# Project Context

## Project

Top Design Salon is a static website for a neighbourhood hair salon in Toa Payoh, Singapore. The site presents the salon's services, story, membership value, FAQ, location details, and contact options.

## Primary Goal

Help local clients quickly understand why they should choose Top Design Salon and make it easy for them to contact the team through WhatsApp, phone, or the contact page.

## Brand Positioning

The strongest positioning is not generic luxury. The salon should be framed as a trusted Toa Payoh hair salon that combines careful technical work with honest, practical advice.

Core message:

> Trusted hair care in Toa Payoh, designed around your lifestyle, hair health, and everyday confidence.

## Audience

- Toa Payoh and Kim Keat residents looking for a reliable local salon.
- Working adults who want polished hair that is easy to maintain.
- Regular clients who value consistent upkeep, memberships, and practical advice.
- Clients considering colour, perming, rebonding, or treatments who need clear consultation before committing.
- English and Mandarin-speaking customers.

## Narrative Principles

- Lead with trust, locality, and real-life results.
- Emphasize hair health and honest consultation before chemical services.
- Avoid vague luxury language such as "sanctuary", "artistry", "bespoke", or "transformation" unless backed by specific proof.
- Use concrete details: Toa Payoh, Kim Keat Palm, since 2015, service prices, opening hours, WhatsApp contacts, and practical aftercare.
- Keep CTAs direct: check availability, ask about pricing, book an appointment, or get hair advice.

## Key Site Facts

- Business name: Top Design Salon
- Location: Lor 7 Toa Payoh, #01-258, Singapore 310018
- Landmark: Kim Keat Palm Market & Food Centre
- Store phone: 6909 8342
- WhatsApp contacts: Kerry at +65 8363 3671, Xiao Lyu at +65 8361 9655
- Opening hours: Monday to Saturday, 10:00 AM to 8:00 PM; Sunday, 10:00 AM to 6:00 PM
- Established: 2015
- Service starting prices: haircuts from $28, wash and blowdry from $18, treatments from $45, colouring from $80, perming or rebonding from $120

## Current Pages

- `index.html`: homepage, services, memberships, story, contact preview
- `about.html`: salon story, values, process, CTA
- `contact.html`: WhatsApp contacts, store details, map
- `faq.html`: appointment, pricing, membership, consultation, and location questions
- `styles.css`: shared visual system, responsive layout, animations, floating WhatsApp, Botpress wrapper

## Technical Notes

- This is a static HTML/CSS site with inline page scripts.
- Shared assets live in `Assets/`.
- The site uses Google Fonts, Spline for the membership visual, Google Maps embed, WhatsApp links, and Botpress webchat.
- SEO metadata, Open Graph metadata, Twitter card metadata, canonical URLs, and JSON-LD structured data are included on the HTML pages.
- Official deployed base URL: `https://top-design.vercel.app/`. Replace this in canonical, OG/Twitter, JSON-LD, sitemap, and robots fields if a custom domain is connected.

## Important Implementation Decisions

- The copy was shifted from abstract premium salon language to a trust-led local positioning.
- The navbar CTA uses the same shimmer treatment as primary buttons.
- A pulsing Botpress wrapper prompts users to speak to a live agent.
- WhatsApp remains a separate floating CTA on the lower-left side.
