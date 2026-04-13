# Enterprise Solutions — Official Website

A luxurious, high-converting static website for **Enterprise Solutions**, a solar energy and engineering company based in Eredo, Epe, Lagos, Nigeria.

---

## Live Preview

Open `index.html` directly in any modern browser — no build tools or server required.

---

## Project Structure

```
├── index.html        # Main HTML file
├── style.css         # All styles and responsive layout
├── script.js         # Animations, lightbox, form, and interactions
├── logo.jpg          # Company logo (used in navbar and footer)
├── sale 1-6          # Product images (jpg/png)
├── work 1-8.jpg      # Project gallery images
└── README.md
```

---

## Sections

| Section | Description |
|---|---|
| Navbar | Fixed, scroll-aware with glass blur effect. Logo left, hamburger right on mobile |
| Hero | Full-screen solar image with animated headline "Let the Sun Pay Your Bills" |
| Ticker | Auto-scrolling services banner |
| About | Company intro with animated stat counters |
| Services | 7 service cards with hover animations |
| Why Us | Benefits checklist + 4 feature cards |
| Products | 6 product cards with ₦0 placeholder prices |
| Gallery | 8-image grid with lightbox on click |
| CTA Banner | Bold call-to-action strip |
| Contact | Address, phone, WhatsApp, map embed, and enquiry form |
| Footer | Full links, social icons, and company info |

---

## Customisation

### Updating Product Prices
In `index.html`, find each product card and replace `₦0` with the real price:
```html
<span class="price">₦150,000</span>
```

### Updating Product Names
Each product card has a placeholder name like `Solar Product 1`. Replace with the actual product name:
```html
<h4>200W Monocrystalline Solar Panel</h4>
```

### Social Media Links
In the footer, update the `href` values on the social icons:
```html
<a href="https://facebook.com/yourpage"><i class="fa-brands fa-facebook-f"></i></a>
```

---

## Tech Stack

- HTML5
- CSS3 (custom, no framework)
- Vanilla JavaScript
- [Google Fonts](https://fonts.google.com) — Montserrat + Open Sans
- [Font Awesome 6](https://fontawesome.com) — icons
- [Unsplash](https://unsplash.com) — hero background image

---

## Business Info

| | |
|---|---|
| Company | Enterprise Solutions |
| Location | Beside Kboom Filling Station, Eredo LCDA, Epe 100120, Lagos |
| Phone | 0913 558 0443 |
| Hours | Open 24 Hours |

---

## Services Offered

- Solar Engineering
- Electrical Engineering
- Plumbing
- Property Development
- Real Estate Management
- Safety Executive
- Solar Installation
