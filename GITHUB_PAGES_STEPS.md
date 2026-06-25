# GitHub Pages Steps

From inside `PUBLIC_REPO_READY/`:

```powershell
git init
git add .
git commit -m "Publish transnational transfer KG demo"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/transnational-transfer-kg.git
git push -u origin main
```

Then on GitHub:

1. Open the repository.
2. Go to Settings → Pages.
3. Choose “Deploy from a branch.”
4. Branch: `main`.
5. Folder: `/docs`.
6. Save.

The public site should appear at:

```text
https://YOUR-USERNAME.github.io/transnational-transfer-kg/
```
