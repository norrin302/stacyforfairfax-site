# Stacy For Fairfax Campaign Website - Project Notes

## Overview
Built a complete, modern campaign website for Stacy R. Hall's Fairfax City Council re-election campaign (Nov 4, 2025). The original site on GoDaddy had limited design capabilities, so we built a new site elsewhere that can be launched without touching the existing domain.

**Election:** November 4, 2025

## Original Site
- URL: www.stacyforfairfax.com (GoDaddy)
- Built with: GoDaddy's site builder tools (limited flexibility)
- Plan: Keep original live until new site is ready, then point domain

## New Site Location
`~/stacyforfairfax-site/` (on WSL/Linux side)

### Files
| File | Description |
|------|-------------|
| `index.html` | Main landing page - hero, about, priorities, accomplishments, events, contact |
| `about.html` | Full biography with timeline, values section, family life |
| `priorities.html` | Detailed issue positions (public safety, environment, fiscal, schools, housing, walkability) |
| `accomplishments.html` | Track record with stats, governance approach, achievements |
| `contact.html` | Contact form with topic dropdown, volunteer/donate sections |
| `README.md` | Deployment instructions for hosting |

## Design Specs
- **Colors:** Navy (#1a365d), Gold (#d69e2e), Red accent (#c53030)
- **Fonts:** Playfair Display (headings), Source Sans 3 (body) via Google Fonts
- **Icons:** Font Awesome 6.5.1 (CDN)
- **Layout:** Mobile-first responsive, CSS Grid/Flexbox
- **Animations:** Scroll fade-ins, hover effects, smooth scrolling

## Features
- [x] Election countdown timer (to Nov 4, 2025)
- [x] Responsive navigation with mobile hamburger menu
- [x] Priority cards with icons
- [x] Accomplishments section with stats
- [x] Contact form (UI only - needs backend)
- [x] Social media links (placeholders)
- [x] Event placeholder cards
- [x] Volunteer/donate call-to-action sections
- [x] Scroll animations (fade-in on scroll)
- [x] Sticky navigation with blur effect

## TODO / Outstanding Items
- [ ] Add real campaign photos (currently using icon placeholders)
- [ ] Connect contact form to email service (Formspree recommended - free)
- [ ] Update social media links with actual URLs
- [ ] Add specific event dates/times when known
- [ ] Add Google Analytics tracking code
- [ ] Add Facebook Pixel for ad tracking (if running ads)
- [ ] Add press mentions / endorsements section
- [ ] Add testimonials from community members
- [ ] Set up hosting (GitHub Pages, Cloudflare Pages, or Netlify)
- [ ] Point stacyforfairfax.com domain to new hosting

## Hosting Options (All Free)

### GitHub Pages
1. Create github.com account
2. Create repository `stacyforfairfax`
3. Upload files to main branch
4. Enable Pages in Settings
5. URL: `username.github.io/stacyforfairfax`

### Cloudflare Pages (Recommended)
1. Go to pages.cloudflare.com
2. Create project → upload files or connect GitHub
3. Custom domain support included
4. Fast global CDN

### Netlify
1. Go to netlify.com
2. Drag and drop the folder
3. Gets you: netlify.com/stacyforfairfax

## Contact Form Setup (Formspree)
1. Go to formspree.io and create free account
2. Create new form for Stacy's campaign
3. Get your form endpoint URL
4. Replace the form action in contact.html:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Content Notes from Original Site

### Stacy's Background
- Daughter of small business owners (bagel/bakery) in Wilmington, DE
- Mom was public high school teacher
- University of Delaware - B.S. Finance, minors in Economics and Biology
- Moved to DC area 2001, Fairfax since 2011
- Married with two sons (FHS football/basketball), two dogs
- Controller for animal health company
- Former 9-year public accountant
- Runs own accounting/bookkeeping/tax business in city
- Kids attended: Providence Elementary, Katherine Johnson Middle, Fairfax High (and Academy)

### Key Issues/Positions
1. **Public Safety** - Fully staff police, address rising crime, help homeless
2. **Environment** - Preserve green spaces, restrict gas-powered leaf blowers, promote renewables
3. **Fiscal Responsibility** - Transparency in budget/taxes, needs vs wants
4. **Transparency** - Open communication, community engagement, resident voice
5. **Schools** - Support FCPS, feasibility study on running own system
6. **Housing** - Affordability, options for teachers/first responders
7. **Walkability** - Bike/ped paths, well-lit maintained areas, scooters

### Original Site Pages
- Home & Contact (with contact form)
- Priorities
- Background
- The Rumor Mill
- Accomplishments

## Next Steps for Russ/Dev
1. Choose hosting platform
2. Set up GitHub/Cloudflare/Netlify account
3. Deploy files
4. Set up Formspree for contact form
5. Update social links
6. Add real photos
7. Point GoDaddy DNS to new host (when ready)

## File Structure
```
stacyforfairfax-site/
├── README.md
├── index.html
├── about.html
├── priorities.html
├── accomplishments.html
├── contact.html
└── PROJECT_NOTES.md (this file)
```

---
*Last Updated: May 14, 2026*
*Built by: Hermes AI Agent*
*For: Stacy R. Hall City Council Campaign 2025*