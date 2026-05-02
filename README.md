# AutoStyle Car Decor — Static Website

A clean, modern, multi-page static website for **AutoStyle**, a premium car decor company. Built with pure HTML and CSS — no frameworks, no JavaScript.

---

## 📄 Pages

| File            | Description                                      |
|-----------------|--------------------------------------------------|
| `index.html`    | Homepage — Hero, Services overview, CTA          |
| `about.html`    | About page — Company story, Mission/Vision, Why Choose Us |
| `contact.html`  | Contact page — Enquiry form, Contact details     |
| `styles.css`    | Shared stylesheet for all pages                  |

---

## 🛠 Technologies Used

- **HTML5** — Semantic markup (`header`, `main`, `section`, `footer`, `nav`)
- **CSS3** — Custom properties (variables), Grid, Flexbox, responsive media queries
- No JavaScript, no external frameworks, no build tools required

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/autostyle-website.git
   cd autostyle-website
   ```

2. **Open in browser:**
   Simply open `index.html` in any modern web browser. No server setup needed.

3. **Or use a local server (recommended for development):**
   ```bash
   # Using Python
   python -m http.server 8000

   # Using VS Code
   Install the "Live Server" extension and click "Go Live"
   ```

---

## 📁 Project Structure

```
autostyle-website/
├── index.html       # Homepage
├── about.html       # About page
├── contact.html     # Contact page
├── styles.css       # Global stylesheet
└── README.md        # Project documentation
```

---

## 🎨 Design System

The site uses a **premium dark automotive** theme defined via CSS variables in `styles.css`:

| Variable               | Value       | Usage                        |
|------------------------|-------------|------------------------------|
| `--color-bg`           | `#0d0d0d`   | Main background              |
| `--color-accent`       | `#e8a020`   | Highlight, buttons, icons    |
| `--color-text-primary` | `#f0f0f0`   | Headings and key text        |
| `--color-text-secondary`| `#a0a0a0`  | Body and description text    |
| `--font-display`       | Georgia     | Headings                     |
| `--font-body`          | Trebuchet MS| Body text, labels            |

To change the colour theme, only update these variables at the top of `styles.css`.

---

## 🤝 Contributing (Team Guidelines)

This is a collaborative project. Please follow these conventions:

- **HTML developers:** Use semantic tags and existing class names only. Do not add `style=""` inline styles.
- **CSS developers:** Add new styles only in `styles.css`. Use existing CSS variables for all colours and spacing.
- **Class naming:** Use `kebab-case` (e.g., `service-card`, `hero-title`)
- **Commits:** Write clear, descriptive commit messages (e.g., `fix: navbar active state on about page`)
- **Branches:** Create a feature branch for each change (`feature/add-gallery-section`)

---

## 📱 Responsive Breakpoints

| Breakpoint  | Width       | Layout Changes                        |
|-------------|-------------|---------------------------------------|
| Desktop     | > 900px     | Full multi-column layouts             |
| Tablet      | ≤ 900px     | Single-column for About, Contact      |
| Mobile      | ≤ 600px     | Stacked layouts, full-width buttons   |

---

## 📬 Contact

For project queries, reach out via the contact form on `contact.html` or email **hello@autostyle.in**.

---

&copy; 2026 AutoStyle Car Decor. All rights reserved.
