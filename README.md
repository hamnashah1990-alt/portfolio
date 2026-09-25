# Hamna Shah — Personal Portfolio

A multi-page personal portfolio website built with plain HTML5 and an external CSS3
stylesheet, created for **CS313: Web Engineering — Lab 3 (HTML Advanced: Personal
Portfolio II)**.

## Live Site

🔗 **GitHub Pages:** https://github.com/hamnashah1990-alt/portfolio

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Landing page with hero banner, a float/clear "About Me" section, education timeline, and awards |
| Hobbies | `hobbies.html` | Hobbies grid and spoken-language proficiency bars |
| Skills | `skills.html` | Programming languages, DS/ML tools, and soft skills |
| Image Gallery | `gallery.html` | Photo gallery of 5 images arranged with CSS `float` and `clear` |
| Contact Me | `contact.html` | Contact card with email, phone, location, and LinkedIn |

## Project Structure

```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   └── photo5.jpg
└── README.md
```

## Features

- Fully **external stylesheet** (`css/style.css`) — no inline or embedded CSS.
- Horizontal **navigation menu** built with CSS `float`, consistent across all pages.
- An **About Me** section on the home page using `float` to place the photo beside
  the text, with a `clear` fix so later sections are not affected by the float.
- A **5-image gallery** laid out with `float` and cleared with a clearfix rule.
- Consistent fonts, colors, spacing, and card/panel styling across every page.
- Fully responsive — the gallery and about-section float layouts collapse to a
  single column on small screens via a media query.
- No JavaScript and no CSS frameworks — plain HTML and CSS only.

## Tech Stack

- HTML5
- CSS3 (Flexbox for card grids, Float/Clear for the nav, about section, and gallery)

## Author

**Hamna Shah** — BS Data Science, NUST, Islamabad
