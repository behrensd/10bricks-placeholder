# GitHub Pages Placeholder Site

A simple placeholder page with Akira font, ready to deploy on GitHub Pages.

## Files Structure
```
.
├── index.html
└── fonts/
    └── Akira Expanded Demo.otf
```

## Next Steps to Deploy on GitHub Pages

### 1. Create a GitHub Repository
- Go to [GitHub](https://github.com) and sign in
- Click the "+" icon in the top right corner
- Select "New repository"
- Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
- Make it **Public**
- Click "Create repository"

### 2. Upload Your Files
You have two options:

**Option A: Using GitHub Web Interface**
- In your new repository, click "Add file" → "Upload files"
- Drag and drop:
  - `index.html`
  - The entire `fonts` folder (with `Akira Expanded Demo.otf` inside)
- Add a commit message (e.g., "Initial commit")
- Click "Commit changes"

**Option B: Using Git Command Line**
```bash
cd "/Users/dom/10bricks placeholder"
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repository on GitHub
- Click on "Settings" tab
- Scroll down to "Pages" in the left sidebar
- Under "Source", select "Deploy from a branch"
- Choose "main" branch and "/ (root)" folder
- Click "Save"

### 4. Access Your Site
- Wait 1-2 minutes for GitHub to build your site
- Visit `https://yourusername.github.io` to see your placeholder page!

## Customization
Edit `index.html` to change the text, styling, or add more content.

