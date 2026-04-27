# Web Development Study Index

A topic-wise roadmap for the Web Development Full Course — with phase breakdown, key concepts, and practice milestones.

---

## How to Use This Index

- Follow phases **in order** — each phase builds on the previous
- Complete the **Practice Milestones** at the end of each phase before moving on
- Use the file references to jump directly to the relevant lesson
- Revisit earlier files whenever you need a refresher

---

## Phase 1 — HTML Foundations

**Goal:** Understand how web pages are structured. Build static pages with proper semantic markup.

| Lesson | File | Key Concepts |
|--------|------|--------------|
| 01 | 01_html_basics.html | DOCTYPE, html/head/body, meta tags, headings (h1–h6), paragraphs, comments |
| 02 | 02_html_lists_links_images.html | ul, ol, li, nested lists, anchor tags (href, target), img (src, alt, width) |
| 03 | 03_html_tables.html | table, tr, th, td, colspan, rowspan, caption |
| 04 | 04_html_forms.html | form, input types (text, email, password, radio, checkbox, file), select, textarea, button, required |
| 05 | 05_html_semantic_elements.html | header, nav, main, section, article, aside, footer, figure, figcaption |

### Phase 1 — Practice Milestones
- [ ] Build a bio page with your name, photo, and a bulleted list of hobbies
- [ ] Create a table showing a school timetable or product comparison
- [ ] Build a contact form with name, email, message, and a submit button
- [ ] Recreate a simple webpage using only semantic elements (no div soup)

---

## Phase 2 — CSS Fundamentals

**Goal:** Style pages professionally. Master layout systems (Flexbox & Grid) and make designs responsive.

| Lesson | File | Key Concepts |
|--------|------|--------------|
| 06 | 06_css_selectors_and_box_model.html | element/class/ID selectors, pseudo-classes (:hover, :nth-child), box model (margin, border, padding, content), box-sizing |
| 07 | 07_css_colors_typography.html | hex/rgb/hsl colors, background-color, background-image, Google Fonts, font-family, font-size, font-weight, line-height, text-align |
| 08 | 08_css_display_position.html | display (block, inline, inline-block, none), position (static, relative, absolute, fixed, sticky), z-index, float, clear |
| 09 | 09_css_flexbox.html | display:flex, flex-direction, justify-content, align-items, flex-wrap, gap, flex-grow, flex-shrink, order |
| 10 | 10_css_grid.html | display:grid, grid-template-columns/rows, grid-gap, grid-area, auto-fit, minmax(), named areas |
| 11 | 11_css_transitions_animations.html | transition (property, duration, timing, delay), @keyframes, animation (name, duration, iteration, direction), transform (translate, rotate, scale) |
| 12 | 12_css_responsive_media_queries.html | @media, breakpoints (mobile/tablet/desktop), mobile-first vs desktop-first, viewport meta tag, relative units (%, em, rem, vw, vh) |

### Phase 2 — Practice Milestones
- [ ] Style your Phase 1 bio page — add colors, fonts, spacing
- [ ] Build a navigation bar using Flexbox
- [ ] Create a 3-column card layout using CSS Grid
- [ ] Add a hover animation to a button
- [ ] Make any page fully responsive (works on phone + desktop)

---

## Phase 3 — JavaScript Core

**Goal:** Add interactivity and logic to web pages. Understand how JavaScript powers dynamic behavior.

| Lesson | File | Key Concepts |
|--------|------|--------------|
| 13 | 13_js_basics_variables_datatypes.html | var/let/const, string, number, boolean, null, undefined, typeof, template literals |
| 14 | 14_js_operators_conditionals.html | arithmetic, comparison, logical operators, if/else, ternary operator, switch |
| 15 | 15_js_loops_and_patterns.html | for, while, do-while, break, continue, nested loops, console.log patterns |
| 16 | 16_js_functions.html | function declaration, function expression, arrow functions, parameters, return, default params, rest params |
| 17 | 17_js_arrays.html | array creation, indexing, push/pop/shift/unshift, slice, splice, map, filter, reduce, forEach, find, includes, sort |
| 18 | 18_js_objects.html | object literals, dot/bracket notation, methods, this keyword, object destructuring, spread operator, Object.keys/values/entries |
| 19 | 19_js_dom_manipulation.html | document.querySelector, getElementById, innerHTML, textContent, setAttribute, createElement, appendChild, removeChild, classList (add/remove/toggle) |
| 20 | 20_js_events.html | addEventListener, click, mouseover, keydown, input, change, submit, event object (e.target, e.preventDefault) |
| 21 | 21_js_form_validation.html | accessing form values, validation logic, showing error messages, preventing invalid submission |
| 22 | 22_js_es6_features.html | let/const, arrow functions, template literals, destructuring, spread/rest, optional chaining (?.), nullish coalescing (??), modules (import/export concept) |
| 23 | 23_js_local_storage.html | localStorage.setItem/getItem/removeItem/clear, JSON.stringify, JSON.parse, persisting data across sessions |
| 24 | 24_js_fetch_api_json.html | fetch(), .then(), .catch(), async/await, response.json(), rendering fetched data to the DOM |

### Phase 3 — Practice Milestones
- [ ] Write a function that takes a name and returns a greeting string
- [ ] Filter an array of numbers to return only even ones
- [ ] Build a counter (increment, decrement, reset) using DOM + Events
- [ ] Validate a form (check empty fields, valid email format) using JS
- [ ] Save a list of items to localStorage and reload them on page refresh

---

## Phase 4 — Projects

**Goal:** Apply everything from Phases 1–3 to build real, complete projects.

| Lesson | File | What You'll Build |
|--------|------|-------------------|
| 25 | 25_project_personal_portfolio.html | Responsive portfolio — hero, about, skills, projects, contact |
| 26 | 26_project_todo_app.html | To-do list with add, complete, delete, and localStorage save |
| 27 | 27_project_calculator.html | Calculator with all operators and keyboard support |
| 28 | 28_project_quiz_app.html | Multiple choice quiz with timer, scoring, and result screen |
| 29 | 29_project_weather_ui.html | Weather card UI rendering JSON data via Fetch API |
| 30 | 30_project_responsive_landing_page.html | Mobile-first landing page for a product or service |

### Phase 4 — Practice Milestones
- [ ] Deploy your portfolio online (GitHub Pages — free and simple)
- [ ] Add a dark mode toggle to one of your projects
- [ ] Extend the To-Do app with due dates and priority tags
- [ ] Modify the quiz app to load questions from an external JSON file
- [ ] Build one completely original project using HTML + CSS + JS

---

## Quick Reference — Key Concepts at a Glance

### HTML Must-Knows
- Always include `<!DOCTYPE html>` and viewport meta tag
- Use semantic tags — avoid using `<div>` for everything
- `alt` attribute on all images (accessibility + SEO)
- Form inputs need `name` and `id` attributes

### CSS Must-Knows
- `box-sizing: border-box` on everything (use `* { box-sizing: border-box; }`)
- Prefer Flexbox for 1D layouts, Grid for 2D layouts
- Use `rem` for font sizes, `%` or `vw/vh` for containers
- Mobile-first: write base styles for mobile, use `@media (min-width: ...)` to scale up

### JavaScript Must-Knows
- Always use `const` by default; use `let` only when the value changes; avoid `var`
- Use `===` (strict equality), never `==`
- `addEventListener` over inline `onclick` attributes
- `JSON.stringify()` before saving to localStorage; `JSON.parse()` when reading back
- `e.preventDefault()` to stop default form submission behavior

---

## Recommended Tools

| Tool | Purpose |
|------|---------|
| VS Code | Code editor |
| Live Server (VS Code extension) | Auto-reload browser on save |
| Chrome DevTools | Inspect, debug, test responsive layouts |
| Google Fonts | Free web fonts |
| Can I Use (caniuse.com) | Check browser support for CSS/JS features |
| GitHub Pages | Free hosting for static HTML/CSS/JS sites |

---

## Study Tips

- **Code every example yourself** — don't copy-paste. Typing builds muscle memory.
- **Break things on purpose** — modify code to see what changes and what breaks.
- **Use DevTools constantly** — Elements panel for HTML/CSS, Console for JavaScript.
- **Build something every week** — even a tiny project reinforces learning.
- **Read error messages** — they tell you exactly what went wrong and where.

---

*For the complete file listing and course overview, see* 👉 [README.md](./README.md)
