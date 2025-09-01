# Website Design Upgrade

This document outlines the changes made to modernize the website design to match the style of https://github.com/aboggust/aboggust.github.io.

## Changes Made

### 1. New Layout System
- **Created `_layouts/splash.html`**: A new layout specifically for the homepage that provides a clean, modern design
- **Updated `_pages/home.md`**: Changed from archive layout to splash layout and restructured content
- **Created `_includes/splash-nav.html`**: A minimal navigation component for the new design

### 2. Modern Styling
- **Created `assets/css/splash.css`**: New CSS file with modern styling inspired by the reference site
- **Features**:
  - Clean typography using Roboto and Roboto Condensed fonts
  - Modern gradient background for the intro section
  - Fixed navigation with backdrop blur effect
  - Responsive design for mobile devices
  - Hover effects and smooth transitions
  - Card-based layout for publications and news

### 3. Content Structure
- **Intro Section**: Prominent name and title with professional headshot
- **Social Links**: Modern button-style links for CV, Google Scholar, GitHub, LinkedIn, and email
- **News Section**: Clean timeline-style news items with dates
- **Publications Section**: Card-based publication display with links

### 4. Updated Publication Format
- **Enhanced publication front matter**: Added `authors` and `links` arrays for better structure
- **Modern publication display**: Clean cards with hover effects and organized link buttons

### 5. Navigation Updates
- **Updated `_data/navigation.yml`**: Changed home URL from `/home/` to `/` for cleaner URLs
- **Fixed navigation**: Sticky navigation bar with modern styling

## Key Design Features

### Typography
- **Primary Font**: Roboto (clean, readable)
- **Heading Font**: Roboto Condensed (modern, professional)
- **Color Scheme**: Blue (#3498db) with dark grays (#2c3e50, #555)

### Layout
- **Single-page design**: Clean, focused homepage
- **Responsive**: Works well on desktop, tablet, and mobile
- **Modern spacing**: Generous padding and margins for readability

### Interactive Elements
- **Hover effects**: Subtle animations on buttons and cards
- **Smooth transitions**: CSS transitions for professional feel
- **Modern buttons**: Rounded corners with shadows and hover states

## Files Modified/Created

### New Files
- `_layouts/splash.html`
- `_includes/splash-nav.html`
- `assets/css/splash.css`
- `preview.html` (for testing)
- `WEBSITE_UPGRADE.md` (this file)

### Modified Files
- `_pages/home.md`
- `_data/navigation.yml`
- `_publications/*.md` (updated front matter)

## Preview

To see the new design, open `preview.html` in a web browser. This shows how the final website will look with the new modern design.

## Next Steps

1. **Test the website**: Run `bundle exec jekyll serve` to test locally
2. **Update content**: Add real publication data with proper authors and links
3. **Customize colors**: Adjust the color scheme if needed
4. **Add more sections**: Consider adding research interests, teaching, or other sections
5. **Optimize images**: Ensure profile photo is high quality and properly sized

## Browser Compatibility

The new design uses modern CSS features including:
- CSS Grid and Flexbox
- Backdrop filter (for navigation blur)
- CSS transitions and transforms
- Modern font loading

These features are supported in all modern browsers (Chrome, Firefox, Safari, Edge).
