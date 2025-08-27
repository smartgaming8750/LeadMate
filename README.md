# SocialSizer Pro

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

A powerful, browser-based tool for resizing and optimizing images for all major social media platforms in bulk. Process multiple images simultaneously with complete privacy - your images never leave your device.

![SocialSizer Pro](https://via.placeholder.com/800x400/2563eb/ffffff?text=SocialSizer+Pro+-+Perfect+Social+Media+Images)

## 🌟 Features

- **Bulk Processing**: Resize multiple images for multiple platforms simultaneously
- **Platform Coverage**: Support for all major social media platforms (Instagram, Facebook, Twitter, LinkedIn, YouTube, Pinterest, TikTok, and more)
- **Privacy-First**: All processing happens locally in your browser - no server uploads required
- **Customization Options**: Multiple resize methods, format selection, quality control, and background color options
- **Batch Download**: Download all resized images at once as a ZIP file
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Completely Free**: No hidden fees, subscriptions, or watermarks

## 🚀 Quick Start

1. Visit [SocialSizer Pro Website](https://yourdomain.com)
2. Click "Upload Images" or drag and drop your files
3. Select the social platforms you need
4. Customize resize options if needed
5. Preview the results
6. Download individually or as a batch

## 📋 Supported Platforms

| Platform | Type | Dimensions | Aspect Ratio |
|----------|------|------------|--------------|
| Instagram | Post | 1080×1080 px | 1:1 |
| Instagram | Story | 1080×1920 px | 9:16 |
| Facebook | Post | 1200×630 px | 1.91:1 |
| Twitter/X | Post | 1600×900 px | 16:9 |
| LinkedIn | Post | 1200×627 px | 1.91:1 |
| Pinterest | Pin | 1000×1500 px | 2:3 |
| YouTube | Thumbnail | 1280×720 px | 16:9 |
| TikTok | Video | 1080×1920 px | 9:16 |
| And more... | | | |

## 🛠️ How It Works

SocialSizer Pro uses the HTML5 Canvas API to process images directly in your browser:

1. **Upload**: Select images from your device (JPG, PNG, WebP, GIF)
2. **Processing**: Images are resized according to platform specifications
3. **Customization**: Apply your preferred resize method and format options
4. **Preview**: See how your images will look on each platform
5. **Download**: Get your perfectly sized images individually or in a batch

## 🔧 Technical Details

### Built With
- HTML5 Canvas API for image processing
- Vanilla JavaScript for functionality
- JSZip for batch download compression
- FileSaver.js for client-side file saving
- Font Awesome for icons
- Google Fonts for typography

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

### File Limitations
- Maximum file size: 10MB per image
- Supported formats: JPG, PNG, WebP, GIF
- No limit on number of images (subject to device capabilities)

## 📦 Installation

No installation required! SocialSizer Pro runs directly in your browser.

For local development:
```bash
# Clone the repository
git clone https://github.com/yourusername/socialsizer-pro.git

# Navigate to the directory
cd socialsizer-pro

# Open in your browser
# Use a local server for best performance (optional)
python -m http.server 8000