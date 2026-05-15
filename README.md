# Stacy For Fairfax Campaign Website

A modern, responsive campaign website for Stacy R. Hall's Fairfax City Council re-election campaign.

## Features

- **Modern Responsive Design** - Mobile-first, looks great on all devices
- **Fast Loading** - Static HTML/CSS/JS, no frameworks needed
- **Accessible** - WCAG compliant with semantic HTML
- **Easy to Update** - Plain HTML files, no CMS required
- **Free Hosting** - Ready for GitHub Pages, Netlify, or Cloudflare Pages

## Pages

1. **Home** (`index.html`) - Hero, About, Priorities, Accomplishments, Events, Contact
2. **Priorities** (`priorities.html`) - Detailed stances on key issues
3. **About** (`about.html`) - Full biography and background
4. **Accomplishments** (`accomplishments.html`) - Track record and achievements
5. **Get Involved** (`involve.html`) - Volunteer, donate, yard signs
6. **Contact** (`contact.html`) - Contact form and information

## Deployment

### GitHub Pages (Free)
1. Create a new GitHub repository
2. Push this code to the `main` branch
3. Enable GitHub Pages in repository Settings
4. Your site will be live at `username.github.io/repo-name`

### Cloudflare Pages (Free)
1. Go to dash.cloudflare.com
2. Create a Pages project
3. Connect your GitHub repo or upload directly
4. Deploy

### Netlify (Free)
1. Go to netlify.com
2. Drag and drop this folder
3. Your site is live!

## Customization

### Colors
Edit the CSS variables at the top of each HTML file:
```css
:root {
    --navy: #1a365d;
    --gold: #d69e2e;
    --red: #c53030;
    /* etc */
}
```

### Content
All text content is in the HTML files. Simply edit the text between the tags.

### Images
Replace placeholder images by:
1. Adding actual photos to an `images/` folder
2. Updating the `src` attributes in the HTML

## TODO
- [ ] Add actual campaign photos
- [ ] Connect contact form to email service (Formspree, Netlify Forms, etc.)
- [ ] Add Google Analytics
- [ ] Add Facebook Pixel for ads
- [ ] Set up custom domain (stacyforfairfax.com) pointing to new host
- [ ] Add press mentions/news articles
- [ ] Add testimonials from community members

## License
Copyright 2025 Stacy For Fairfax. All rights reserved.