# Workshop Registration Page

A single-page registration website for a free weekend HTML & CSS workshop, built with **pure HTML and CSS**: no JavaScript, no frameworks.

The main goal of this project was to practice **CSS attribute selectors** on a realistic page with a workshop list, a registration form and a resources section.

## Features

- Workshop list with schedule and difficulty-level colors
- Registration form with required fields, a disabled field, a dropdown, a date picker and a checkbox
- Resource and contact links styled according to their `href` value
- Downloadable workshop schedule (PDF)
- Hover and focus effects on buttons, inputs and links
- Clean, centered card layout

## Attribute Selectors Used

| Selector | What it does |
|---|---|
| `[title]` | Adds a dashed underline and a help cursor to elements that have a tooltip |
| `input[required]`, `select[required]` | Marks required fields with a red left border |
| `[type="submit"]`, `[type="reset"]` | Gives the form buttons different colors |
| `[type="checkbox"]` | Styles the checkbox separately from the other inputs |
| `a[href$=".pdf"]` | Selects links that **end with** `.pdf` |
| `a[href^="https"]` | Selects links that **start with** `https` (external links) |
| `a[href^="mailto"]` | Selects email links |
| `a[href^="tel:"]` | Selects phone links |
| `a[href*="#"]` | Selects links that **contain** `#` |

## Other CSS Topics Practiced

- Box model: `padding`, `margin`, `border`, `border-radius`
- `max-width` and `margin: auto` for centering
- `float` for aligning the workshop times
- `opacity`, `box-shadow` and `letter-spacing`
- Pseudo-classes: `:hover`, `:focus`, `:first-child`, `:nth-child()`, `:last-child`
- Font Awesome icons

## Project Structure

```
├── index.html
├── style.css
└── pdf/
    └── atolye-programi.pdf
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yusif9999/css-attribute-selectors-practice.git
   ```
2. Open `index.html` in your browser.

## Built With

- HTML5
- CSS3
- [Font Awesome](https://fontawesome.com/)
