# Khedni Maak! · shared links

Published at **https://khednimaak.github.io** (GitHub Pages, organization `khednimaak`).

Public "open in the app" pages for links shared from the **Khedni Maak!** app (USJ carpooling).
The app's code lives in a separate private repository.

- `u/?id=<user id>`: opens a public profile in the app ("Share my profile").
- Phase 6 "Share my trip" will reuse the same page.
- No personal data is stored or shown here: only the logo, a short line in English, French and
  Arabic, and an "Open in Khedni Maak!" button.
- `config.json` says where the app is: the Expo development server (`exp://<laptop>:8081/--`)
  during development, `khednimaak:/` in the real app. Updated with `npm run links:dev` from the
  app repo.
- `og.png` is the link preview card (built with `npm run links:og` in the app repo).
