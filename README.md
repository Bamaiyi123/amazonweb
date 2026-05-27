# DealHub

A simple static affiliate deals website built with HTML and CSS.

## Files

- `index.html` - main landing page with category links and product cards.
- `phones.html` - Amazon phone search shortcut page.
- `laptops.html` - Amazon laptop search shortcut page.
- `fashion.html` - Amazon fashion search shortcut page.
- `electronics.html` - Amazon electronics search shortcut page.
- `about.html` - about page.
- `contact.html` - contact page.
- `privacy-policy.html` - privacy policy page.
- `affiliate-disclosure.html` - affiliate disclosure page.

## How it works

- The category buttons on `index.html` now point to dedicated pages for `Phones`, `Laptops`, `Fashion`, and `Electronics`.
- Each category page contains direct Amazon search links and a `Home` link back to the main page.
- The site is fully static and does not require a build step.

## Local preview

Open `index.html` directly in your browser, or run a local server from the folder:

```powershell
cd "C:\Users\DELL\OneDrive\Desktop\My website"
python -m http.server 8000
```

Then visit:

```
http://localhost:8000
```

## Deployment

This static site can be hosted on platforms like Render, Netlify, Vercel, or GitHub Pages.

### Render

1. Push the site folder to a Git repository.
2. Create a new `Static Site` on Render.
3. Connect your repo and choose the branch.
4. Set publish directory to `/`.

## Notes

- The `Home` category was removed from the navigation.
- This project uses direct Amazon URLs for product pages.
