BEXMOUNT WEBSITE — READY TO PUBLISH
==================================
Files:
- index.html: Website content and SEO metadata
- styles.css: Responsive navy/white/gold design
- script.js: Mobile menu and footer year
- favicon.svg: Browser tab icon

Quick preview: open index.html in a browser.

Publishing with GitHub Pages:
1. Create a GitHub repository (for example, bexmount-site).
2. Upload these four files to the repository root.
3. In Settings > Pages, select Deploy from a branch, main, / (root).
4. Under Custom domain, enter bexmount.com and save.
5. At your domain registrar, set the A records for the root domain to GitHub Pages' current documented IP addresses, and set www as a CNAME to your GitHub Pages hostname. Verify current values in GitHub documentation before applying them.
6. Enable Enforce HTTPS once the certificate is available.

IMPORTANT: Keep your Google Workspace MX, SPF, DKIM and DMARC DNS records in place. Changing website A/CNAME records does not require deleting email DNS records.

Before launch:
- Confirm justin@bexmount.com is the intended contact email (it is used in mailto links).
- Confirm that all website descriptions accurately reflect your current services.
- Consider adding a privacy policy before installing analytics or collecting personal data through forms.
- This site uses mailto links, not a contact form or data collection backend.
- Fonts are loaded from Google Fonts; fallback fonts work if they are unavailable.
