ODPAD-NIK - ready project for GitHub + Netlify

Structure:

- index.html (root)                -> main page
- assets/css/style.css             -> styles
- assets/images/logo-placeholder.png -> logo
- admin/index.html                 -> Netlify CMS admin loader
- admin/config.yml                 -> Netlify CMS config (git-gateway, media in static/uploads)
- posts/testovaci-clanok.md       -> sample post
- static/uploads/                 -> uploads (images will be stored here by CMS)

HOW TO DEPLOY (quick):
1. Create GitHub repo 'odpadnik-blog' (public) and push the content of this ZIP to repo root.
2. In Netlify, create new site from Git -> pick this GitHub repo -> Branch: main, Publish directory: .
3. In Netlify site settings -> Identity -> Enable Identity -> Services -> Enable Git Gateway.
4. Invite your email to Identity or use 'Log in with GitHub' on /admin.
5. After deploy, open https://<your-site>.netlify.app/admin to login and create posts. Images uploaded via CMS go to /static/uploads.

If you need help pushing to GitHub via web UI, upload all files from the ZIP's root (select all and drag into GitHub upload page).
