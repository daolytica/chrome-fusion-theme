# Magnetic Fusion Chrome Theme

A Tokamak fusion-inspired Chrome theme with a lead brick frame design, featuring a dark color scheme optimized for scientific and technical work.

## Features

- **Dark Theme**: Optimized for low-light environments and extended use
- **Fusion-Inspired Design**: Tokamak reactor aesthetic with lead brick frame
- **High Contrast**: Excellent readability with carefully chosen color combinations
- **Incognito Support**: Custom colors for private browsing mode
- **Responsive Images**: Properly sized background and frame images

## Installation

### Method 1: Load as Unpacked Extension (Developer Mode)

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" in the top right corner
3. Click "Load unpacked" and select this theme directory
4. The theme will be applied immediately

### Method 2: Package as .crx File

1. In Chrome Extensions page, click "Pack extension"
2. Select this directory as the extension root
3. Install the generated .crx file

## File Structure

```
chrome-theme/
├── manifest.json          # Theme configuration
├── icons/                 # Theme icons (16x16 to 128x128)
│   ├── icon16.png
│   ├── icon32.png
│   ├── icon48.png
│   └── icon128.png
├── images/                # Theme images
│   ├── frame.png          # Browser frame background
│   ├── toolbar.png        # Toolbar background
│   └── ntp_background.png # New Tab Page background
└── README.md             # This file
```

## Customization

### Color Scheme

The theme uses a carefully balanced dark color palette:

- **Frame**: Dark gray (#191919) - Browser frame
- **Toolbar**: Medium gray (#282828) - Address bar area
- **Text**: White (#FFFFFF) - High contrast for readability
- **Accent**: Blue (#3C78C8) - Interactive elements

### Image Requirements

- **Frame Image**: Should be 128x128px or larger
- **Toolbar Image**: Should be 128x128px or larger  
- **NTP Background**: Should be 1920x1080px or larger for best results

### Resolution Independence

The theme is configured to maintain consistent alignment across different screen resolutions:

- **Background Positioning**: Uses `center` alignment to keep elements centered
- **No Tiling**: Prevents image repetition that could cause misalignment
- **Cover Scaling**: Backgrounds scale to cover the entire area without distortion
- **Tint Controls**: Consistent color application across all UI elements

## Technical Details

### Manifest Version
- Uses Manifest V3 for modern Chrome compatibility
- Includes proper icon sizes for all Chrome UI elements
- Supports both regular and incognito browsing modes

### Color Properties
- `frame`: Browser frame color
- `toolbar`: Address bar and toolbar color
- `tab_text`: Active tab text color
- `tab_background_text`: Inactive tab text color
- `bookmark_text`: Bookmark bar text color
- `ntp_background`: New Tab Page background color
- `ntp_text`: New Tab Page text color
- `button_background`: Button background color

### Image Properties
- `ntp_background_alignment`: "center" - Centers background image
- `ntp_background_repeat`: "no-repeat" - Prevents image tiling
- `ntp_background_size`: "cover" - Scales image to cover entire area

## Troubleshooting

### Theme Not Applying
1. Ensure all image files exist in the correct locations
2. Check that manifest.json is valid JSON
3. Try refreshing the extensions page
4. Restart Chrome completely

### Images Not Displaying
1. Verify image file paths in manifest.json
2. Check image file sizes and formats (PNG recommended)
3. Ensure images are not corrupted

### Color Issues
1. Verify color values are in RGB format [R, G, B]
2. Check that all required color properties are defined
3. Test in both regular and incognito modes

## Development

To modify the theme:

1. Edit `manifest.json` to change colors or properties
2. Replace image files in the `images/` directory
3. Update icon files in the `icons/` directory
4. Test changes by reloading the extension

## License

This theme is provided as-is for educational and personal use.

## Credits

Inspired by Tokamak fusion reactor designs and scientific visualization aesthetics.
