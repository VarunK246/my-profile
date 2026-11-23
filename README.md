# [Your Name] — Portfolio

A static personal portfolio site: Hero, Skills, Projects, Education, Contact.
Built with plain HTML/CSS/JS, deployed via GitHub Pages, with CI/CD through GitHub Actions.

## 🛠 Before you push

1. Find-and-replace every `[PLACEHOLDER]` in `index.html` with your real content
   (name, bio, projects, education, email, social links).
2. Update the `<title>` and `<meta name="description">` tags in `index.html`.
3. Rename this repo to `yourusername.github.io` (replace `yourusername` with your
   actual GitHub username) — this gives you the clean root URL instead of
   `yourusername.github.io/reponame`.

## 🚀 First-time setup

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin git@github-personal:yourusername/yourusername.github.io.git
git push -u origin main
```

(Swap `github-personal` for whatever SSH host alias you've set up, or use the
plain `git@github.com:...` remote if you're not using multiple SSH identities.)

## ⚙️ Enable GitHub Pages

1. On GitHub, go to your repo → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main` — the workflow in `.github/workflows/deploy.yml` will build
   and deploy automatically. Check the **Actions** tab to watch it run.
4. Your site will be live at `https://yourusername.github.io`.

## 🌐 Adding a custom domain later

1. Buy a domain (Porkbun, Namecheap, etc.).
2. Create a file named `CNAME` (no extension) in the repo root containing just
   your domain, e.g. `www.yourdomain.com`.
3. In your domain registrar's DNS settings, add GitHub Pages' A records for the
   apex domain and a CNAME record for `www` pointing to `yourusername.github.io`.
4. Back in repo **Settings → Pages**, enter your custom domain and enable
   **Enforce HTTPS** once it's verified.

## 📁 Structure

```
.
├── index.html
├── css/style.css
├── js/script.js
├── .github/workflows/deploy.yml
└── README.md
```
