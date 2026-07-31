# Academic Profile Website - Dr. Sachin Kumar

A professional, responsive academic website showcasing research, publications, team, and projects. Built with clean HTML/CSS for easy deployment on GitHub Pages.

## 📁 File Structure

```
/
├── index.html              # Home page (main profile)
├── publications.html       # Complete publications list
├── team.html              # Team members and supervision
├── projects.html          # Research projects and grants
├── profile.jpg            # Your profile photo (add this)
├── README.md              # This file
└── style-guide.txt        # Customization guide
```

## 🚀 Quick Start - Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in to your account
2. Click **"New"** to create a new repository
3. Name it: `yourusername.github.io`
   - Example: `sachinikumar.github.io`
4. Make sure it's **Public**
5. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop all HTML files and this README
3. Add a commit message: `Initial commit: Academic profile website`
4. Click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Clone the repository
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io

# Copy all files into this directory
# Then commit and push
git add .
git commit -m "Initial commit: Academic profile website"
git push origin main
```

### Step 3: Add Your Profile Photo

1. Save your professional headshot as `profile.jpg` (180x180 px recommended)
2. Upload to your GitHub repository
3. The website will automatically display it

### Step 4: Access Your Site

Your website will be live at: **https://yourusername.github.io**

*Note: It may take 1-5 minutes for GitHub Pages to build and deploy.*

---

## ✏️ Customization Guide

### Edit Personal Information

Open `index.html` and locate the profile section:

```html
<h1>Dr. Sachin Kumar</h1>
<div class="title">
    Associate Professor<br>
    Computer Science<br>
```

Update with your:
- Full name
- Title
- Department
- Institution
- Contact information

### Update Social Links

In `index.html`, find the `.links` section:

```html
<div class="links">
    <a href="https://scholar.google.co.in/citations?user=FtQHB6kAAAAJ&hl=en" target="_blank">Google Scholar</a>
    <!-- Update these URLs to your profiles -->
```

### Customize Content Sections

All sections are clearly marked in HTML with comments:

```html
<!-- Research Interests -->
<section id="research">
    <h2>Research Interests</h2>
    <!-- Edit bullet points here -->
```

Key sections to update:
- **Short Bio** - Your professional summary
- **News** - Latest updates (add/remove news items)
- **Research Interests** - Your research focus areas
- **Experience** - Employment history
- **Education** - Degrees and institutions
- **Courses** - Courses you teach
- **Awards** - Recognitions and honors

### Update Publications

Edit `publications.html`:

1. Add/remove publication entries
2. Update with your actual publications
3. Include DOI links and journal information
4. Organize by year

### Update Team Section

Edit `team.html`:

1. Add your current advisees
2. Update postdoc information
3. Remove placeholder names
4. Add open positions description

### Modify Project Details

Edit `projects.html`:

1. Replace with your actual research projects
2. Update grant information
3. Add project descriptions
4. Include outcomes and publications

---

## 🎨 Styling & Colors

The default color scheme uses:
- **Primary Blue**: `#0066cc` - Headers, links
- **Dark Text**: `#1a1a1a` - Headings
- **Body Text**: `#333` - Regular text
- **Light Background**: `#f8f9fa` - Sections

### Change Primary Color

Find this in each HTML file's `<style>` section:

```css
color: #0066cc;  /* Change this hex code */
```

Replace `#0066cc` with your preferred color throughout.

---

## 📱 Responsive Design

The website automatically adapts to different screen sizes:
- **Desktop**: Full layout with 2-column sections
- **Tablet**: Adjusted spacing
- **Mobile**: Single-column layout, touch-friendly

No additional work needed - responsiveness is built-in!

---

## 🔍 SEO & Meta Tags

Optimize for search engines by updating the meta tags in each file:

```html
<title>Dr. Sachin Kumar - Associate Professor</title>
<meta name="description" content="Your short bio or description">
<meta name="keywords" content="machine learning, AI, healthcare, ...">
```

---

## 📊 Adding/Removing Sections

### To Add a New Section:

1. Add in `index.html` after existing sections:
```html
<section id="new-section">
    <h2>New Section Title</h2>
    <p>Your content here...</p>
</section>
```

2. Add to table of contents:
```html
<li><a href="#new-section">New Section</a></li>
```

### To Remove a Section:

1. Delete the entire `<section>` block
2. Remove from table of contents

---

## 🔗 Navigation

- **HOME**: Links to `index.html`
- **RESEARCH**: Jumps to research section in index
- **EXPERIENCE**: Jumps to experience section in index
- **PUBLICATIONS**: Links to `publications.html`
- **TEAM**: Links to `team.html`
- **PROJECTS**: Links to `projects.html`

Navigation is consistent across all pages for easy browsing.

---

## 💡 Tips & Best Practices

### Profile Photo
- Size: 180x180 pixels (will be automatically sized)
- Format: JPG or PNG
- Recommended: Professional headshot on neutral background
- File name: `profile.jpg`

### Text Content
- Keep paragraphs concise (2-3 sentences)
- Use bullet points for lists
- Bold important terms using `<strong>` tags
- Maintain professional tone throughout

### Links
- Always use full URLs: `https://example.com`
- Add `target="_blank"` to external links
- Test all links before publishing

### Updates
- Update "Last updated" date in footer
- Review news section regularly
- Keep publication list current

---

## 🐛 Troubleshooting

### Website Not Showing?
1. Check repository name is `yourusername.github.io`
2. Ensure files are in the main branch
3. Wait 5 minutes for GitHub Pages to build
4. Check repository settings: Settings → Pages (should be enabled)

### Images Not Showing?
1. Ensure `profile.jpg` is in the same directory as HTML files
2. Check file name matches exactly (case-sensitive on Linux)
3. Use full paths for images if needed

### Styling Looks Wrong?
1. Clear browser cache (Ctrl+Shift+Delete)
2. Try different browser
3. Check that CSS is between `<style>` tags

### Links Not Working?
1. Verify URLs start with `https://`
2. Check for typos in file names
3. Ensure external links are correct

---

## 📚 Resources

- **GitHub Pages Guide**: https://pages.github.com/
- **HTML Tutorial**: https://www.w3schools.com/html/
- **CSS Tutorial**: https://www.w3schools.com/css/
- **Markdown Guide**: https://www.markdownguide.org/

---

## 📝 File Descriptions

| File | Purpose |
|------|---------|
| `index.html` | Main profile page with bio, research interests, and CV sections |
| `publications.html` | Complete list of publications organized by year |
| `team.html` | Information about advisees, postdocs, and supervision philosophy |
| `projects.html` | Current research projects, grants, and research themes |
| `profile.jpg` | Your professional headshot (add this yourself) |

---

## ✅ Before Going Live

- [ ] Add your professional photo (`profile.jpg`)
- [ ] Update all personal information
- [ ] Verify all links work
- [ ] Update publications list
- [ ] Check Google Scholar and Scopus links
- [ ] Review formatting and spelling
- [ ] Test on mobile device
- [ ] Update footer year if needed
- [ ] Add social media profiles (Google Scholar, LinkedIn, etc.)

---

## 🎓 Advanced Customization

### Add Google Analytics
Add before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_GA_ID"></script>
```

### Add a Blog Section
Create new file `blog.html` following the same template, add to navigation

### Custom Domain
In GitHub settings, add your custom domain in Pages section

### Enable SSL Certificate
GitHub Pages automatically provides HTTPS - no action needed

---

## 📧 Support & Questions

For detailed information about your research, publications, or updates:
- Email: s.kumar@aua.am
- Profile: https://people.aua.am/team_member/sachin-kumar-phd/

For GitHub Pages help:
- GitHub Docs: https://docs.github.com/en/pages
- GitHub Support: https://support.github.com

---

## 📄 License

This template is free to use and modify for academic purposes.

---

**Last Updated**: March 2025

Good luck with your academic website! 🎉
