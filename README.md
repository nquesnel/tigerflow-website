# TigerFlow Website

This is the official website for TigerFlow - SEO Analyzer for Webflow.

## Setup Instructions

### 1. Create GitHub Repository

1. Go to [GitHub](https://github.com/new)
2. Create a new repository named `tigerflow-website`
3. Make it public
4. Don't initialize with README (we have one here)

### 2. Push to GitHub

```bash
cd /Users/q/tigerflow-website
git init
git add .
git commit -m "Initial commit - TigerFlow website"
git branch -M main
git remote add origin https://github.com/[yourusername]/tigerflow-website.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and "/ (root)"
6. Click "Save"

### 4. Access Your Site

Your site will be available at:
- `https://[yourusername].github.io/tigerflow-website/`

Note: It may take a few minutes for the site to become available after enabling GitHub Pages.

## URLs for Webflow Submission

Once deployed, use these URLs:
- Privacy Policy: `https://[yourusername].github.io/tigerflow-website/privacy.html`
- Terms of Service: `https://[yourusername].github.io/tigerflow-website/terms.html`
- Support: `https://[yourusername].github.io/tigerflow-website/support.html`

## Customization Needed

Before deploying, update:
1. Email address in `support.html` (currently placeholder: support@tigerflow.app)
2. GitHub Issues link in `support.html` (update username)
3. Install link on homepage when you have the Webflow marketplace URL

## Optional: Custom Domain

If you want to use a custom domain:
1. Create a `CNAME` file in this directory with your domain (e.g., `tigerflow.app`)
2. Configure your domain's DNS to point to GitHub Pages
3. Enable HTTPS in GitHub Pages settings

## File Structure

```
tigerflow-website/
├── index.html         # Homepage
├── privacy.html       # Privacy Policy
├── terms.html         # Terms of Service
├── support.html       # Support/FAQ page
├── style.css          # Styles with TigerFlow branding
├── README.md          # This file
└── CNAME             # (Optional) Custom domain
```

## Color Palette

- Tiger Orange: #FF6B35
- Amber Gold: #FFB627
- Tiger Black: #1A1A1A
- Cream White: #FFF8F0
- Success Green: #22C55E
- Warning Red: #EF4444