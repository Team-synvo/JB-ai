# JBAFF - Jailbreak Archive & Fix Framework

A dark-themed documentation website for AI jailbreak techniques and defense strategies.

## 🚀 GitHub Pages Deployment

### Quick Setup

1. **Upload to GitHub:**
   ```bash
   # Create a new repository on GitHub
   # Then run these commands in your terminal:
   
   git init
   git add .
   git commit -m "Initial commit: JBAFF website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select branch: **main**
   - Select folder: **/ (root)**
   - Click **Save**

3. **Your site will be live at:**
   ```
   https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
   ```

## 📁 File Structure

```
.
├── index.html       # Main HTML file
├── styles.css       # All styling
├── script.js        # Interactive features
└── README.md
```

## ✨ Features

- **Dark Theme**: Professional dark UI optimized for readability
- **Live Search**: Filter jailbreaks by name (e.g., "GROK v9")
- **Smooth Animations**: Fade-ins, slide-ups, and hover effects
- **Code Blocks**: One-click copy functionality
- **Expandable Instructions**: Step-by-step guides for each script
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Pure Static**: No build process, no dependencies

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --bg-primary: #0a0a0a;
    --primary: #a855f7;
    /* ... other colors ... */
}
```

### Add More Scripts
Add new script cards in `index.html` following the existing pattern.

## 📝 Educational Purpose

This documentation is for educational and research purposes only. It helps AI developers understand vulnerabilities and implement better security measures.

## 🛠️ Local Testing

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

---

**JBAFF** - Educational Resource • 2025
