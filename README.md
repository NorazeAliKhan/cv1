# Noraze Khan — Executive CV & Portfolio Website

A responsive, single-page CV portfolio website for **Noraze Khan**, implemented from the supplied design specification (`DESIGN.md` and `screen.png`).

---

## 🚀 How to Run the Website

You can view and run the website immediately using either of these quick methods:

### Method 1: Direct File Open (Recommended & Fastest)
Double-click `index.html` in Windows Explorer or open it in any web browser:
```powershell
Start-Process "c:\Users\DELL\Desktop\CV page with scroll\index.html"
```

### Method 2: Local HTTP Server (PowerShell)
Run the included lightweight local server:
```powershell
powershell -ExecutionPolicy Bypass -File .\serve.ps1
```
This automatically hosts the site at `http://localhost:8080/` and launches it in your default browser.

---

## 📐 Sections & Structure

All sections are organized on one continuous page with vertical scrolling:

1. **Sticky Navigation Bar**
   - Brand logo with title and `Intern` status badge
   - Navigation links in order: **About**, **Skills**, **Projects**, **Education**, **Certifications**, **Contact**
   - Direct "Contact Me" button
   - Interactive ScrollSpy that dynamically highlights the section currently in view
   - Responsive mobile hamburger menu with animated drawer for small screens

2. **Hero Section** (`#hero`)
   - Eyebrow tag: `Computer Science Student`
   - Name: **Noraze Khan**
   - Title: `Aspiring Software Developer | BSCS Student`
   - Professional introduction focusing on web engineering and AI
   - Call-to-action buttons: **View My Projects** (smooth scrolls to `#projects`) and **Contact Me** (smooth scrolls to `#contact`)
   - Verified GitHub link (`https://github.com/NorazeAliKhan`)
   - Professional clean student portrait photo with ambient lighting and card container

3. **About Me** (`#about`)
   - Professional summary describing background and internship aspirations
   - 3 Key Metric Cards:
     - **Degree**: BS Computer Science, Qarshi University
     - **Graduation**: Expected 2027, Currently in 7th Semester
     - **Current CGPA**: 2.91 / 4.00, Academic Standing

4. **Technical Skills** (`#skills`)
   - Categorized into 6 cards:
     - **Programming Languages**: Python, Java, C++, JavaScript
     - **Frontend Development**: HTML5, CSS3, React.js
     - **Backend Development**: Node.js, PHP
     - **Database Technologies**: Database Fundamentals
     - **Tools & Design**: Git, GitHub, VS Code, Figma, AI-powered development tools
     - **Core Concepts**: Object-Oriented Programming (OOP), Web Development

5. **Featured Projects** (`#projects`)
   - **Fixora — Home Services Platform** (`In Progress`) with custom connected node architecture SVG visualization
   - **AI Interior Design** (`In Progress | Final Year Project`) with custom isometric wireframe SVG visualization
   - **University Portal** (`Completed | OOP Project`) with custom academic portal dashboard SVG visualization

6. **Education** (`#education`)
   - Qarshi University — Bachelor of Science in Computer Science (BSCS)
   - 7th Semester | Expected Graduation: 2027 | Lahore, Pakistan
   - Current CGPA: 2.91 / 4.00

7. **Certifications & Learning** (`#certifications`)
   - **Artificial Intelligence** — Coursera (Completed)
   - **Web Development** — Coursera (Completed)

8. **Let's Connect (Contact)** (`#contact`)
   - Direct clickable email link: `mailto:norazekha01@gmail.com`
   - Direct GitHub link: `https://github.com/NorazeAliKhan`
   - Location: Lahore, Pakistan
   - Interactive "Get In Touch" action card with "Email Me" and "View GitHub Profile" buttons

9. **Footer**
   - Copyright: `© 2026 Noraze Khan. All rights reserved.`
   - Smooth "Back to Top" navigation button

---

## 🎨 Design System & Palette

- **Deep Navy Blue**: `#14213D` / `#000A24` (dominant headings, brand identity)
- **Professional Blue**: `#0051D5` / `#2563EB` (actions, links, active states)
- **Teal Accent**: `#0F9D8A` / `#83F6E0` (tags, badges, pulse indicators)
- **Background Surface**: `#F8F9FF`
- **Card Surfaces**: `#FFFFFF` with `#E5E7EB` border contours
- **Typography**: `Inter` (Google Fonts) with Material Symbols icons

---

## 📱 Responsive Support

- **Desktop (1024px+)**: 12-column layout with right-column terminal and 3-column project grid.
- **Tablet (768px - 1023px)**: 2-column cards with responsive spacing.
- **Mobile (< 768px)**: Stacked single-column layout, touch-friendly tap targets, and full mobile navigation drawer.
