# Ayushi Portfolio - Go Live Steps

## 1. Open locally

Open `index.html` in your browser.

Before sharing the site, add:

- `assets/ayushi.jpg`
- `assets/Ayushi-Resume.pdf`

Then edit these placeholders in `index.html`:

- LinkedIn URL
- Email address
- Writing URL, if available

## 2. Put the project in GitHub

Open Terminal inside the `ayushi-portfolio` folder and run:

```bash
git init
git add .
git commit -m "Initial Ayushi portfolio"
git branch -M main
```

Create a new empty repository on GitHub. Do not add a README from GitHub, because this project already has files.

Then connect your local folder to GitHub:

```bash
git remote add origin https://github.com/YOUR-USERNAME/ayushi-portfolio.git
git push -u origin main
```

## 3. Deploy on Vercel

1. Go to `https://vercel.com`.
2. Sign in with GitHub.
3. Click `Add New...` then `Project`.
4. Import the `ayushi-portfolio` repository.
5. Keep framework preset as `Other` or `No Framework`.
6. Leave build command empty.
7. Leave output directory empty.
8. Click `Deploy`.

Vercel will create a live URL. Every time you push to `main`, Vercel will deploy the newest version.

## 4. Update later

After editing files:

```bash
git add .
git commit -m "Update portfolio"
git push
```
