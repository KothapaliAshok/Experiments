# Deploy IPL Predictor to Streamlit Community Cloud

## What's done

- Removed local-only files: `run_app.bat`, `.vscode/settings.json`
- Added `.gitignore` so `venv/` and other local files are not committed
- Git repo initialized with `app.py`, `ipl_data.csv`, `requirements.txt`

---

## Step 1: Create GitHub repository

1. Go to **https://github.com/new**
2. Set **Repository name** (e.g. `ipl-predictor`)
3. Choose **Public**
4. Do **not** add README, .gitignore, or license
5. Click **Create repository**

---

## Step 2: Push your code

In a terminal from `d:\Mark\Research\Experiments`:

```powershell
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repository name.

---

## Step 3: Deploy on Streamlit Cloud

1. Open **https://share.streamlit.io**
2. Sign in with GitHub
3. Click **New app**
4. Set:
   - **Repository:** `YOUR_USERNAME/YOUR_REPO_NAME`
   - **Branch:** `main`
   - **Main file path:** `app.py`
5. Click **Deploy**

Your app will be available at something like: `https://ipl-predictor-xxx.streamlit.app`
