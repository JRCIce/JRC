# GitHub Setup Guide for JRC Website

## Step-by-Step Instructions to Host on GitHub

### 1. Create a GitHub Account
- Go to [github.com](https://github.com)
- Click "Sign up" and follow the registration process
- Verify your email address

### 2. Create a New Repository
1. Log in to GitHub
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Repository name: `jrc-ice-plant` (or any name you prefer)
5. Description: "JRC Ice Plant Website - Ice tube manufacturer in Mariveles, Bataan"
6. Choose "Public" (free hosting)
7. Check "Add a README file"
8. Click "Create repository"

### 3. Upload Your Files
You have two options:

#### Option A: Web Upload (Easiest)
1. In your new repository, click "uploading an existing file"
2. Drag and drop these files:
   - JRC.html
   - style.css
   - README.md
   - GITHUB_SETUP.md (this file)
3. For the image folder:
   - Click "uploading an existing file" again
   - Create a folder named `image`
   - Upload all image files: JRC.png, 5kg.png, 10kg.png, 15kg.png, 25kg.png, etc.
4. Add a commit message: "Initial commit - JRC website files"
5. Click "Commit changes"

#### Option B: Command Line (Advanced)
```bash
# Navigate to your JRC folder
cd path/to/your/JRC

# Initialize git
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit - JRC website files"

# Add remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/jrc-ice-plant.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "main branch"
5. Click "Save"
6. Your site will be live at: `https://YOUR_USERNAME.github.io/jrc-ice-plant`

### 5. Verify Deployment
- Wait a few minutes for GitHub Pages to build
- Visit your site URL to see it live
- Test all functionality (navigation, contact form, etc.)

## Repository Structure
Your GitHub repository should look like this:
```
jrc-ice-plant/
├── JRC.html
├── style.css
├── README.md
├── GITHUB_SETUP.md
└── image/
    ├── JRC.png
    ├── 5kg.png
    ├── 10kg.png
    ├── 15kg.png
    └── 25kg.png
```

## Next Steps
- Share your live website URL with customers
- Consider setting up a custom domain
- Monitor your site's performance
- Update content as needed

## Troubleshooting
- If GitHub Pages doesn't activate, ensure you have a valid HTML file
- Check that all image paths are correct
- Make sure your repository is public for free GitHub Pages hosting

Need help? Contact support or refer to GitHub's documentation.