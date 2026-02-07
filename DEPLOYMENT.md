# GitHub Pages Deployment Instructions

Follow these steps to deploy your Monty Hall app to GitHub Pages:

## Step 1: Create a New Repository on GitHub

1. Go to https://github.com and log in
2. Click the "+" icon in the top right, then "New repository"
3. Repository name: `monty-hall-app` (or any name you prefer)
4. Description: "Interactive Monty Hall Problem demonstration"
5. Make it **Public** (required for free GitHub Pages)
6. **DO NOT** check "Add a README file" (we already have one)
7. Click "Create repository"

## Step 2: Upload Files to GitHub

You have two options:

### Option A: Using GitHub Web Interface (Easiest)

1. On your new repository page, click "uploading an existing file"
2. Drag and drop these three files:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. Scroll down and click "Commit changes"

### Option B: Using Git Command Line

If you have Git installed, run these commands in your terminal:

```bash
cd /path/to/monty-hall-app
git init
git add .
git commit -m "Initial commit: Monty Hall problem app"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/monty-hall-app.git
git push -u origin main
```

(Replace YOUR-USERNAME with your GitHub username)

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and "/root", then click "Save"
6. Wait 1-2 minutes for deployment

## Step 4: Access Your App

Your app will be live at:

```
https://YOUR-USERNAME.github.io/monty-hall-app/
```

(Replace YOUR-USERNAME with your actual GitHub username)

## Troubleshooting

- **404 Error**: Wait a few more minutes, GitHub Pages can take 5-10 minutes initially
- **Repository not found**: Make sure your repository is public
- **Page not updating**: After making changes, it can take 1-2 minutes to reflect

## Updating Your App

To update the app later:
1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make your changes
5. Click "Commit changes"
6. Wait 1-2 minutes for the changes to appear on your live site

---

**Need help?** The files are ready in the `monty-hall-app` folder!
