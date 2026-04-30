# Jasmine Butterfield — Portfolio v3

A personal portfolio website built with plain HTML and CSS. No frameworks or build tools required — open any page directly in a browser.

## Pages

| File | Title |
|---|---|
| `index.html` | Home / Hero |
| `projects.html` | Work (project gallery) |
| `experience.html` | Professional Experience |
| `education.html` | Education & Awards |
| `skills.html` | Skills & Expertise |

## Design

- **Color scheme:** Black background with white text and cyan neon glow (`text-shadow`)
- **Layout:** Fixed left sidebar navigation + main content area
- **Typography:** [Inter](https://fonts.google.com/specimen/Inter) (body) and [Gloock](https://fonts.google.com/specimen/Gloock) (display/headings) via Google Fonts
- **Assets:** Images and PDFs stored in `img/`

## Usage

No installation needed. Open `index.html` in any modern browser, or serve locally:

```bash
cd portfolio_v3
python3 -m http.server 8080
# then visit http://localhost:8080
```

## File Structure

```
portfolio_v3/
├── index.html
├── projects.html
├── experience.html
├── education.html
├── skills.html
└── img/
    ├── logo.jpg
    ├── restored.jpg
    └── ...
```
