# Home Theater Cost Estimator Widget

A premium, single-file React widget for estimating home theater costs.

## Features
- **Real-time Cost Estimation**: Instantly updates based on Room Size, Video Tier, and Audio Tier.
- **Lead Capture**: Gates the detailed breakdown behind a name/phone form.
- **Cinematic Design**: Dark mode with gold accents and glassmorphism effects.
- **Single File**: All code (HTML, CSS, JS) is contained in `index.html`.

## Quick Start
1. **Download**: Save the `index.html` file.
2. **Run**: Open the file directly in any modern web browser (Chrome, Edge, Safari). No server required.

## Integration
To embed this in an existing website:
1. Copy the `<script>` tags from the `<head>` (React, Tailwind, Babel).
2. Copy the `styles` and `tailwind.config`.
3. Copy the `<div id="root"></div>` where you want the widget to appear.
4. Copy the `<script type="text/babel">` block containing the React code at the end of your `<body>`.

## Customization
- **Pricing**: Edit the `PRICING` constant object in the script to change base costs.
- **Colors**: Modify the `tailwind.config` script in the `<head>` to change the color palette.
