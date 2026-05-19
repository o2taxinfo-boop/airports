# O2Taxi Airport Transfers — airport.o2taxi.com

Full static website for O2Taxi's airport transfer service, optimised for local SEO across Thame and South Oxfordshire.

## Pages included

### Core pages
- `index.html` — Homepage (airport.o2taxi.com)
- `pages/prices.html` — Guide price table
- `pages/areas.html` — All service areas hub
- `pages/contact.html` — Booking form + contact
- `pages/about.html` — About O2Taxi

### Airport pages (6)
- `pages/heathrow.html`
- `pages/gatwick.html`
- `pages/luton.html`
- `pages/stansted.html`
- `pages/birmingham.html`
- `pages/oxford.html`

### Local SEO area pages (24)
One page per village/town in South Oxfordshire, targeting "[village] airport taxi" keywords.

## GitHub Pages Setup

1. Create a new GitHub repository (e.g. `o2taxi-airport`)
2. Upload all files maintaining the folder structure
3. Go to **Settings → Pages**
4. Set Source to **Deploy from a branch → main / root**
5. Add your custom domain `airport.o2taxi.com` in the Pages settings
6. In your domain DNS, add a CNAME record:
   - Name: `airport`
   - Value: `YOUR-GITHUB-USERNAME.github.io`
7. Enable **Enforce HTTPS**

## Contact Form Setup

The contact form uses Formspree. To activate it:
1. Go to https://formspree.io and create a free account
2. Create a new form and copy your Form ID
3. In `pages/contact.html`, replace `YOUR_FORM_ID` in the form action URL with your actual ID

## SEO checklist after launch

- [ ] Submit `sitemap.xml` to Google Search Console
- [ ] Verify ownership in Google Search Console
- [ ] Set up Google Business Profile pointing to airport.o2taxi.com
- [ ] Add internal link from o2taxi.com homepage to airport.o2taxi.com
- [ ] Submit to Bing Webmaster Tools
- [ ] Register on local directories (Yell, Thomson Local, FreeIndex)

## Phone & WhatsApp
All pages link to: **07923 360048**
