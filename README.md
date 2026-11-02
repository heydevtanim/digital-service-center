# Digital Service Center — static website

HTML/CSS/JS only (no build step). 19 categories, all services in `data.js`.

## Edit
- `config.js` — name, phone, WhatsApp (e.g. 8801XXXXXXXXX), email, address
- `data.js` — add/remove services (`Name~min-max`, separated by `|`)

## Deploy
```bash
git init && git add . && git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<you>/<repo>.git
git push -u origin main
```
Vercel → Add New Project → import the repo → Framework Preset: **Other** → Deploy (leave build/output empty).
