# Trustrida — Guide & FAQ (Seat 8 Contribution)

This covers my part of the **Trustrida** project, built for Webbo3 Academy's Payload Pod build. Trustrida is a verification site that lets a first-time buyer confirm a delivery rider is real — photo, ID, plate number, live dispatch status — before they pay.

**My seat:** Seat 8 — Guide and FAQ (duty: copy and tone)

## What I Built

- **`faq.html`** — the Guide & FAQ page. 11 questions across four categories (Trust & Identity, Payment, Using the Link, Why This Over Alternatives), written as an accordion so buyers can jump straight to what they're worried about.
- **`contact.html`** — a contact page with a working form (name, email, subject, message) and an info panel, styled to match the rest of the site.
- **`css/style.css`** — shared styles for the site header/nav and footer, built on top of the brand tokens.

## Structure

```
├── faq.html
├── contact.html
├── css/
│   ├── brand.css      # shared design tokens (not authored by me — from the pod's brand sheet)
│   └── style.css      # header/nav + footer styles (my contribution)
```

## Brand Tokens Used

All colors and fonts come from `css/brand.css` as CSS variables — I didn't hardcode any values, so my pages stay in sync if the palette changes.

| Color | Hex | Role |
|---|---|---|
| 🟢 Trust Green | `#087F5B` | Buttons, verification, accents |
| 🔵 Deep Navy | `#102A43` | Headings, text, navigation |
| 🟡 Amber | `#8A5A00` | Pending/attention states |
| 🟠 Warm Cream | `#FFF8EE` | Backgrounds |
| ⚪ White | `#FFFFFF` | Cards, forms |

## My Duty (Copy & Tone)

Wrote the FAQ questions as things a real first-time buyer in Lagos would actually ask before paying — not filler to hit a number. Read through the page for tone and kept answers short and direct rather than templated.

## Notes

- The contact form is UI-only for now — it doesn't send email yet. Would need a backend or a service like Formspree before real launch.
- 
