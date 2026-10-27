# AURORE Atelier — Future-Ready Fashion

A luxury-inspired fashion storefront concept focused on premium bags, editorial imagery, and a refined shopping experience.

## Overview

**AURORE Atelier** is a responsive, single-page e-commerce storefront concept for a premium fashion and accessories brand. It combines editorial-style layouts, warm neutral colors, elegant typography, product discovery, and lightweight JavaScript interactions.

> **Project status:** Front-end demo. Checkout, newsletter subscription, and referral actions are mock interactions; they do not process real payments or send real emails.

## Features

- **Luxury editorial design** with a warm sand, cream, charcoal, and burgundy palette.
- **Responsive layout** for desktop, tablet, and mobile screens.
- **Product collections** featuring bestsellers and everyday styles.
- **Product interactions** including quick view, color swatches, and quick-add buttons.
- **Shopping bag drawer** with item-count and shipping-progress UI.
- **Wishlist controls** with a wishlist counter.
- **Search and mobile navigation** interface.
- **Editorial and community sections**, including a lookbook-style banner and social gallery.
- **Referral and newsletter forms** with demo feedback messages.
- **Privacy, terms, and customer-service links** in the footer UI.

## Built With

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript
- Google Fonts: Cormorant Garamond and Plus Jakarta Sans
- Phosphor Icons
- Unsplash-hosted image assets

## Getting Started

This project is built as a standalone HTML page and does not require a package installation or build step.

### Run locally

1. Download or clone this repository.
2. Make sure the main HTML file is named `index.html`.
3. Open `index.html` in a modern browser.

For a local development server, you can use the **Live Server** extension in Visual Studio Code, then choose **Open with Live Server** on `index.html`.

## Deploy to GitHub Pages

1. Create a repository on GitHub.
2. Upload `index.html` and this `README.md` to the repository's root directory.
3. In the repository, open **Settings → Pages**.
4. Under the build and deployment settings, select **Deploy from a branch**.
5. Choose your main branch and the `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site and open the URL shown in the Pages settings.

If the project uses a different HTML filename, rename it to `index.html` so GitHub Pages can load it as the default page.

## Important Notes

- An internet connection is required for CDN-hosted Tailwind CSS, Google Fonts, Phosphor Icons, and remote Unsplash images.
- The checkout is a **mock/demo flow**. Connect a secure payment provider and a server-side order system before accepting real orders.
- Newsletter and referral form feedback is currently front-end only; no messages are sent or stored.
- Product names, prices, reviews, delivery promises, certifications, and brand claims shown in the demo are sample storefront content. Verify and replace them before using the site commercially.
- The footer includes policy links as interface elements. Publish complete, accurate Privacy Policy, Terms of Service, and Cookie Policy pages before launching a real store.
- Do not collect customer information until the required privacy disclosures, security controls, and data-handling processes are in place.

## Customization

You can customize the site by editing `index.html`:

- **Branding:** update the AURORE name, logo, and copy.
- **Colors and typography:** adjust the Tailwind configuration and CSS variables/styles near the top of the file.
- **Products:** edit product titles, descriptions, prices, images, and color options.
- **Images:** replace the Unsplash image URLs with assets you have permission to use.
- **Interactions:** update the JavaScript functions near the bottom of the file.
- **Policies and contact details:** add real business information and link each footer item to its corresponding page.

## License

No license is specified for this project. Add a `LICENSE` file if you intend to publish the code for reuse. Check the license and usage terms of all external fonts, icon libraries, and images before redistributing them.

---

Made as a front-end storefront concept for AURORE Atelier.
