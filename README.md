# manaksu — Personal Website

## Deploy to Vercel

### Step 1 — Push to GitHub
Create a new GitHub repo called `manaksu` and upload both files:
- index.html
- vercel.json

### Step 2 — Import to Vercel
vercel.com → Add New → Project → Import from GitHub → select `manaksu` → Deploy

No environment variables needed — this is a fully static site.

### Step 3 — Custom domain (optional)
Vercel → Project → Settings → Domains → Add `manaksu.com` or any domain you own.

### To update project links
In index.html find this section near the bottom:
  const links = {
    '01': '#',   ← replace with your MathBoost URL
    '02': '#',   ← replace with your Kerala Fuel Pulse URL
    '03': '#',   ← replace with your DeckTune URL
  };
