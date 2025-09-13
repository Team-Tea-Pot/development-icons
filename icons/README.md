# Icons Folder Structure

This repository contains a structured hierarchy of icons for tea-related applications. The icons are organized by platform type and application category to support efficient development and packaging workflows.

## Folder Structure Overview

```
icons/
├── mobile-apps/          # Mobile application icons
├── web-apps/            # Web application icons  
├── shared/              # Shared assets across applications
└── assets/              # Source files and exported assets
```

## Mobile Apps (`mobile-apps/`)

Icons and visual assets for mobile applications across three tea business categories:

### Tea Supplier App (`tea-supplier/`)
- **app-icons/**: Main application icons
  - `ios/`: iOS-specific app icons (various sizes)
  - `android/`: Android-specific app icons (various densities)
  - `sizes/`: Generic size variants
- **ui-icons/**: User interface icons used within the app
- **splash-screens/**: Launch screen assets
- **tab-bar-icons/**: Navigation tab icons

### Tea Collector App (`tea-collector/`)
- Same structure as tea-supplier but for tea collection applications
- Icons focused on collection workflows and logistics

### Tea Collection Centre App (`tea-collection-centre/`)
- Same structure as above but for collection centre management
- Icons focused on processing and distribution workflows

## Web Apps (`web-apps/`)

Icons and visual assets for web applications:

### For each application type (`tea-supplier/`, `tea-collector/`, `tea-collection-centre/`):
- **favicons/**: Website favicon files
  - `16x16/`: Small favicon for browser tabs
  - `32x32/`: Standard favicon size
  - `192x192/`: High-resolution for mobile bookmarks
  - `512x512/`: High-resolution for PWA manifests
- **ui-icons/**: User interface icons for web applications
- **hero-images/**: Large banner and hero section images
- **navigation-icons/**: Website navigation and menu icons

## Shared Assets (`shared/`)

Common assets used across multiple applications:

- **logos/**: Company and product logos
- **common-ui/**: Reusable UI elements and icons
- **brand-assets/**: Brand guidelines, colors, and visual identity assets

## Assets (`assets/`)

Development and source materials:

- **source-files/**: Original design files (PSD, AI, Sketch, Figma exports)
- **exported/**: Processed and optimized icon files ready for distribution

## Usage Guidelines

1. **File Naming**: Use descriptive, kebab-case naming (e.g., `tea-leaf-icon.png`)
2. **Formats**: Include multiple formats (PNG, SVG, ICO where appropriate)
3. **Sizes**: Provide multiple sizes for scalability across devices
4. **Organization**: Place icons in their appropriate category and platform folder
5. **Documentation**: Update this README when adding new categories or restructuring

## Build Process Integration

This folder structure is designed to be consumed by automated build processes that will:
- Copy appropriate icons to application bundles
- Generate platform-specific icon sets
- Optimize icons for different deployment targets
- Maintain consistent branding across all tea applications

## Contributing

When adding new icons:
1. Place them in the appropriate category folder
2. Include multiple sizes/formats as needed
3. Update documentation if creating new categories
4. Follow established naming conventions