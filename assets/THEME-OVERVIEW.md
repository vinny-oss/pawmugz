# PawMugz Shopify Theme Overview

## Theme Information
- **Base Theme:** Shopify Rise
- **Store:** PawMugz (Dog-themed mugs)
- **Logo:** Official logo included
- **Page Width:** 1200px
- **Fonts:**
  - Headers: Poppins (Bold)
  - Body: Murecho

## Directory Structure

```
pawmugz/
├── config/                    # Theme configuration
│   ├── settings_data.json     # Current theme settings
│   └── settings_schema.json   # Theme customization options
│
├── templates/                 # Page templates
│   ├── index.json            # Homepage
│   ├── product.json          # Product pages
│   ├── collection.*.json     # Collection pages (20+ variations)
│   ├── cart.json             # Shopping cart
│   ├── page.*.json           # Custom pages
│   └── customers/            # Customer account pages
│
├── sections/                  # Reusable sections
│   ├── image-banner.liquid
│   ├── featured-collection.liquid
│   ├── multicolumn.liquid
│   ├── slideshow.liquid
│   ├── video.liquid
│   └── ... (24 sections total)
│
├── snippets/                  # Small reusable components
│   ├── product-card.liquid
│   ├── product-media-gallery.liquid
│   ├── buy-buttons.liquid
│   ├── cart-drawer.liquid
│   └── ... (30+ snippets)
│
├── locales/                   # Multi-language support
│   ├── en.default.json       # English (default)
│   └── ... (50+ languages)
│
└── assets/                    # CSS, JS, images (in root)
    ├── base.css
    ├── global.js
    ├── component-*.css
    └── ... (150+ asset files)
```

## Dog Breed Collections

Your theme includes custom templates for these dog breeds:
- **Bulldog** (bulldog-front-page)
- **Chihuahua** (chichi-front-page)
- **Corgi** (corgi-front-page)
- **Dachshund** (dach-front-page)
- **French Bulldog** (frenchy-front-page)
- **German Shepherd** (german-shep)
- **Golden Retriever** (golden-front-page)
- **Labrador** (lab-front-page)
- **Pomeranian** (pom-front-page)
- **Pug** (pug-front-page)

## Special Collections
- Coffee Pups
- Fitness Pups
- Humour Pups
- Love Collection
- Pupnado
- Halloween
- Christmas (Coming Soon)
- All Mugz

## Theme Features

### Design Elements
- ✅ Rounded buttons (24px radius)
- ✅ Custom color schemes (5 different schemes)
- ✅ Animations on scroll
- ✅ Hover effects (vertical lift)
- ✅ Card-based layouts
- ✅ Badge positioning (bottom left)
- ✅ Custom thumbnails (12px rounded)

### Functionality
- ✅ Cart drawer/notification
- ✅ Predictive search
- ✅ Quick add to cart
- ✅ Product media galleries
- ✅ Multi-language support
- ✅ Gift card support
- ✅ Customer accounts
- ✅ Blog functionality
- ✅ Video sections
- ✅ Slideshow capabilities

### Color Schemes
1. **Scheme 1:** White background, black text
2. **Scheme 2:** Light gray (#f3f3f3)
3. **Scheme 3:** Dark navy (#242833)
4. **Scheme 4:** Black (#121212)
5. **Scheme 5:** Blue (#334fb4)

## How to Preview This Theme

### Option 1: Shopify CLI (Recommended)
```bash
# Install Shopify CLI (if not already installed)
npm install -g @shopify/cli @shopify/theme

# Login to your Shopify store
shopify auth login

# Preview the theme locally
shopify theme dev
```

### Option 2: Upload to Shopify
1. Zip this entire directory
2. Go to your Shopify Admin
3. Navigate to: **Online Store > Themes**
4. Click **"Add theme" > "Upload zip file"**
5. Upload and preview

### Option 3: Push to Shopify Store
```bash
# Push to your store's theme library
shopify theme push
```

## File Counts
- **Templates:** 35+ files
- **Sections:** 24 files
- **Snippets:** 30+ files
- **CSS Files:** 60+ files
- **JS Files:** 30+ files
- **SVG Icons:** 80+ files
- **Locales:** 50+ languages

## Custom CSS Highlights
- Product media without borders/shadows
- Rounded product thumbnails (12px)
- Active thumbnail highlighting
- Responsive page width container
- Custom header grid layout
- Centered logo positioning

## Next Steps

1. **Set up Shopify CLI** for local development
2. **Connect to your Shopify store**
3. **Run `shopify theme dev`** to preview locally
4. **Make customizations** as needed
5. **Deploy** when ready

## Support & Documentation
- [Shopify Theme Documentation](https://shopify.dev/themes)
- [Rise Theme Guide](https://help.shopify.com/en/manual/online-store/themes/themes-by-shopify/rise)
