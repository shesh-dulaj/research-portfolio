WATER PURIFICATION: RESEARCH PORTFOLIO WEBSITE
===========================================================================

Plain HTML + CSS (no JavaScript), as required by the course web.
Pages: index, domain, milestones, documents, presentations, about, contact (+ thanks).

STILL TO FILL IN (highlighted in coral on the pages)
- Names and student IDs of the four members (about.html, domain.html)
- Supervisor and co-supervisor details (about.html, footer)
- Programme and research ID (index.html)
- Literature review findings and references (domain.html)
- Novelty of each component (domain.html)
- Achievements (about.html)
- Documents, presentations and system demo, copied into the files/ folder (see files/README.txt)

HOW THE CONTACT FORM SENDS REAL EMAIL
The form on contact.html posts to FormSubmit (formsubmit.co), a free service that
forwards each message to dinidu2001dananjaya@gmail.com.

1. The research team email is already set to dinidu2001dananjaya@gmail.com
   in contact.html and in every page footer. To change it later, replace that
   address in those places.
2. Upload the site to the course web. The form does NOT work when contact.html is
   opened from your computer as a file; it needs a web address (http or https).
3. Open contact.html on the live site, fill in the form and press Send message.
   FormSubmit sends ONE activation email to that address. Open it and click
   "Activate Form". This is needed only once.
4. Send a second test message. It should arrive in the inbox (check spam).

ABOUT THE VIEW AND DOWNLOAD BUTTONS
- Download only forces a file download when the site is opened through a web address
  (the course web, or a local server). If you double-click an HTML file on your computer,
  the browser opens PDFs in a tab instead of downloading them. This is a browser rule.
  To test downloads on your computer, run "python -m http.server 8000" inside this folder
  and open http://localhost:8000/documents.html
- Slides cannot be shown inside a browser, so the View button on the Presentations page
  opens a PDF copy of each deck. Export each .pptx to PDF (File > Save as > PDF) and save
  it in files/ with the same name and a .pdf ending.
- The whole site must stay under 20 MB (course web limit).

Optional: to send visitors to your own confirmation page (thanks.html) after
sending, add this line inside the form in contact.html, using your real address:
  <input type="hidden" name="_next" value="https://YOUR-SITE/thanks.html">
Without it, FormSubmit shows its own confirmation page.
