# Nandhini Kaliappan — Portfolio

A static one-page portfolio site built with plain HTML/CSS.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `nandhini-portfolio`).
2. Push these files to the repo's `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then **Save**.
6. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Local preview

Just open `index.html` in a browser, or serve it locally:
```bash
npx serve .
```
