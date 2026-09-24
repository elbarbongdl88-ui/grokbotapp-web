# Grokbotapp (public static)

Production host: Railway Caddy.

- Live: https://grokbotapp.up.railway.app/
- Source: https://github.com/elbarbongdl88-ui/grokbotapp-web
- App contract repo: https://github.com/elbarbongdl88-ui/grokbotapp

## Deploy paths

1. **Railway (live production)**  
   Push to `main` on this repository. Service `grokbotapp` in project `grokbotapp` uses `Caddyfile` and `railway.json`.

2. **GitHub Pages (free public mirror)**  
   `.github/workflows/pages.yml` enables Pages from Actions and publishes the repository root.  
   Expected URL after a green run: https://elbarbongdl88-ui.github.io/grokbotapp-web/

Vercel team billing is blocked (HTTP 402). Do not add a Vercel token workflow.
