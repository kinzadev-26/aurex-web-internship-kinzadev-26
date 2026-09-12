# AUREX Full-Stack Engineering Internship

## Week 1 — Frontend Foundation

**Intern:** Kinza Imtiaz
**Domain:** Full-Stack Web Development

### Task Description
Built a personal profile / developer introduction webpage (`index.html`) using pure HTML5 — no CSS styling, per Week 1 requirements. The page includes Header, Navigation, About Me, Skills, Education, Experience, Projects, Blog, Contact Form, and Footer sections, all structured with semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) and accessibility basics (`alt` attributes on images, `<label>` on all form inputs).

### Technologies Used
- HTML5
- Git
- GitHub

### How to Run Locally
1. Clone the repository:
   ```
   git clone https://github.com/kinzadev-26/aurex-web-internship-kinzadev-26.git
   ```
2. Navigate into the project folder:
   ```
   cd aurex-web-internship-kinzadev-26
   ```
3. Open `index.html` directly in any browser (double-click the file, or right-click → Open with → Chrome/Edge).

## Week 2 — CSS Styling, Layout & Responsive Design

**Intern:** Kinza Imtiaz
**Domain:** Full-Stack Web Development

### Live Deployment
🔗 https://aurex-web-internship-kinzadev-26.vercel.app

### Task Description
Took the Week 1 HTML structure and transformed it into a fully responsive, styled multi-page portfolio using custom CSS. The homepage now works like a dashboard(About, Skills, Education, Experience, Projects, Contact) that each link to their own dedicated page with full details.

### Folder Structure
```
aurex-web-internship-kinzadev-26/
├── index.html
├── about.html
├── skills.html
├── education.html
├── experience.html
├── projects.html
├── contact.html
├── style.css
├── images/
│   └── hero-image.jpeg
│   └── about.jpeg
│   └── contact.jpeg
└── README.md
```

### Technologies Used
- HTML5, CSS3
- Google Fonts (Quicksand, Poppins, Caveat)
- Font Awesome 6 (icons)
- Git, GitHub
- Vercel (deployment)

### CSS Features & Layout Techniques Implemented
- **Flexbox** — header/navigation bar, hero content alignment, button groups, and the icon + text + arrow layout inside each card
- **CSS Grid** — homepage summary-card dashboard (column count changes per breakpoint), project cards, and the tech-stack icon grid on the Skills page
- **CSS Custom Properties** — colors, spacing scale, and border-radius values centralized in `:root` for consistency
- **Mobile-first responsive design** — base styles target mobile first, then enhanced using `min-width` media queries
- **Box model** — consistent padding/margin scale, borders, and rounded corners throughout
- `position: sticky` for the header, `position: fixed` for the desktop sidebar of social icons
- A Flexbox-based sticky-footer pattern (on `body`/`main`) so the footer sits correctly regardless of page content height

### Responsive Breakpoints
| Breakpoint | Width | Layout |
|---|---|---|
| Mobile | default (below 768px) | Single column, stacked hero image and text |
| Tablet | 768px and up | 3-column card grid, hero text and image side by side |
| Laptop / Desktop | 1024px and up | 6-column card grid (one row), fixed sidebar, wider spacing |

### Key Learnings

Writing mobile-first meant starting with simple, stacked styles and adding complexity only as the screen got
wider, rather than the other way around. I also learned that testing responsive design properly means
checking on real devices (phone, tablet, laptop) and not just resizing a desktop browser window.


### Difficulties Faced During Responsive Design
Getting the homepage cards to behave consistently across every screen size took several rounds of iteration. I also ran into the fixed sidebar (social icons) overlapping page content.