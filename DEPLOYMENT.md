# Deploying with GitHub Pages

This project is a plain static website. It does not need Node.js, npm, a framework, a database, or a build workflow.

## Option A: Upload using the GitHub website

1. Sign in to GitHub and create a new repository.
2. Extract the provided ZIP file.
3. Upload **the files inside** the `philosophy-quest-github` folder to the repository root. Make sure `index.html` is at the top level, not inside a second nested folder.
4. Commit the uploaded files.
5. Open the repository's **Settings**.
6. Select **Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select the `main` branch and `/ (root)` folder, then save.
9. Wait for GitHub to finish publishing. The Pages screen will show the site's URL.

Typical address:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Option B: Upload using Git

Create an empty GitHub repository first, then run these commands inside the extracted project folder. Replace the sample URL with your repository URL.

```bash
git init
git add .
git commit -m "Publish Philosophy Quest"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Then enable GitHub Pages using steps 5–9 above.

## Updating the site

Replace or edit the affected files, commit the changes, and push to `main`. GitHub Pages will redeploy automatically. Browser caches may briefly show the older version; refresh the page or reopen it after deployment finishes.

## Troubleshooting

- **404 page:** Confirm that `index.html` is in the published root and that Pages points to `main` and `/ (root)`.
- **Pages option unavailable:** Check repository permissions and the GitHub plan or organization policy.
- **Old version still appears:** Wait for deployment to complete, then hard-refresh or clear the site's browser cache.
- **Student progress is missing:** Progress stays in the specific browser/device where it was created. It does not synchronize through GitHub.
- **Certificate does not download as expected:** Use the certificate's Print/Save as PDF option, and allow downloads or pop-ups if the browser requests permission.

Official reference: [Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
