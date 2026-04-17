======================================
  FIENYX TRANSLATION — Website 2026
======================================

PROJECT OVERVIEW
-----------------
This is the official website for Fienyx Translation, a professional
linguistic services agency founded in 2017, headquartered in Yogyakarta,
Indonesia.

FOLDER STRUCTURE
-----------------
fienyx-website/
│
├── index.html          → Main site (English)
├── id.html             → Indonesian version (Bahasa Indonesia)
├── robots.txt          → SEO: search engine crawl rules
├── README.txt          → This file
│
└── css/
    └── styles.css      → Main stylesheet (shared by both HTML pages)

HOW TO DEPLOY
--------------
Option 1 — GitHub Pages (free):
  1. Create a GitHub repo (e.g. fienyxtranslation.github.io)
  2. Upload all files preserving the folder structure
  3. Go to Settings > Pages > Deploy from branch (main / root)
  4. Your site will be live at https://fienyxtranslation.github.io

Option 2 — Netlify Drop (instant):
  1. Go to https://app.netlify.com/drop
  2. Drag & drop the entire fienyx-website/ folder
  3. Your site is live instantly with a free subdomain

Option 3 — Vercel:
  1. Go to https://vercel.com
  2. Connect your GitHub repo or drag & drop
  3. Vercel auto-detects static HTML and deploys

CUSTOMIZING
------------
Colors: Edit the CSS variables in css/styles.css under :root {}
  --blush:       #f9d2ca  (soft pink / accent)
  --navy:        #2d3c7c  (deep navy / primary)
  --mauve:       #a58c85  (warm taupe)
  --periwinkle:  #8788ae  (blue-purple / interactive)
  --lavender:    #9494bc  (lighter purple)

Email: Replace "contact@fienyxtranslation.com" with your actual email
       (search & replace in both index.html and id.html)

Social Links: Update all href="https://..." links in the footer section

Team Photos: Replace the placeholder letters in .team-avatar-placeholder
  divs with actual <img> tags pointing to your photo files.

LANGUAGE SWITCHING
-------------------
- English version: index.html
- Indonesian version: id.html
- A language switcher button in the top-right corner links between them

SEO METADATA
-------------
Each page includes:
  - <meta name="description"> for search engines
  - <meta name="keywords"> relevant to the services
  - Open Graph tags for social sharing
  - Canonical URL tag
  - robots.txt for crawl guidance

CONTACT
--------
Website: https://fienyxtranslation.github.io
Email:   contact@fienyxtranslation.com
Facebook: https://web.facebook.com/Fienyx.translation
Twitter:  https://twitter.com/Fienyxtrans

© 2026 Fienyx Translation. All rights reserved.
