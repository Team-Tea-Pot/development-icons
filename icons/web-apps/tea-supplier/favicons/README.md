# Tea Supplier Web App Favicons

Favicon files for the Tea Supplier web application.

## Required Files

### 16x16
- `favicon-16x16.png` - Small browser tab icon
- `favicon-16x16.ico` - IE compatibility

### 32x32  
- `favicon-32x32.png` - Standard browser favicon
- `favicon.ico` - Root favicon file

### 192x192
- `android-chrome-192x192.png` - Android Chrome bookmark icon
- `apple-touch-icon-192x192.png` - iOS Safari bookmark

### 512x512
- `android-chrome-512x512.png` - High-resolution Android icon
- `apple-touch-icon-512x512.png` - High-resolution iOS icon

## Web App Manifest
Include these icons in your web app manifest:
```json
{
  "icons": [
    {
      "src": "/icons/web-apps/tea-supplier/favicons/192x192/android-chrome-192x192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "/icons/web-apps/tea-supplier/favicons/512x512/android-chrome-512x512.png", 
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
```