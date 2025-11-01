# Qianle (Bill) Chen - Academic CV

<h1 align="center">🌍 Environmental Science Research & Sustainability Advocacy</h1>

<p align="center">
  <strong>Research Assistant at UCLA | Founder of Harmony with Nature | Student Researcher</strong><br/>
  Bridging climate science, data analytics, and community action for a sustainable future.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/qianle-chen/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=social&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://HarmonyWithNature.org">
    <img src="https://img.shields.io/badge/Website-Harmony%20with%20Nature-green?style=social" alt="Harmony with Nature">
  </a>
  <a href="mailto:qianlechen4324@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=social&logo=gmail" alt="Email">
  </a>
</p>

---

## 👋 About Me

I'm a high school senior and aspiring environmental scientist conducting research at UCLA's Joint Institute for Regional Earth System Science and Engineering (JIFRESSE). My work focuses on:

- 🔥 **Wildfire & Climate Research** - Analyzing thermal satellite imagery to study wildfire progression and urban heat patterns (featured in NASA's Caltech JPL ECOSTRESS gallery)
- 🤖 **AI for Emergency Response** - Coordinating a $1M research project with Orange County Fire Department to develop AI-based decision-support models
- 🌱 **Environmental Stewardship** - Founder & President of Harmony with Nature, a 501(c)(3) nonprofit engaging 250+ participants in sustainability education
- 📊 **IoT & Data Science** - Developed an air quality monitoring system with Python analytics and mobile app deployment

I'm passionate about applying remote sensing, GIS, and data science to address environmental challenges while bridging research and community action.

---

## 🔬 Research & Projects

### Current Research
- **UCLA JIFRESSE** - Wildfire progression analysis using thermal satellite imagery
- **Orange County Fire Department Partnership** - AI decision-support for resource allocation
- **Air Quality Monitoring** - IoT sensor network with real-time pollutant tracking

### Featured Projects
- 🌿 **Harmony with Nature** - 501(c)(3) nonprofit promoting sustainability through education
- 📱 **AtmoFlow App** - Cross-platform mobile app for live air quality monitoring
- 📚 **The Little Tree That Could** - Self-published children's book on urban reforestation (500+ trees funded)

---

## 🛠️ Technical Skills

- **Programming:** Python, data analytics, mobile app development
- **Research Tools:** GIS, remote sensing, thermal imagery analysis, ECOSTRESS data
- **Environmental Science:** Climate research, air quality monitoring, IoT sensors (BME280, LTR-559, MICS6814)
- **Languages:** English (native), Chinese (Mandarin), Spanish, French, German

---

## 🎓 Education

- **Arnold O. Beckman High School** - GPA: 3.97/4.00 (Unweighted), 4.67/4.00 (Weighted)
- **Irvine Valley College** - Dual Enrollment, GPA: 4.00/4.00
- **California State Summer School for Mathematics and Science** - Research Program (2025)

---

## 🚀 Getting Started with This Site

This academic CV website is built with [Hugo Blox Builder](https://hugoblox.com/) and showcases my research, projects, and experiences in environmental science and sustainability.

### Run Locally

```bash
# Install dependencies
pnpm install

# Start development server
hugo server

# Visit http://localhost:1313
```

### Deploy

This site can be deployed to:
- **GitHub Pages** (recommended)
- **Netlify**
- **Vercel**
- Any static hosting service

---

## 🌐 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/qianle-chen/)
- 🌱 [Harmony with Nature](https://HarmonyWithNature.org)
- 📧 [qianlechen4324@gmail.com](mailto:qianlechen4324@gmail.com)

---

## 📚 Resources

- **Hugo Blox Documentation:** [docs.hugoblox.com](https://docs.hugoblox.com/)
- **Hugo Documentation:** [gohugo.io/documentation](https://gohugo.io/documentation/)
- **UCLA JIFRESSE:** [jifresse.ucla.edu](https://jifresse.ucla.edu/)

---

## 📝 Edit Guide: How to Update Your Site Content

This guide explains exactly where to edit each component of your academic CV site.

### 👤 Personal Profile & Biography

**File:** `content/authors/admin/_index.md`

Edit this file to update:
- Name, role/tagline, and bio paragraph (at the bottom)
- Email, social links (LinkedIn, website, etc.)
- Interests/research areas
- Education history (degrees, institutions, dates, GPA, coursework)
- Work experience (positions, companies, dates, descriptions)
- Skills (technical, leadership, hobbies)
- Languages (with proficiency percentages)
- Awards & certifications

**Avatar Photo:** Replace `content/authors/admin/avatar.png` with your photo (keep the filename).

---

### 🏠 Homepage Sections

**File:** `content/_index.md`

This file controls all homepage sections/widgets:

- **Research Section:** Edit the markdown block titled "My Research & Work"
- **Section Visibility:** Each block has an `id` (e.g., `papers`, `talks`, `news`). To hide a section, comment it out or remove it.
- **Section Order:** Rearrange blocks to change the order of sections on your homepage.

---

### 📚 Publications

**Location:** `content/publications/`

- **Main Index:** `content/publications/_index.md` (controls the publications page settings)
- **Individual Publications:** Create a subfolder for each publication (e.g., `content/publications/my-paper/`)
  - Add `index.md` with frontmatter (title, authors, date, publication venue, abstract, DOI, links)
  - Add `featured.jpg` for a cover image
  - Add `cite.bib` for BibTeX citation
  - Add PDF files directly to the folder

**Example:** See `content/publications/conference-paper/` for the format.

---

### 💼 Projects

**Location:** `content/projects/`

- **Main Index:** `content/projects/_index.md` (controls the projects page)
- **Individual Projects:** Each project has its own subfolder (e.g., `content/projects/air-quality-sensor/`)
  - Edit `index.md` with frontmatter (title, date, summary, tags, links)
  - Add `featured.png` or `featured.jpg` for a project image
  - Write detailed project descriptions in markdown below the frontmatter

**Current Projects:**
- `pandas/` → Air Quality Sensor Development Project
- `pytorch/` → Harmony with Nature Non-Profit
- `scikit/` → The Little Tree That Could

---

### 🎤 Talks & Events

**Location:** `content/events/`

- **Main Index:** `content/events/_index.md` (controls the talks/events page)
- **Individual Talks:** Create a subfolder for each talk (e.g., `content/events/my-talk/`)
  - Add `index.md` with frontmatter (title, event, location, date, abstract, slides/video links)
  - Add `featured.jpg` for an event image

**Example:** See `content/events/example/` for the format.

---

### 📰 Blog Posts

**Location:** `content/blog/`

- **Main Index:** `content/blog/_index.md`
- **Individual Posts:** Each post has its own subfolder with `index.md`
- Format is similar to projects/publications

---

### 📄 CV/Resume PDF

**Location:** `static/uploads/resume.pdf`

Replace this file with your updated CV/resume PDF. The download button on the homepage links to this file.

---

### ⚙️ Site Configuration

**Global Settings:** `config/_default/`

- **`hugo.yaml`** - Site title, base URL, language settings
- **`params.yaml`** - Site description, SEO, logo text, theme colors, navbar settings
- **`menus.yaml`** - Navigation menu items (add/remove/reorder menu links)
- **`languages.yaml`** - Multi-language support (if needed)
- **`module.yaml`** - Hugo modules and theme settings

**Common edits:**
- Site title: `config/_default/hugo.yaml` → `title`
- Site description: `config/_default/params.yaml` → `marketing.seo.description`
- Logo text: `config/_default/params.yaml` → `header.navbar.logo.text`
- Theme color: `config/_default/params.yaml` → `appearance.color`

---

### 📊 Experience Page (Detailed View)

**File:** `content/experience.md`

This page pulls from your author profile (`content/authors/admin/_index.md`) but displays it in a dedicated page format. Edit settings here to:
- Reorder education/experience sections
- Show/hide skill percentages
- Customize date formats

---

### 🎨 Images & Media

**Locations:**
- **Profile avatar:** `content/authors/admin/avatar.png`
- **Project/publication images:** Add `featured.jpg` or `featured.png` to each project/publication folder
- **Other media:** `assets/media/` or `static/img/`

---

### 🚀 Building & Deploying

**Local Development:**
```bash
# Install dependencies
pnpm install

# Run local server
hugo server

# View at http://localhost:1313
```

**Building for Production:**
```bash
hugo
# Output in public/ folder
```

**Deployment:**
- Push to GitHub
- Deploy via Netlify, GitHub Pages, or your preferred hosting service

---

### 📝 TODO Notes

Look for `<!-- TODO: ... -->` comments in content files for placeholders to fill in later.

---

### 🆘 Need Help?

- **Hugo Blox Documentation:** https://docs.hugoblox.com/
- **Community Discord:** https://discord.gg/z8wNYzb
- **Hugo Documentation:** https://gohugo.io/documentation/

---

MIT © 2016-Present [George Cushen](https://georgecushen.com)

<!--START_SECTION:news-->
<!--END_SECTION:news-->
