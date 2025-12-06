# Skyout Assets

Static assets for Skyout Paragliding communications, served via jsDelivr CDN.

## CDN URL Pattern

```
https://cdn.jsdelivr.net/gh/jeffsinason/skyout-assets@main/{path}
```

## Folder Structure

```
images/
├── logos/      # Brand logos
├── headers/    # Email/newsletter headers
└── products/   # Product images (t-shirts, gear, etc.)

ebooks/
└── covers/     # Ebook cover images

newsletters/
└── 2025/       # Newsletter-specific images by year
```

## Usage Examples

```html
<!-- Logo -->
<img src="https://cdn.jsdelivr.net/gh/jeffsinason/skyout-assets@main/images/logos/skyout-logo.png" alt="Skyout Logo">

<!-- Newsletter header -->
<img src="https://cdn.jsdelivr.net/gh/jeffsinason/skyout-assets@main/newsletters/2025/jan-header.jpg" alt="January Newsletter">
```

## Adding Images

1. Upload via GitHub web UI or git commit
2. Images are instantly available via CDN
3. Optionally catalog in CRM admin for easy URL lookup
