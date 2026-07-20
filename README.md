# IronForge Gym — Landing Page

A premium, single-page landing website for a local strength & conditioning gym. Built to convert visitors into trial members via a direct WhatsApp contact flow.

## Features

- Responsive hero section with background photography
- Programs section (Strength, Fat loss, Functional fitness) with images
- Pricing table with 3 membership tiers (Basic / Pro / Elite)
- Photo gallery strip
- WhatsApp click-to-chat buttons (pre-filled message, no backend needed)
- Razorpay payment button integration point (Pro plan)
- Google Analytics tracking snippet (ready to connect)
- Fully responsive — mobile, tablet, desktop

## Tech Stack

- HTML5
- CSS3 (custom properties / CSS variables, Flexbox, Grid)
- Google Fonts (Oswald + Inter)
- No frameworks, no build step — pure static site

## Project Structure

```
wep-page/
├── index.html      # Page structure and content
├── style.css       # All styling
└── README.md        # Project documentation
```

## Setup

1. Clone or download this repository
2. Open `index.html` directly in a browser — no build step required
3. To deploy on GitHub Pages:
   - Push both `index.html` and `style.css` to the repo root
   - Go to **Settings → Pages → Source**, select the `main` branch
   - Site goes live at `https://<username>.github.io/<repo-name>/`

## Configuration

Before going live, update the following in `index.html`:

| What | Where | Replace with |
|---|---|---|
| WhatsApp number | All `wa.me/919876543210` links | Your business WhatsApp number (with country code, no `+` or spaces) |
| Google Analytics ID | `G-XXXXXXXXXX` (2 places) | Your GA4 Measurement ID |
| Razorpay button | `pl_YOUR_BUTTON_ID_HERE` | Your Razorpay Payment Button ID |
| Gym name, address, phone | Footer section | Your business details |

## Notes

- WhatsApp buttons open a pre-filled chat but require the visitor to tap "Send" — this is a WhatsApp platform restriction and cannot be bypassed by any website.
- Images are sourced from Unsplash (free to use, no attribution required).

## License

Free to use and modify for personal or client projects.
