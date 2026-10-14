# Harshitha Sai Maddukuri — Portfolio

My personal portfolio: projects, experience, and how to reach me.

**Live:** https://YOUR-DOMAIN.vercel.app

It's a static site in a single `index.html` (HTML, CSS, and JavaScript together), with a small Express server for previewing it locally.

## What's on the site
- **Summary** with a quick highlights strip
- **Technical skills**
- **Experience:** IpserLab and Virtusa
- **Projects:** Snippr, Kambaz, Mental Health Detection, Signature Verification, each with a case study you can expand (the problem, how it works, the hard part, the result)
- **Education:** Northeastern University and VVIT
- **Contact:** email, resume, LinkedIn, GitHub
- Light and dark mode, and it works on phones

## Files
| File | What it does |
| --- | --- |
| `index.html` | The whole site |
| `profilepic.jpg` | Optional profile photo. If it's missing, the site shows "HM" initials instead |
| `resume.pdf` | Opened by the resume buttons |
| `server.js`, `package.json` | Local preview server only |
| `vercel.json` | Vercel config (serves every file as static) |

## Run it locally
```bash
npm install      # first time only
npm start        # then open http://localhost:3000
```

## Deploy
The repo is connected to Vercel, so pushing to `main` redeploys the site automatically.

```bash
git add .
git commit -m "Describe what you changed"
git push
```

## Updating
- **Resume:** open download the PDF, and save it here as `resume.pdf`.
- **Photo:** replace `profilepic.jpg`, keeping the same name. A head-and-shoulders crop works best.
- **Text and links:** everything is in `index.html`. Search for the section name (for example `SNIPPR` or `KAMBAZ`) to jump to it.

## Built with
HTML, CSS, and vanilla JavaScript. Fonts: Playfair Display, Outfit, and JetBrains Mono (Google Fonts). Hosted on Vercel.