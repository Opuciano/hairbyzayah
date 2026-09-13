# Hair by Zayah Beauty Hub

> Luxury hair salon & beauty hub website — Rivers State, Nigeria.

A premium, mobile-responsive single-page website for **Hair by Zayah Beauty Hub**, a registered Nigerian luxury hair salon offering hair styling, braiding, wigging, hair installation, wig revamp, and hair sales. Built with a black, royal violet, and metallic gold visual identity.

## Table of Contents

- [Background](#background)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Install](#install)
- [Usage](#usage)
- [Configuration](#configuration)
- [Project Status](#project-status)
- [Contributing](#contributing)
- [License](#license)

## Background

This repository contains the marketing website for Hair by Zayah Beauty Hub, designed to showcase the salon's services and hair collection, build trust with prospective clients, and drive appointment bookings and WhatsApp enquiries for a Nigerian audience.

## Features

- Full-screen hero section with primary calls to action
- About, Services, Hair Collection/Shop, and "Why Zayah" sections
- Filterable image gallery (masonry layout)
- Client testimonials section
- Appointment booking form that generates a pre-filled WhatsApp message on submit
- Floating WhatsApp button with pre-filled enquiry message
- Contact section with placeholder map embed
- SEO metadata, Open Graph tags, and local business structured data
- Fully responsive layout (mobile, tablet, desktop) with a mobile hamburger menu
- Accessible focus states and support for reduced-motion preferences

## Tech Stack

- HTML5
- CSS3 (custom properties, no framework)
- Vanilla JavaScript (no build step, no dependencies)
- [Google Fonts](https://fonts.google.com/) — Cormorant Garamond & Inter

## Install

No build tools or dependencies are required.

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

## Usage

Open `index.html` directly in a browser, or serve it locally:

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000` (or the port shown in your terminal).

## Configuration

Before deploying, update the following placeholders in `index.html`:

| Item | Location |
|---|---|
| WhatsApp number | `WHATSAPP_NUMBER` constant in the `<script>` block |
| Phone, email, address, business hours | Contact and Footer sections |
| Instagram, Facebook, TikTok handles | Social and Footer sections |
| Product prices | Hair Collection section |
| Google Maps embed | Contact section |
| Client testimonials | Testimonials section (currently placeholder copy) |
| Photography | Hero, About, and Gallery sections (currently gold line-art placeholders) |

## Project Status

🚧 Work in progress. Content, imagery, and business details are still being finalized.

## Contributing

This is a private, commercial project for Hair by Zayah Beauty Hub and is not currently open to outside contributions.

## License

**All rights reserved.**

This project and its source code are proprietary. No license is granted to any person or entity to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of this code, in whole or in part, for any purpose, without the express prior written permission of the copyright holder.

© 2026 Hair by Zayah Beauty Hub. All Rights Reserved.
