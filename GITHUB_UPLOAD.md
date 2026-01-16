# How to Upload to GitHub

Follow these steps to push your CS Fashion Shop project to GitHub:

## Step 1: Initialize Git Repository (if not already done)

```bash
git init
```

## Step 2: Add All Files

```bash
git add .
```

## Step 3: Create Initial Commit

```bash
git commit -m "Initial commit: CS Fashion Shop website"
```

## Step 4: Create a New Repository on GitHub

1. Go to [github.com](https://github.com)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it `CS-Fashion-Shop` (or your preferred name)
5. Add description: "A modern, responsive fashion e-commerce website"
6. Choose "Public" or "Private"
7. Click "Create repository"

## Step 5: Add Remote Repository

Replace `YOUR_USERNAME` with your GitHub username:

```bash
git remote add origin https://github.com/YOUR_USERNAME/CS-Fashion-Shop.git
```

## Step 6: Push to GitHub

```bash
git branch -M main
git push -u origin main
```

## Step 7: Enable GitHub Pages (Optional - to host your website)

1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to "Pages" section
4. Under "Branch", select `main` and folder `/root`
5. Click "Save"
6. Your website will be available at: `https://YOUR_USERNAME.github.io/CS-Fashion-Shop/`

## Common Issues and Solutions

### Issue: "fatal: not a git repository"

**Solution:** Make sure you're in the project folder and run `git init`

### Issue: "authentication failed"

**Solution:**

- Use personal access token instead of password
- Or configure SSH keys on GitHub

### Issue: Path errors on GitHub Pages

**Ensure:**

- All relative paths use forward slashes `/`
- No spaces in folder names (use hyphens instead)
- Images are referenced correctly with `./` for same folder

## Verify Everything Works

1. Clone from GitHub locally to test:

```bash
git clone https://github.com/YOUR_USERNAME/CS-Fashion-Shop.git
```

2. Open `index.html` in a browser
3. Test navigation and all links
4. Check that images load correctly

## Troubleshooting Path Issues

If you see 404 errors on GitHub Pages:

1. Check file names are case-sensitive
2. Avoid spaces in paths - use `About%20Us` in URLs
3. Ensure all image paths are correct
4. Check that background images exist in the correct folders

## Update Your Repository

To push future changes:

```bash
git add .
git commit -m "Your commit message here"
git push
```

Good luck! 🚀
