# Priyanka Savjani — Portfolio

A single-page portfolio for a self-taught technical investor, showcasing three
AI tools built to source and evaluate early-stage AI companies.

## The tools featured

1. **[AI Capital Flows](https://aicapitalflows.com)** — a dashboard tracking
   early-stage AI investment across Europe and the US, refreshing daily at 7am.
2. **[LLM Chatbot from scratch](https://pri-chatbot.onrender.com)** — a language
   model built from the ground up to understand LLM architecture first-hand.
3. **[Logo Velocity Tracker](https://logogrowth.onrender.com/)** — a monthly
   scan of startup websites measuring customer-logo growth as an adoption proxy.

## Stack

Plain, dependency-free static site — HTML, CSS, and a little vanilla JavaScript.
Nothing to build; it runs anywhere.

- `index.html` — page content and structure
- `styles.css` — design system, light/dark theming, responsive layout
- `script.js` — theme toggle, scroll reveals, nav behavior

## Running locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

Any static host works (GitHub Pages, Netlify, Vercel, Render). No build step,
no environment variables.

### GitHub Pages
Push to your default branch and enable Pages (Settings → Pages → deploy from
branch, root). The site is served as-is.
