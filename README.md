---

## 📄 Project Reflection Report

### 🧩 Project Development Process

1. **Planning & Setup** — Created project folder with 3 HTML files, 1 shared CSS file, and a JS file.  
2. **Design System First** — Defined CSS custom properties for colors, fonts (Fraunces + DM Sans), spacing, and shadows before layout.  
3. **Shared Components** — Built sticky navbar and footer first and reused across all pages.  
4. **Home Page (index.html)** — Developed hero section, animated backgrounds, logo ticker, feature cards, sign-up modal, and footer.  
5. **About & Services Page (about.html)** — Implemented hero, stats, team cards, services section, and pricing cards.  
6. **Contact Page (contact.html)** — Built two-column layout, form validation, success animation, contact panel, FAQ accordion, and modal.  
7. **Scroll Animations** — Used IntersectionObserver for reveal animations without external libraries.  
8. **Testing & Bug Fixes** — Fixed layout, navbar conflicts, and alignment issues across devices.  
9. **Deployment** — Used relative paths and deployed via GitHub Pages.

---

### 📌 Project Overview

**Lumora** is a fictional AI-powered SaaS product website designed to help teams automate workflows, analyze data, and collaborate securely.

- Built as a **fully responsive multi-page website**
- Uses **Bootstrap 5 + custom design system**
- Consistent UI using CSS variables
- Typography: Fraunces (headings) + DM Sans (body)
- Includes animations, modals, and modern UI design

---

### 📄 Pages Included

**Home Page (index.html)**  
- Hero section with animated visuals  
- Feature cards and logo ticker  
- Modal-based sign-up  
- Footer with social icons  

**About & Services Page (about.html)**  
- Company overview and stats  
- Team section  
- Services breakdown  
- Pricing plans  

**Contact Page (contact.html)**  
- Contact form with validation  
- Contact info panel (email, phone, office, live chat)  
- FAQ accordion  
- Demo booking modal  

---

### ⚙️ Bootstrap Usage

- Navbar + Collapse (responsive navigation)  
- Grid system (layout structure)  
- Modals (signup/demo)  
- Utility classes (spacing, alignment)  
- Forms (inputs, select, textarea)  
- Responsive breakpoints  

---

### 🛠 Tools & References

- Bootstrap 5 Documentation  
- Bootstrap Icons CDN  
- Google Fonts  
- GitHub Pages (deployment)  
- AI tools (ChatGPT / Claude) used for debugging CSS issues and improving layout alignment (used responsibly, not for full code generation)

---

### ⚠️ Challenges & Solutions

**Contact Page Alignment Issue**  
- Problem: Misaligned icon-text layout  
- Solution: Used flexbox with fixed-width icon container  

**Glassmorphism Compatibility**  
- Problem: `backdrop-filter` not working everywhere  
- Solution: Added fallback background + vendor prefix  

**Form Validation**  
- Problem: No external library  
- Solution: Built custom validation using JavaScript  

**Navbar Conflict**  
- Problem: CSS overriding Bootstrap styles  
- Solution: Fixed selector specificity  

**Deployment Issues**  
- Problem: Broken links  
- Solution: Used relative paths  

---

### 📈 Learning Journey

- Started with Bootstrap basics → moved to custom styling  
- Learned when to use flexbox vs grid  
- Improved debugging skills through real issues  
- Built confidence in creating responsive multi-page websites  
- Used AI tools only for specific fixes, not full development  

---

### 🎯 Learning Outcomes

- Bootstrap is a base, not a complete design solution  
- CSS variables improve consistency  
- Real understanding comes from debugging  
- IntersectionObserver enables smooth animations  
- Multi-page structure improves scalability  

---

### ⏱ Time Taken

Completed in approximately **10 hours**:

- Planning & setup — 1 hr  
- Home page — 3 hrs  
- About page — 2 hrs  
- Contact page — 3 hrs  
- Testing & deployment — 1 hr  

---

### ✅ Conclusion

This project helped me understand how to design, build, debug, and deploy a complete responsive website using modern frontend technologies.

---
