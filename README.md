# WM Public Assets

Public CDN for Wender Media brand assets. Used when an asset needs to be fetched by external services (email clients fetching logos in DOI mails, social media fetching OG images, third-party APIs, etc.) and the originating site has password protection or is otherwise unreachable.

## Usage

Direct GitHub raw URLs are CDN-backed and globally cached:

```
https://raw.githubusercontent.com/arnoldwender/wm-public-assets/main/<brand>/<asset>
```

## Brands

### Hairprofis.de

```
https://raw.githubusercontent.com/arnoldwender/wm-public-assets/main/hairprofis/logo.png
https://raw.githubusercontent.com/arnoldwender/wm-public-assets/main/hairprofis/logo-2x.png
```

## Adding a new asset

1. Create a folder per brand (`<brand-slug>/`)
2. Add files with descriptive names
3. Commit + push — files are immediately available via raw URL
4. CDN cached globally with ~5 min TTL on cache invalidation
