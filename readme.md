# Top Design Salon Website

Static website for Top Design Salon, a trusted hair salon at Kim Keat Palm in Toa Payoh, Singapore.

## Overview

The site is designed to help local clients understand the salon's services, pricing, story, opening hours, and contact options. The narrative focuses on practical hair care, honest consultation, hair health, and everyday confidence.

## Pages

- `index.html` - Homepage with hero, services, membership cards, story section, and contact preview.
- `about.html` - Salon background, trust-led positioning, values, process, and booking CTA.
- `contact.html` - WhatsApp contacts, phone number, address, opening hours, directions, and map.
- `faq.html` - Common questions about bookings, services, pricing, memberships, and consultations.
- `styles.css` - Shared styling, responsive layouts, animations, floating CTAs, and Botpress wrapper.

## Assets

Primary assets are stored in `Assets/`.

- `storeFront.png` / `storeFront.jpeg` - Salon storefront imagery.
- `cuts.jpg` - Hair service imagery.
- `hairCut.png`, `hairColor.png`, `hairPerm.png`, `hairTreatment.png`, `hairWash.png` - Service images.
- `Memberships.png` - Membership/beauty visual.
- `faveicon.png` - Site favicon/logo asset.

There are also root-level image files that may be older or duplicate assets. Prefer the `Assets/` versions when updating page content.

## Brand Message

Core positioning:

> Trusted hair care in Toa Payoh, designed around your lifestyle, hair health, and everyday confidence.

Preferred copy direction:

- Be specific, local, and practical.
- Mention Toa Payoh, Kim Keat Palm, honest advice, hair health, and manageable everyday results.
- Avoid generic luxury phrases unless they are supported by concrete proof.

## Contact Details

- Address: Lor 7 Toa Payoh, #01-258, Singapore 310018
- Landmark: Kim Keat Palm Market & Food Centre
- Store phone: 6909 8342
- WhatsApp: Kerry, +65 8363 3671
- WhatsApp: Xiao Lyu, +65 8361 9655
- Hours: Monday to Saturday, 10:00 AM to 8:00 PM; Sunday, 10:00 AM to 6:00 PM

## SEO and Structured Data

Each page includes:

- Meta description and keywords
- Canonical URL
- Open Graph metadata
- Twitter card metadata
- JSON-LD structured data

The official base URL is `https://top-design.vercel.app/`. If the site moves to a custom domain, update:

- Canonical links
- `og:url`
- `twitter:url`
- `og:image`
- `twitter:image`
- JSON-LD `url`, `@id`, image, and breadcrumb values

## Integrations

- Google Fonts for typography.
- Spline viewer on the homepage membership section.
- Google Maps embed on contact/location sections.
- WhatsApp floating CTA.
- Botpress webchat with a pulsing live-agent wrapper.

## Local Use

This is a static site. Open `index.html` directly in a browser to preview most changes. If testing external embeds or browser security behavior, serve the folder with a simple local server.

Example:

```powershell
python -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Maintenance Checklist

- Keep phone numbers and WhatsApp links consistent across all pages.
- Keep service prices aligned between `index.html`, `faq.html`, and JSON-LD.
- Check mobile layout after changing hero text, CTAs, or floating widgets.
- Revalidate JSON-LD after editing structured data.
- Update the deployed base URL if the Vercel domain changes.
