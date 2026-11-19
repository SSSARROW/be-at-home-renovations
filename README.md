# BE at Home Renovations website

Single-page marketing site for BE at Home Renovations, a handyman and renovation business serving the Charlotte, NC metro.

## Structure

- `index.html`: the whole site (HTML, CSS and JavaScript inline)
- `firebase.json`: Firebase Hosting configuration

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 5507
```

## Deploy

```
npx firebase-tools deploy --only hosting
```

## Before launch

- Project photos currently load from the business's Google Maps listing. Download them into the repo and update the image URLs so they don't break.
- The estimate form opens a pre-filled text message. Connect it to a form backend (Formspree, Netlify Forms or a CRM) to capture leads automatically.
