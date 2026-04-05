# Brazen Recruits — Link Hub Setup Guide

## What's in this folder

- `index.html` — The link hub page (all links in one place)
- `recruiter-photo.jpeg` — Kara's profile photo
- `qr-code-brazenrecruits-hub.png` — QR code pointing to brazenrecruits-hub.netlify.app
- `SETUP-INSTRUCTIONS.md` — This file

---

## STEP 1: Deploy to Netlify (2 minutes)

1. Log into **https://app.netlify.com**
2. Click **"Add new site" → "Deploy manually"**
3. Drag and drop the entire `brazen-recruits-hub` folder
4. Netlify will assign a random name — go to **Site Configuration → Site name**
5. Change it to **brazenrecruits-hub** (so the URL becomes brazenrecruits-hub.netlify.app)

That's it. No environment variables, no serverless functions — it's just a static page.

---

## STEP 2: Print the QR Code

The `qr-code-brazenrecruits-hub.png` file points to **https://brazenrecruits-hub.netlify.app**.

Use this on:
- Business cards
- Flyers and posters
- Booth materials
- Instagram story highlights

### Important note about QR codes and business cards

The QR code points to the **URL**, not the page content. As long as the site stays at `brazenrecruits-hub.netlify.app`, you can redesign the page as many times as you want without reprinting cards. The only thing that would require a reprint is changing the site's URL.

---

## PAGES SUMMARY (all three sites)

| URL | Purpose |
|---|---|
| brazenrecruits-hub.netlify.app | **Link hub** (QR code destination) |
| brazenrecruits.netlify.app | Lead capture / "Connect with me" form |
| brazenrecruits-survey.netlify.app | Qualification survey |
| brazenrecruits-survey.netlify.app/faq.html | "3 Things You Didn't Know" page |
| brazenrecruits-survey.netlify.app/refer.html | Referral link generator |

---

## OPTIONAL: Custom Domain Later

If Kara ever wants a custom domain (like brazenrecruits.com):

1. Buy the domain from Namecheap, Google Domains, etc. (~$10-15/year)
2. In Netlify: **Site Configuration → Domain management → Add custom domain**
3. Follow Netlify's DNS instructions
4. The QR code would need to be regenerated to point to the new domain
5. BUT — you can set up a redirect from the old .netlify.app URL to the new domain, so existing printed QR codes still work
