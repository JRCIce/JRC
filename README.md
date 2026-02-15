# JRC Ice Plant Website

A static website for JRC Ice Plant, a manufacturer of high-quality ice tubes in Mariveles, Bataan.

## Features

- Responsive design
- About Us section
- Services overview
- Product showcase
- Contact form with Google Sheets integration
- Modern, clean layout

## Files Structure

```
JRC/
├── JRC.html          # Main HTML file
├── style.css         # CSS styling
└── image/            # Image assets
    ├── JRC.png       # Logo
    ├── 5kg.png       # Product images
    ├── 10kg.png
    ├── 15kg.png
    └── 25kg.png
```

## Deployment to Vercel

### Method 1: Drag and Drop (Easiest)

1. Go to [vercel.com](https://vercel.com)
2. Sign up for a free account
3. Once logged in, drag your entire `JRC` folder to the Vercel dashboard
4. Your site will be deployed automatically
5. You'll get a URL like `your-site-name.vercel.app`

### Method 2: Connect GitHub Repository (Recommended)

1. Create a GitHub repository
2. Upload all your JRC files to the repository
3. Go to Vercel and click "New Project"
4. Connect your GitHub account
5. Select your repository
6. Configure build settings (no build command needed for static sites)
7. Deploy! Vercel will automatically deploy when you push to GitHub

### Method 3: Vercel CLI

1. Install Vercel CLI: `npm install -g vercel`
2. Navigate to your JRC folder in terminal
3. Run: `vercel`
4. Follow the prompts to deploy

## Custom Domain

After deployment, you can:
- Use the provided Netlify subdomain
- Connect a custom domain (if you have one)
- Set up HTTPS (automatically enabled)

## Contact Form

The contact form is integrated with Google Sheets for lead collection. Make sure the Google Apps Script URL in the HTML file is correctly configured.

## Support

For any issues or questions about the website, please contact the developer.