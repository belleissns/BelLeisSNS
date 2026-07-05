# Bel Lei's Lye, Dye, and DIY Soap Calculator

A responsive, GitHub Pages-ready static website for a beautiful handmade soap calculator.

## What is included

- `index.html` — website/app page
- `styles.css` — responsive purple, gold, silver, floral/apothecary styling
- `app.js` — calculator logic, local saved recipes, print behavior
- `assets/` — SVG graphics, floral accents, favicon, dividers, paper texture
- `manifest.webmanifest` and `service-worker.js` — starter PWA support

## Current features

- Bar soap NaOH calculator
- Grams and ounces
- Superfat percentage
- Water:lye ratio
- Lye concentration
- Water as percentage of oils
- Fragrance load calculator
- Starter oils library with editable SAP values
- Add/remove oil rows
- Balance oils by percentage
- Recipe preview
- Print recipe sheet
- Save up to 3 recipes locally on the device
- Free / Pro / Studio tier preview
- Mobile, tablet, and desktop responsive layout

## Important safety note

This calculator uses standard NaOH SAP math. SAP values can vary by supplier and oil composition. Always verify recipes before making soap, wear proper PPE, and follow safe lye-handling practices.

## How to use with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder into the root of the repository. The `index.html` file should be at the top/root level.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root` folder.
6. Save. GitHub will give you a live Pages link.

## Recommended next build steps

1. Add a mold size calculator.
2. Add recipe scaling.
3. Add custom saved oil library.
4. Add prettier PDF export.
5. Add cost-per-batch and cost-per-bar tools.
6. Later: user accounts, cloud recipe vault, and Stripe subscriptions.
