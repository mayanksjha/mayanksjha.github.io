GitHub Pages deployment

1. Create a new public GitHub repository.
2. Upload all files from this folder to the root of the repository.
3. In GitHub: Settings -> Pages.
4. Under Build and deployment, choose: Deploy from a branch.
5. Select Branch: main and Folder: /(root), then Save.
6. Wait a minute or two.
7. Your site will appear at:
   https://<your-github-username>.github.io/<repository-name>/

Notes:
- The .nojekyll file prevents GitHub Pages from applying Jekyll processing.
- If you want the site at https://<your-github-username>.github.io/ exactly,
  name the repository: <your-github-username>.github.io
