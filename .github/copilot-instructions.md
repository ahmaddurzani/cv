# Copilot Instructions for CV-AHMAD-DURZANI

## Project Overview
This is a static personal CV website for Ahmad Durzani, built with plain HTML and CSS. No JavaScript, frameworks, or build tools are used.

## Key Patterns and Conventions

### Language and Content
- All user-facing content is in Indonesian (Bahasa Indonesia)
- Maintain language consistency in any new sections or updates
- Example: Section headings like "Tentang Saya", "Pengalaman Kerja", "Keahlian"

### HTML Structure
- Use semantic HTML with `<header>`, `<main>`, `<section>` elements
- Sidebar contains profile image, name, tagline, contact info, and social links
- Main content organized in sections with `<h2>` headings
- Experience entries use `<div class="card">` with title, date span, and description
- Skills displayed in `<div class="skills-grid">` with individual `<div class="skill-item">`

### CSS Styling Patterns
- Reset with `* { margin: 0; padding: 0; box-sizing: border-box; }`
- Body uses full-height flex centering with gradient background: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Container is flex layout: sidebar (35% width) and main-content (65% width)
- Accent color: `#764ba2` used for borders, backgrounds, and headings
- Cards have left border and light background: `background: #f9f9f9; border-left: 3px solid #764ba2;`
- Skills grid: `grid-template-columns: repeat(2, 1fr);`
- Responsive: At `max-width: 768px`, switch to column layout

### File Organization
- `index.html`: Main structure and content
- `style.css`: All styling, including responsive design
- `profilpoto.jpeg`: Profile image (referenced in HTML)

### Development Workflow
- Edit HTML directly for content changes
- Modify `style.css` for styling updates
- No build process required - open `index.html` in browser to preview
- Ensure responsive design works on mobile devices

## Key Files to Reference
- [index.html](index.html) - Complete HTML structure example
- [style.css](style.css) - CSS patterns and responsive design</content>
<parameter name="filePath">d:\CV-AHMAD-DURZANI\.github\copilot-instructions.md