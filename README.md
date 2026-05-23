# Wix Car Rentals Uganda 🚗 Preepared by JohnIsaac

> Uganda's trusted car rental agency — self-drive and guided tours from Kampala.  
> Live website built with pure HTML, CSS, and JavaScript. No frameworks. No dependencies to install.

---

## 🌍 Live Site

Hosted on GitHub Pages:  
**`https://johnisaacKIZZA.github.io/wix-car-rentals`**

---

## 📁 Project Structure

```
wix-car-rentals/
├── index.html          ← Entire website (HTML + CSS + JS in one file)
├── README.md           ← You are here
└── assets/             ← Local images (hero background, car photos, etc.)
    └── world-dotted-map.png
```

---

## ✨ Features

- **Transparent sticky navbar** — clear over the hero, turns solid white on scroll
- **Hero section** with quick reservation form (desktop)
- **Fleet section** with 6 vehicle classes and live filter tabs (All / Premium / SUV / Pickup / Sedan)
- **Booking form** with live cost summary — calculates days, rate, driver fee, and total automatically
- **EmailJS integration** — booking confirmations sent directly to `kizzajohnisaac@gmail.com` with no backend or server required
- **Services, How It Works, Testimonials, About, Travel Tips, Contact** sections
- **Embedded Google Map** of the Akamwesi Complex office
- **Floating WhatsApp button** for instant customer contact
- **Fully responsive** — works on mobile, tablet, and desktop
- **Scroll reveal animations** on all sections

---

## 🚗 Fleet & Pricing

| Vehicle | Class | Price |
|---|---|---|
| Toyota Prado | Premium | $145/day |
| Toyota Hilux | Pickup | $120/day |
| Hyundai Santa Fe | SUV | $100/day |
| Hyundai Tucson | Crossover | $85/day |
| Hyundai Sonata | Large | $55/day |
| Hyundai Elantra | Medium | $50/day |

Optional driver add-on: **+$30/day**

---

## 📧 Email Setup (EmailJS)

Booking confirmations are sent via [EmailJS](https://emailjs.com) — no server needed.

### Template variables

```
{{first_name}}     — Customer first name
{{last_name}}      — Customer last name
{{email}}          — Customer email
{{phone}}          — Customer phone number
{{vehicle}}        — Selected vehicle
{{rate}}           — Daily rate (e.g. $145/day)
{{pickup}}         — Pick-up date
{{dropoff}}        — Drop-off date
{{location}}       — Pick-up location
{{driver}}         — Driver included (Yes/No)
{{days}}           — Number of rental days
{{total}}          — Estimated total cost
```




---

## 🎨 Colour Scheme

| Variable | Colour | Usage |
|---|---|---|
| `--ink` | `#0e1d34` | Dark navy — backgrounds |
| `--red` | `#c0392b` | Primary accent — buttons, badges |
| `--gold2` | `#e0a83a` | Gold — hero stats, highlights |
| `--white` | `#ffffff` | White |
| `--off` | `#f5f3ef` | Off-white — section backgrounds |

---


---

## 🛠 Built With

- HTML5 & CSS3
- Vanilla JavaScript (no frameworks)
- [EmailJS](https://emailjs.com) — client-side email sending
- [Tabler Icons](https://tabler-icons.io) — icon set
- [Google Fonts](https://fonts.google.com) — Poppins + Outfit
- [Unsplash](https://unsplash.com) — stock photography

---

*© 2026 Wix Car Rentals Uganda Ltd. All rights reserved.* Developed by JohnIsaac Lutwama KIZZA
