# BioSupport Care Shopify Theme

A comprehensive Shopify theme for BioSupport Care's orthopedic products, featuring a modern e-commerce interface with teal/turquoise and blue color scheme.

## Features

- Responsive design optimized for mobile, tablet, and desktop
- Clean, modern aesthetic with teal/turquoise color scheme
- Product grid layout with circular "+" buttons for quick add-to-cart
- Comprehensive waitlist form for product notifications
- Multilingual support with Spanish translations included

## Directory Structure

### Main Layout
- `theme.liquid` - Main theme layout with HTML structure and global styling
- `settings_schema.json` - Theme settings schema for customizing colors, typography, and more

### Sections
- `header.liquid` - Top navigation and site header with teal top bar
- `announcement-bar.liquid` - Pre-header message bar for promotions or announcements
- `hero-section.liquid` - Hero section with image, heading, and call-to-action buttons
- `product-grid.liquid` - Product grid display with circular "+" buttons
- `featured-products.liquid` - Featured products section for showcasing specific products
- `waitlist-section.liquid` - Waitlist form section for collecting customer information
- `product-template.liquid` - Product detail page template

### Configuration and Data
- `settings_schema.json` - Theme settings schema for customizing colors, typography, and more
- `sample-product-data.json` - Sample product data that can be used to import products into your store
- `locales/es.json` - Spanish translations for your theme

## Installation Instructions

### Option 1: Using the Shopify Theme Editor

1. Log in to your Shopify admin dashboard
2. Go to **Online Store > Themes**
3. Click on **Actions > Edit code** for your current theme (or a duplicate of it)
4. Navigate to the appropriate directories:
   - For sections: Go to the "Sections" folder and create new section files
   - For templates: Go to the "Templates" folder and create new template files
   - For the layout: Go to the "Layout" folder and edit or create a new layout file
5. Copy the code from each file in this directory and paste it into the corresponding file in the Shopify theme editor
6. Save each file after pasting

### Option 2: Using Shopify Theme CLI (for developers)

If you're comfortable with development tools, you can:

1. Install the [Shopify CLI](https://shopify.dev/themes/tools/cli)
2. Initialize a new theme or download your current theme
3. Replace the appropriate files with the ones from this directory
4. Deploy the theme using the Shopify CLI

## Customization

Each section includes a schema that allows for customization through the Shopify theme editor. After adding these sections to your theme, you can:

1. Go to **Online Store > Themes**
2. Click on **Customize** for your theme
3. Add the sections to your pages through the theme editor
4. Customize the content, colors, and settings as needed

## Color Scheme

The primary color used throughout the theme is a teal/turquoise: `#0ab2a8`

The theme also uses these complementary colors:
- Dark teal: `#089089`
- Light teal background: `#e8f7f6`
- Light blue background: `#d7efff`

## Notes

- The templates are designed to work with Tailwind CSS, which is loaded via CDN in the theme.liquid file
- Font Awesome is used for icons
- Alpine.js is included for interactive elements
- The product grid template includes hover effects for "add to cart" buttons

If you need to make any further customizations, refer to the [Shopify Liquid documentation](https://shopify.dev/api/liquid).