# Development Icons

A structured repository for organizing and managing icons used across tea supply chain applications.

## Overview

This repository provides a comprehensive folder structure for storing and organizing icons used in mobile apps, web applications, and shared brand assets for the tea supply chain ecosystem.

## Applications Supported

### Mobile Applications
- **Tea Supplier App**: Mobile application for tea suppliers to manage inventory and orders
- **Tea Collector App**: Mobile application for tea collectors to track routes and coordinate pickups  
- **Tea Collection Centre App**: Mobile application for collection centre management and processing

### Web Applications
- **Tea Supplier Web App**: Web dashboard for supplier business operations
- **Tea Collector Web App**: Web platform for collection operations management
- **Tea Collection Centre Web App**: Comprehensive web platform for centre management

## Folder Structure

```
icons/
├── mobile-apps/          # Mobile application icons
│   ├── tea-supplier/
│   ├── tea-collector/
│   └── tea-collection-centre/
├── web-apps/            # Web application icons  
│   ├── tea-supplier/
│   ├── tea-collector/
│   └── tea-collection-centre/
├── shared/              # Shared assets across applications
│   ├── logos/
│   ├── common-ui/
│   └── brand-assets/
└── assets/              # Source files and exported assets
    ├── source-files/
    └── exported/
```

## Usage

1. **Developers**: Use this repository as a dependency or submodule in your application projects
2. **Designers**: Store source files in `assets/source-files/` and export optimized versions to appropriate app folders
3. **Build Systems**: Configure your build process to copy icons from this repository to your application bundles

## Documentation

Each major folder contains detailed README files with specific guidelines and requirements:
- [`icons/README.md`](icons/README.md) - Complete folder structure documentation
- [`icons/mobile-apps/README.md`](icons/mobile-apps/README.md) - Mobile app icon guidelines
- [`icons/web-apps/README.md`](icons/web-apps/README.md) - Web app icon guidelines
- [`icons/shared/README.md`](icons/shared/README.md) - Shared assets documentation
- [`icons/assets/README.md`](icons/assets/README.md) - Source files and build process

## Contributing

When adding new icons:
1. Place them in the appropriate category and platform folder
2. Include multiple sizes/formats as needed for your target platform
3. Update documentation if creating new categories or applications
4. Follow established naming conventions (kebab-case recommended)

## Build Integration

This folder structure is designed to integrate with automated build processes that can:
- Copy appropriate icons to application bundles during build
- Generate platform-specific icon sets (iOS, Android, PWA)
- Optimize icons for different deployment targets
- Maintain consistent branding across all applications