# Git Upload Commands

Run these commands in your terminal from the magazine directory:

## Step 1: Add all files to staging
```bash
git add .
```

## Step 2: Commit your files
```bash
git commit -m "Initial commit: Magazine website"
```

## Step 3: Add your remote repository
Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name:
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

**OR if you want to use SSH:**
```bash
git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO_NAME.git
```

## Step 4: Push to your repository
```bash
git branch -M main
git push -u origin main
```

---

## Quick Copy-Paste Version (replace YOUR_USERNAME and YOUR_REPO_NAME):

```bash
git add .
git commit -m "Initial commit: Magazine website"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

## Notes:
- If your repo already exists on GitHub, make sure it's empty or you'll need to pull first
- If you get authentication errors, you may need to set up GitHub credentials
- For SSH, make sure you have SSH keys configured with GitHub

