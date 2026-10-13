# Varsha D. | Personal Portfolio Website

A modern, premium developer portfolio website designed and built for **Varsha D.**, an aspiring software developer and data analyst.

Built with **React**, **TypeScript**, **Tailwind CSS**, and **Lucide Icons**, featuring a dark navy and pitch-black theme, electric blue and purple gradients, subtle ambient glowing effects, smooth animations, rounded cards, and responsive layouts across desktops, laptops, tablets, and smartphones.

---

## 🎨 Design & Style
- **Color Palette:** Dark navy and pitch-black backgrounds (`#030712`, `#060b18`, `#0b1329`) with vibrant electric blue (`#3b82f6`, `#06b6d4`) and electric purple (`#8b5cf6`, `#a855f7`) gradients.
- **Visuals:** Subtle ambient glowing orbs, glassmorphic cards (`backdrop-blur-xl`), animated gradient borders, and clean modern typography (`Plus Jakarta Sans` & `JetBrains Mono`).
- **Hero Section:** Dynamic typing animation rotating between roles (*Data Analyst*, *Python Developer*, *Software Developer*, *Problem Solver*), circular profile photo frame with glowing rings and floating tech badges, quick project & contact CTAs.
- **A11y & Motion:** Accessible skip links, aria-labels, focus indicators, and support for `prefers-reduced-motion`.

---

## 🧭 Sections & Features

1. **Sticky Navigation Bar:**
   - Displays "Varsha D." with custom glowing monogram.
   - Smooth navigation links: *Home*, *About*, *Skills*, *Projects*, *Experience*, *Contact*.
   - Quick **Download Resume** button with toast feedback.
   - Slide-out mobile drawer with backdrop overlay.

2. **Hero Section:**
   - Heading: *"Hi, I'm Varsha D."*
   - Role: *"Aspiring Software Developer | Data Analyst"*
   - Dynamic typing animation for roles.
   - Circular profile photo area with blue-purple gradient background, glowing rings, and floating badges.
   - Action buttons: *"Explore My Projects"*, *"Contact Me"*, and *"Resume"*.
   - Direct GitHub, LinkedIn, and Email connect icons.

3. **About Me:**
   - Two-column modern layout with professional narrative.
   - 4 Feature Cards:
     - **Web Development** (React, Frontend, Responsive UI)
     - **Data Analytics** (Power BI, Python, Pandas, BI Dashboards)
     - **Problem Solving** (Core Logic, Java, SQL, Database Systems)
     - **Continuous Learning** (AI Exploration, Embedded Systems, IoT)

4. **Skills:**
   - Categorized cards without fake proficiency percentages:
     - **Programming:** Python, Java, SQL
     - **Data Analytics:** Power BI, Excel, Python Data Cleaning
     - **Database:** MySQL, SQLite
     - **Web Development:** HTML, CSS, JavaScript, React
     - **Tools:** Git, GitHub, Visual Studio Code
     - **Hardware:** Arduino, Sensors, Embedded Systems
   - Category filtering and glowing hover effects.

5. **Projects Showcase:**
   - **Revenue Sales Analytics Dashboard** (Power BI, Python, Data Analytics)
   - **Smart Road Safety and Accident Prevention System** (Arduino, Sensors, Python, Web Development)
   - **Traffic Violation Management System** (SQL, MySQL, Database Management)
   - **AI-Assisted Digital Forensics Recovery** (AI, Data Recovery, Database, Web Development)
   - Interactive Project Modal with in-depth architecture, key features, preview mockup, and GitHub links.

6. **Experience & Education:**
   - Comprehensive timeline with tab filtering (*All*, *Internship*, *Education*, *Certifications*, *Hackathons*):
     - **Industry Internship:** Data Analytics Intern at *iRobo Automation Pvt. Ltd., Mysuru* (Power BI & Python data cleaning pipelines).
     - **Academic Foundation:** Bachelor of Engineering / Technology (B.E./B.Tech) & Pre-University (12th Grade).
     - **Professional Certifications:** Python Data Analytics, Power BI Business Intelligence, SQL & Relational Databases.
     - **Hackathons & Competitions:** Technical Symposiums & Prototype Demonstrations.

7. **Achievements:**
   - Verified milestones for hackathon prototype exhibitions, analytics pipeline deployments, database schema architecture, and technical certifications.

8. **Contact & Resume:**
   - 1-Click "Copy Email" and direct links for Email, LinkedIn, and GitHub.
   - Interactive contact form with client-side validation and toast confirmation.
   - Clear notice for connecting backend email forwarding services (Formspree, EmailJS, Web3Forms).

9. **Footer:**
   - Displays *"Designed and built by Varsha D."*
   - Social links, navigation links, and back-to-top smooth scrolling button.

---

## 🚀 Running the Project Locally

```bash
# 1. Install dependencies
npm install

# 2. Run local development server
npm run dev

# 3. Build for production
npm run build

# 4. Preview production build
npm run preview
```

Open `http://localhost:5173` in your browser.

---

## ✏️ Customizing Your Content

All data is centralized in one file for effortless editing:
📂 **`src/data/portfolioData.ts`**

Update your socials, email, resume file, or add more projects and certifications whenever you like!

---

## 📄 Updating the Resume PDF
Place your updated resume file named `resume.pdf` into the **`public/`** folder. The download buttons throughout the site will automatically serve this file.
