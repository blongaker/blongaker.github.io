# Grad School Site

Barebones academic homepage: `index.html` + `style.css`. No build step, no dependencies.

## Edit content
`index.html` is a blank template (academicpages/Minimal-Mistakes-inspired layout: sidebar photo + nav + content sections).
Fill in all the empty tags with your own text. Colors/spacing live at the top of `style.css` under `:root`.

## Add your photo
1. Save a professional headshot as `photo.jpg` (square photos crop best) into the `images/` folder.
2. It's already referenced in `index.html` as `<img class="avatar" src="images/photo.jpg">` — just replace the file.
3. To use a different filename or format (`.png`, `.webp`), update the `src` attribute to match.

## Add a CV
Drop a `cv.pdf` file in the repo root — it's already linked in the CV section.

## Host on GitHub Pages

1. Create a new GitHub repo (e.g. `yourusername.github.io` for a root URL, or any name like `grad-site` for a project page).
2. Push these files to the repo:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/yourusername/REPO_NAME.git
   git push -u origin main
   ```
3. In the repo on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, then pick branch `main`, folder `/ (root)`. Save.
4. Your site goes live at:
   - `https://yourusername.github.io/` (if repo is named `yourusername.github.io`)
   - `https://yourusername.github.io/REPO_NAME/` (otherwise)

It can take a minute or two after each push for changes to appear.

## Optional: custom domain
Add a `CNAME` file containing your domain (e.g. `yourname.com`) to the repo root, and point your domain's DNS at GitHub Pages per [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
