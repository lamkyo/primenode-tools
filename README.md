# Deploying PrimeNode Affiliate Tools to GitHub Pages

## 🚀 1-Click Deployment
1. Go to your GitHub repository -> **Settings** -> **Pages**.
2. Under **Build and deployment**:
   * **Source**: Deploy from a branch
   * **Branch**: `main` (or current branch)
   * **Folder**: `/public_web` (or root)
3. Click **Save**.
4. In about 60 seconds, your site will be live at:
   `https://<your-username>.github.io/<repo-name>/public_web/`

## 🛠 Local Preview
To test locally right now:
```bash
python3 scripts/serve_local_calculator.py
```
Then open: `http://localhost:8090`
