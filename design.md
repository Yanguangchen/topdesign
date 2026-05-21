# Design Guide

## Design Intent

The site should feel polished, warm, and credible without losing the character of a trusted neighbourhood salon. The visual direction should support the salon's practical positioning: careful hair care, honest advice, local familiarity, and everyday confidence.

## Visual Personality

- Warm and premium, but not overly formal.
- Local and approachable, not distant or luxury-for-luxury's-sake.
- Clean enough for easy scanning on mobile.
- Detailed enough to communicate care and professionalism.

## Layout Principles

- Make the first viewport immediately communicate the salon name, location, and value proposition.
- Keep contact paths visible and easy to act on.
- Use full-width sections with clear spacing instead of stacking too many card-like containers.
- Preserve strong visual hierarchy: hero headline, supporting copy, CTA, proof points, then services.
- Avoid nested cards. Cards should be used for repeated items such as services, values, FAQ entries, or membership tiers.

## Typography

- The site uses Rubik from Google Fonts.
- Use uppercase sparingly for labels, CTAs, and small interface text.
- Keep body copy direct and readable.
- Avoid oversized text inside compact panels.
- Do not use negative letter spacing.

## Color and Texture

The current palette uses dark salon neutrals, warm gold accents, and translucent glass effects.

Guidelines:

- Gold should signal action, highlights, and premium care.
- Dark translucent panels should be used where they improve contrast and readability.
- Avoid turning every section into the same gold/dark treatment.
- Green is reserved for WhatsApp.
- The Botpress wrapper uses the gold CTA language so it feels native to the site.

## Imagery

Use imagery that shows the real salon, real service context, or relevant hair care visuals.

Preferred assets:

- Storefront images for trust and location recognition.
- Service images for cuts, colour, perming, treatments, and wash/blowdry.
- Membership image where membership value is discussed.

Avoid:

- Generic beauty stock imagery that does not look connected to the salon.
- Dark, overly cropped, or atmospheric images that make the actual service unclear.

## Motion and Interaction

Motion should guide attention, not distract.

Current interaction patterns:

- Reveal-on-scroll for major sections and cards.
- Shimmer effect for primary CTAs and navbar CTA.
- Pulsing WhatsApp button with rotating speech prompt.
- Pulsing Botpress live-agent wrapper with a fixed speech prompt.
- FAQ accordion animation.

Guidelines:

- Keep animations short and smooth.
- Respect `prefers-reduced-motion`; the stylesheet already reduces animations for users who request it.
- Do not add competing floating widgets without checking mobile overlap.

## CTAs

Primary actions should be concrete:

- Explore Services
- Why Clients Return
- Contact Us
- Book your appointment
- Ask for hair advice
- Speak to a live agent

Avoid vague CTAs like "Begin your transformation" or "Enter the sanctuary." They do not match the current positioning.

## Copy and Narrative Fit

The visual design should reinforce the copy:

- Trust over glamour.
- Hair health over trend-chasing.
- Consultation over hard selling.
- Local Toa Payoh familiarity over generic luxury.

Use headings that sound specific and useful:

- Hair That Feels Right After You Leave
- Hair Services for Real Life
- A Toa Payoh Salon Built on Trust
- Plan Your Next Hair Appointment

## Responsive Considerations

- Floating WhatsApp sits bottom-left.
- Botpress live-agent wrapper sits bottom-right.
- Navbar CTA is hidden on smaller mobile navigation layouts.
- Long CTA text and speech bubbles must not overflow narrow screens.
- Check service cards, membership cards, map embed, and footer links on mobile after layout changes.

## Accessibility Notes

- Preserve semantic headings and page structure.
- Keep `aria-label` values on icon-only or floating controls.
- Maintain visible focus states.
- Ensure text contrast remains readable over translucent and image-backed sections.
- Use descriptive image alt text when the image communicates content; use empty alt text for purely decorative images.
