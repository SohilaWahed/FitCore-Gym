# FitCore Gym — Landing Page

A responsive gym landing page built with pure HTML and CSS — no frameworks, no JavaScript.

---

## Project Structure

```
fitcore-gym/
├── index.html
├── css/
│   ├── style.css      # Main styles & CSS variables
│   └── media.css      # Responsive breakpoints
└── images/
    ├── hero-section-img.png
    ├── why-choose-us.png
    ├── avatar-1.jpg
    ├── avatar-2.jpg
    └── avatar-3.jpg
```

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Headline, intro text, and CTA buttons |
| **Why Choose Us** | 3 feature cards + detailed features list |
| **Our Members** | Testimonials cards + statistics bar |
| **Join Form** | Membership registration form |
| **Footer** | Links, contact info, and social media |

---

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox)
- Google Fonts — Roboto (400, 500, 700)

---

## Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 992px` | Desktop — two-column layouts |
| `≤ 992px` | Tablet — single column, stacked sections |
| `≤ 768px` | Mobile — reduced padding and font sizes |

---

## CSS Variables (`:root`)

```css
--font-family-base
--font-weight-regular: 400
--font-weight-medium: 500
--font-weight-bold: 700
--padding-block: 40px
--padding-block-md: 60px
--padding-block-lg: 80px
--dark-background-color: #101828
--secondary-background-color: #F9FAFB
--main--text-color: #101828
--secondary--text-color: #4a5565
--third-text-color: #364153
--footer-text-color: #99a1af
```

---

## How to Run

No build tools needed. Open `index.html` directly in any browser.

```bash
# Clone the repo
git clone https://github.com/your-username/fitcore-gym.git
cd fitcore-gym

# Open in browser
open index.html
```

Or use the **VS Code Live Server** extension — right-click `index.html` → Open with Live Server.

---

## Author

FitCore Gym Project — 2025
