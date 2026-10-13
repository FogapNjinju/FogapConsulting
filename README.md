# Fogap Consulting Ltd Website

This is a static website for Fogap Consulting Ltd, built as a polished marketing site with a services, outcomes, and careers focus.

## Structure

- `index.html` — homepage and main brand entry point
- `about.html` — about Fogap Consulting and company values
- `services.html` — combined services, delivery model, and process content
- `outcomes.html` — delivery examples, clinical outputs, and quality practices
- `experience.html` — team capability and relevant work experience
- `careers.html` — current hiring and recruitment information
- `contact.html` — contact details and enquiry CTA
- `process.html` — legacy redirect page to `services.html`
- `testimonials.html` — legacy redirect page to `outcomes.html`
- `assets/css/styles.css` — core styling for the site
- `assets/js/script.js` — mobile navigation toggle script
- `assets/clinical-lab.jpg` — locally hosted homepage image

## Usage

Open `index.html` in a web browser to preview the site.

The site is fully static and can be published from the repository root with GitHub Pages; it requires no build step or server-side service. The contact form prepares an email in the visitor's mail app, so it does not require a form backend.

If you want to run it locally with a simple server:

```powershell
cd C:\Users\User\FogapConsultingSite
python -m http.server 8000
```

Then visit `http://localhost:8000`.
