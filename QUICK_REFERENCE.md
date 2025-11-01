# Quick Reference Guide - Where to Edit What

## 🎯 Most Common Edits

### Change Your Name/Bio
📁 `content/authors/admin/_index.md`

### Update Homepage Text
📁 `content/_index.md` (look for "My Research & Work")

### Add a New Project
1. Create folder: `content/projects/my-project-name/`
2. Add file: `content/projects/my-project-name/index.md`
3. Copy format from `content/projects/pandas/index.md`

### Add a New Publication
1. Create folder: `content/publications/my-paper/`
2. Add file: `content/publications/my-paper/index.md`
3. Copy format from `content/publications/conference-paper/index.md`
4. Optional: Add `featured.jpg`, `cite.bib`, PDF

### Add a New Talk/Event
1. Create folder: `content/events/my-talk/`
2. Add file: `content/events/my-talk/index.md`
3. Copy format from `content/events/example/index.md`

### Replace Your Photo
📁 `content/authors/admin/avatar.png` (keep filename, replace image)

### Update Your Resume PDF
📁 `static/uploads/resume.pdf`

### Change Site Title
📁 `config/_default/hugo.yaml` → `title` field

### Change Site Colors/Theme
📁 `config/_default/params.yaml` → `appearance.color` field

### Change Navigation Menu
📁 `config/_default/menus.yaml`

---

## 🔍 Find All TODOs

Run this in your terminal to see all TODO notes:
```bash
cd /Users/qiantaichen/Documents/GitHub/QianleChen.github.io
grep -r "<!-- TODO:" content/
```

---

## 🚀 Build & Run

### Local Development
```bash
cd /Users/qiantaichen/Documents/GitHub/QianleChen.github.io
pnpm install
hugo server
# Open http://localhost:1313
```

### Build for Production
```bash
hugo
# Site built in public/ folder
```

---

## 📂 File Structure at a Glance

```
├── config/_default/          # Site configuration
│   ├── hugo.yaml            # Site title, URL
│   ├── params.yaml          # Theme, SEO, navbar
│   └── menus.yaml           # Navigation links
│
├── content/
│   ├── _index.md            # Homepage
│   ├── authors/admin/       # Your profile
│   ├── projects/            # Your projects
│   ├── publications/        # Your papers
│   ├── events/              # Your talks
│   ├── blog/                # Blog posts
│   └── experience.md        # Experience page
│
├── static/uploads/          # Files for download
│   └── resume.pdf           # Your CV/resume
│
└── assets/media/            # Images and media
```

---

## 💡 Pro Tips

1. **Before editing**, always read the file comments and frontmatter structure
2. **After editing**, test locally with `hugo server`
3. **Search for examples**: If unsure of format, find a similar file and copy its structure
4. **Keep consistent**: Use the same date format, tags, and structure across similar content types
5. **Images**: Name featured images as `featured.jpg` or `featured.png` in each content folder

---

## 🆘 Quick Troubleshooting

**Site won't build?**
- Check YAML syntax (indentation matters!)
- Make sure frontmatter is between `---` markers
- Run `hugo --verbose` to see detailed errors

**Changes not showing?**
- Hard refresh browser (Cmd+Shift+R on Mac)
- Clear browser cache
- Restart `hugo server`

**Image not displaying?**
- Check filename matches what's in frontmatter
- Verify image is in correct folder
- Check file extension (.jpg vs .jpeg, .png)

---

For detailed explanations, see **README.md** Edit Guide section!

