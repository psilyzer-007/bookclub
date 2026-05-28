# ବହି Registry — Book Club of Communitie Odisha

A beautiful, searchable member directory for the Book Club of Communitie Odisha.

## Files in this folder

- `index.html` — Home page (hero, stats, quotes, CTA)
- `directory.html` — Searchable member directory (all 42 members, filter by city/genre/language)
- `join.html` — Join page with Project Marginalia form link
- `style.css` — Shared styles used by all pages
- `netlify.toml` — Netlify configuration

---

## How to deploy on Netlify (step by step)

1. **Zip the folder**
   - Select all files inside the `bahi-registry` folder
   - Right-click → Compress / Create ZIP
   - Name it `bahi-registry.zip`

2. **Go to Netlify**
   - Visit [netlify.com](https://netlify.com) and sign up (free)
   - Click **"Add new site"** → **"Deploy manually"**

3. **Drag and drop**
   - Drag your `bahi-registry.zip` onto the deploy box
   - Netlify will give you a live URL like `https://random-name.netlify.app`

4. **Optional: rename your site**
   - In Netlify → Site settings → Site name → Change to something like `bahi-registry`

That's it! Your site is live. 🎉

---

## How to update the member list

1. Open `directory.html` in any text editor (Notepad, TextEdit, VS Code)
2. Find the `const members = [` section (around line 332)
3. Copy an existing member entry and paste it at the end of the list
4. Fill in the new member's details
5. Re-zip and re-deploy to Netlify (same drag-and-drop)

---

## Site pages

| Page | Purpose |
|------|---------|
| `/` or `index.html` | Homepage with hero, stats, member quotes |
| `/directory.html` | Full searchable/filterable directory |
| `/join.html` | Join page → links to Project Marginalia Google Form |
