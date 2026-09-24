# Ezbiz - Angular Corporate Website

A responsive 5-page demo website for a technology consultancy serving cooperative societies (koperasi), insurance and financial services.

## Pages
- Home
- About
- Services
- Solutions
- Contact

## Local setup
Requirements: Node.js 20+ and npm.

```bash
npm install
npm start
```

Open: http://localhost:4200

## Production build
```bash
npm run build
```

The production files will be generated under `dist/corporate-site/browser` and can be hosted on AWS S3/CloudFront, Azure Static Web Apps, Nginx, IIS, or other static hosting.

## Before production
- Replace the demo company name `Ezbiz` with your actual company name.
- Replace demo email/phone/contact details.
- Add your official logo and favicon.
- Connect the Contact form to your Node.js API, email provider or CRM.
- Add privacy/PDPA and terms pages as required.
