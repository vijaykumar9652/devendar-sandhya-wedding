# Devendar & Sandhya Wedding Website

Simple static wedding invitation website (HTML/CSS/JS), ready to deploy on GitHub Pages.

## Local Project Path

`/Users/vijaybanoth/Downloads/test/devender-sandhya-wedding-main`

## Deploy to GitHub Pages

1. Create a new repository in GitHub.
2. Push this project to the `main` branch:

```bash
cd /Users/vijaybanoth/Downloads/test/devender-sandhya-wedding-main
git init
git add .
git commit -m "Initial wedding website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

3. In GitHub, open the repo and go to `Settings` -> `Pages`.
4. Under `Build and deployment`:
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`
5. Click `Save`.

After deployment, your site URL will be:

`https://<your-username>.github.io/<repo-name>/`

## Notes

- Keep `index.html` in the repository root.
- If you want URL as `https://<your-username>.github.io/`, the repo name must be `<your-username>.github.io`.
