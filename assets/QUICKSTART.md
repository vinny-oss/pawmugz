# PawMugz Theme - Quick Start Guide

## ✅ What's Installed
- **Shopify CLI:** v3.88.0
- **Theme Files:** 60 Liquid templates
- **Collections:** 20+ dog breed collections
- **Languages:** 50+ locales

## 🚀 How to Preview Your Theme Locally

### Step 1: Connect to Your Shopify Store
```bash
shopify auth login
```
This will open a browser window to authenticate with your Shopify store.

### Step 2: Start Development Server
```bash
shopify theme dev
```
This will:
- Upload your theme to Shopify
- Start a local preview server
- Watch for file changes
- Hot-reload in the browser

### Step 3: Open in Browser
The CLI will provide a local URL (usually `http://127.0.0.1:9292`)

## 📦 Other Useful Commands

### Check Theme for Issues
```bash
shopify theme check
```

### Push Theme to Shopify
```bash
# Push to development theme
shopify theme push --development

# Push to live theme (BE CAREFUL!)
shopify theme push --live
```

### Pull Theme from Shopify
```bash
shopify theme pull
```

### List Your Themes
```bash
shopify theme list
```

### Share Preview Link
```bash
shopify theme share
```

## 📁 Theme Structure Summary

```
📂 pawmugz/
├── 📄 60 Liquid templates
├── 📄 24 Sections
├── 📄 30+ Snippets
├── 📄 60+ CSS files
├── 📄 30+ JavaScript files
├── 📄 80+ SVG icons
└── 📄 50+ Language files
```

## 🎨 Your Collections

### Dog Breeds
- Bulldog, Chihuahua, Corgi, Dachshund
- French Bulldog, German Shepherd
- Golden Retriever, Labrador
- Pomeranian, Pug

### Special Collections
- Coffee Pups
- Fitness Pups
- Humour Pups
- Love Collection
- Pupnado
- Halloween
- Christmas (Coming Soon)

## 🛠️ Development Workflow

1. **Make changes** to your theme files
2. **Shopify CLI auto-detects** changes
3. **Browser auto-refreshes** with updates
4. **Test** your changes locally
5. **Push** to Shopify when ready

## ⚠️ Important Notes

- **DO NOT** push to live without testing first
- Always use `--development` flag when testing
- Keep backups of your theme
- Test on multiple devices/browsers

## 🆘 Need Help?

```bash
# General help
shopify help

# Theme-specific help
shopify theme help

# Check for updates
shopify upgrade
```

## 📚 Resources

- [Shopify Theme Docs](https://shopify.dev/docs/themes)
- [Liquid Reference](https://shopify.dev/docs/api/liquid)
- [Rise Theme Guide](https://help.shopify.com/en/manual/online-store/themes/themes-by-shopify/rise)

---

**Ready to start?** Run `shopify theme dev` to begin!
