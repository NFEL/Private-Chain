# DeZone Frontend Configs

Configuration files and assets for DeZone Network frontend applications.

## Structure

```
frontend-configs/
├── configs/
│   ├── marketplace.json           # Marketplace apps configuration
│   ├── marketplace-categories.json # App categories
│   ├── marketplace-banner.json    # Marketplace banner settings
│   ├── featured-networks.json     # Network configurations
│   ├── footer-links.json          # Footer navigation links
│   ├── 3rd-party-widgets.json     # Third-party widget configs
│   └── zetachain-chains.json      # ZetaChain integration
└── assets/
    ├── dezone-logo.svg            # Main logo (light mode)
    ├── dezone-logo-dark.svg       # Main logo (dark mode)
    ├── dezone-icon.png            # Network icon (light mode)
    ├── dezone-icon-dark.png       # Network icon (dark mode)
    └── og-image.png               # Open Graph image for social sharing
```

## Network Info

- **Chain ID:** 48198
- **RPC URL:** https://rpc.lime.dezone.network

## Usage

These files are served via GitHub raw URLs:

```
https://raw.githubusercontent.com/dezone-network/frontend-configs/main/configs/<file>.json
https://raw.githubusercontent.com/dezone-network/frontend-configs/main/assets/<file>
```

## Assets

Add your branding assets to the `assets/` folder:

- `dezone-logo.svg` - Recommended size: 200x50px
- `dezone-icon.png` - Recommended size: 64x64px
- `og-image.png` - Recommended size: 1200x630px
