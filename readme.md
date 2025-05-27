# HYBRIDIOT Vehicle Questionnaire

A modern, interactive questionnaire to help users find the most efficient vehicle for their lifestyle.

## Files Overview

- `index.html` - Main questionnaire page with React components
- `package.json` - Project configuration and dependencies
- `netlify.toml` - Netlify deployment and form handling configuration
- `README.md` - This file

## Features

- 📱 **Mobile-responsive design**
- 🎨 **Clean, modern UI** with HYBRIDIOT brand colors
- 📊 **Multi-step questionnaire** with progress tracking
- 📧 **Automatic email notifications** to forms@hybridiot.com
- 🚀 **Zero-config deployment** on Netlify

## How It Works

1. Users complete the questionnaire step-by-step
2. Form submissions are automatically handled by Netlify Forms
3. Email notifications are sent to forms@hybridiot.com
4. All data is collected for analysis and personalized recommendations

## Deployment Instructions

### Step 1: Upload to GitHub
1. Create a new repository on GitHub
2. Upload all these files to your repository

### Step 2: Deploy on Netlify
1. Go to [netlify.com](https://netlify.com) and sign up
2. Click "New site from Git"
3. Connect your GitHub account
4. Select your repository
5. Deploy settings should auto-configure from netlify.toml
6. Click "Deploy site"

### Step 3: Custom Domain (Optional)
1. In Netlify dashboard, go to Site settings > Domain management
2. Add your custom domain (e.g., questionnaire.hybridiot.com)
3. Follow Netlify's instructions to update your DNS

## Form Data

All form submissions will be:
- Stored in your Netlify dashboard under "Forms"
- Automatically emailed to forms@hybridiot.com
- Available for export as CSV

## Customization

### Logo
Replace the placeholder logo URL in `index.html`:
```html
<img src="your-logo-url-here" alt="HYBRIDIOT Logo" className="h-16 w-auto" />
```

### Colors
The questionnaire uses:
- **Dark Teal**: `teal-800` for primary text and headings
- **Orange**: `orange-500` for accents and CTAs
- **Light Teal**: `teal-50` for hover states

### Content
Modify the questions and options directly in the `steps` array within `index.html`.

## Tech Stack

- **React 18** - UI framework
- **Tailwind CSS** - Styling
- **Netlify Forms** - Form handling
- **Lucide Icons** - Icon library

## Support

For questions about deployment or customization, refer to:
- [Netlify Forms Documentation](https://docs.netlify.com/forms/setup/)
- [Netlify Deployment Guide](https://docs.netlify.com/site-deploys/create-deploys/)
