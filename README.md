# Peachology Learning App

A mobile-first, installable web app (PWA) for Peachology learners. It combines practical entrepreneurship courses, lesson progress, a step-by-step business idea builder, and a lightweight community feed.

## Run locally

Serve this folder over HTTPS or through a local web server, then open it on a phone. Use the browser's **Add to Home Screen** action to install it. The app uses plain HTML, CSS, and JavaScript, so no build step or package installation is needed. The service worker caches the core app shell for repeat/offline launches.

## Deploy to Vercel

This is a static site and can be deployed directly from a GitHub repository:

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Leave the framework preset as **Other**, with no build command and the project root as the output directory.
4. Deploy. Vercel serves `index.html` from the project root.

## Prototype notes

- Business Builder fields are saved to the browser's local storage on the final step.
- Course cards, filters, responsive navigation, and community post creation are interactive.
- This front-end prototype does not include accounts, cloud sync, instructor tools, payments, or a back-end database.
