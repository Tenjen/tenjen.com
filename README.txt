TENJEN MOKTAN — WEBSITE
========================

This is a static, responsive personal-profile website designed for:
https://tenjen.com.np

FILES
-----
index.html     Main website
style.css      Responsive design
script.js      Mobile navigation + year + active section
assets/        Favicon and assets

CLOUDFLARE PAGES — DIRECT UPLOAD
--------------------------------
1. Log in to Cloudflare.
2. Open Workers & Pages.
3. Create application > Get started > Drag and drop your files.
4. Use project name: tenjen
5. Upload the contents of this folder (or the ZIP).
6. Deploy.
7. Open the project > Custom domains > Set up a domain.
8. Enter: tenjen.com.np
9. Activate the domain.

The website is static, so it does not require WordPress, PHP or MySQL.

IMPORTANT CUSTOMIZATION
-----------------------
- Replace the portrait placeholder in index.html with your own professional photo if desired.
- Change hello@tenjen.com.np if you use another email address.
- Add your real social links in the footer/contact section if desired.
- Review all biography/project wording before publishing.

CONTACT FORM
------------
The current form uses a mailto link and opens the visitor's email application.
For a server-side form later, use a form service or a Cloudflare Worker/Pages Function.

DOMAIN
------
Cloudflare Pages supports custom domains. For an apex domain such as tenjen.com.np,
the domain must be a Cloudflare zone with the appropriate nameservers.
