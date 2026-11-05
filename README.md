# Neil Jun Maglunsod - Portfolio

Static portfolio site for an AI Automation & GoHighLevel Specialist, hosted on Netlify.

Live site: https://neiljun-automation.netlify.app/

## Files

- `index.html` - main page
- `case-study-*.html` - project case studies
- `Neil_Jun_Maglunsod_Resume.pdf` - resume download
- `robots.txt`, `sitemap.xml` - search engine files

## Preview

Open the folder in VS Code and use the Live Server extension, or open `index.html` in a browser. The contact form can only be tested on Netlify.

## Contact form

The form posts to Netlify Forms and to an n8n webhook. A success message appears only when Netlify returns a 2xx status, or the webhook returns JSON with `"messageSaved": true`. Netlify form detection must be enabled for the site.
