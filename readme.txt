# SignEase — Sign Language Learning Website

## 📖 Project Overview
This project was developed as **Assignment 01 — HTML & CSS**.  
The goal was to build a **multi-page, accessible, and responsive website** using semantic HTML5 and modern CSS3.  
The website has three pages:
- `index.html` — Homepage
- `about.html` — Project information
- `contact.html` — Contact form  

It provides resources for learning sign language, promotes accessibility, and includes interactive features like quizzes, videos, forms, and responsive layouts.

---

## 🚀 Features Implemented
### General
- Semantic HTML5 structure (`header`, `nav`, `main`, `section`, `article`, `footer`).
- Shared **header and footer** across all pages with consistent navigation.
- Responsive layout using **CSS Grid** and **Flexbox**.
- Dark mode support using **CSS variables** + `@media (prefers-color-scheme: dark)`.
- **Bootstrap (via CDN)** integrated for optional components.

### Index Page (`index.html`)
- `<h1>` heading for page title.
- Paragraph with `<strong>` and `<em>`.
- Three types of lists:
  - `<ul>` Unordered list  
  - `<ol>` Ordered list  
  - `<dl>` Description list
- **Responsive image** using `<picture>` + `<figcaption>`.
- **Table** with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`.
- **Video** element with `<track>` captions.
- External link, mailto link, and a **downloadable PDF** link.
- Call-to-action hero section.

### About Page (`about.html`)
- Structured with `<article>` and `<section>`.
- Example of **block element** (`<div>`) and **inline element** (`<span>`).
- CSS specificity demo (class selector overriding general selector).
- **Styled button** with hover animation.
- **Collapsible content** using `<details>/<summary>`.

### Contact Page (`contact.html`)
- Accessible **form** with:
  - Inputs: text, email, url, date, color, range, checkbox.
  - Proper `<label for="">` associations.
  - Built-in HTML5 validation.
  - Submit and reset buttons.
- **Download link** for brochure (PDF).

### Media & Gallery
- Responsive image **gallery (6+)** built with CSS Grid.
- Images optimized with `loading="lazy"`.
- Video/audio integrated.

---

## ♿ Accessibility Improvements
- **Alt text** for all images.
- Decorative images use `alt=""`.
- **ARIA roles**:
  - `role="navigation"`
  - `role="main"`
  - `role="contentinfo"`
- Keyboard-accessible navigation (focus states included).
- Color contrast checked for **WCAG 2.1 AA** compliance.
- `<address>` tag used for contact info in footer.

---

## 🔍 SEO & Performance Enhancements
- `<meta name="description">` added for all pages.
- **Open Graph tags**:
  - `og:title`, `og:description`, `og:image`.
- **Print-friendly stylesheet** using `@media print`.
- Files organized into `assets/css/`, `assets/images/`, `assets/media/`.

---

## 📊 Lighthouse Audit
### Before Fixes
- Accessibility: ~65  
- SEO: ~70  
- Best Practices: ~75  
- Performance: ~68  

### After Fixes
- Accessibility: **≥ 90**  
- SEO: **≥ 90**  
- Best Practices: **≥ 90**  
- Performance: **≥ 85**  

Screenshots of the Lighthouse reports are included in the `/assets/media/` folder.

- 

---

## 📌 Extras Implemented
- **Dialog box (`<dialog>`)** with open/close buttons using JavaScript.
- **Bootstrap integration** for styling cards and navigation bar.
- **Transitions & animations** for hover effects and buttons.
