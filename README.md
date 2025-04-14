# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals and enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-NETLIFY-ID/deploy-status)](https://app.netlify.com/)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Resources & Support](#resources--support)

## Overview
AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources in a clean, three-column grid layout. Built with HTML5, CSS3, and vanilla JavaScript for optimal performance.

## Features
- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- ⚡ Fast loading performance
- 🎨 Customizable styling
- 📊 SEO optimized

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Git
- Text editor (VS Code recommended)

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure
```
ai-tools-directory/
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
├── data/
│   └── directory-items.json
├── index.html
├── README.md
└── package.json
```

## Customization Guide

### Adding Directory Items
Edit `data/directory-items.json`:
```json
{
  "items": [
    {
      "id": "1",
      "title": "Tool Name",
      "description": "Tool description",
      "category": "Category",
      "url": "https://example.com",
      "image": "tool-image.jpg"
    }
  ]
}
```

### Modifying Categories
Update the categories array in `assets/js/main.js`:
```javascript
const categories = [
  'AI Writing',
  'Image Generation',
  'Voice AI',
  'Code Assistance'
];
```

### Updating Hero Section
Modify the hero section in `index.html`:
```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description text</p>
</section>
```

### Customizing Colors
Edit `assets/css/style.css`:
```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
  --text-color: #333333;
}
```

## Deployment

### Netlify Deployment
1. Push your code to GitHub
2. Log in to Netlify
3. Click "New site from Git"
4. Select your repository
5. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
6. Click "Deploy site"

## Custom Domain Setup

1. Purchase domain from your preferred registrar
2. In Netlify:
   - Go to Site settings > Domain management
   - Click "Add custom domain"
   - Enter your domain name
3. Update DNS records:
   ```
   A Record: @ points to Netlify's IP
   CNAME: www points to yoursite.netlify.app
   ```

## Troubleshooting

### Common Issues

#### Images Not Loading
- Verify file paths in `directory-items.json`
- Check image format compatibility
- Ensure images are in the correct directory

#### Search Not Working
- Clear browser cache
- Check console for JavaScript errors
- Verify data structure in JSON file

## Resources & Support

- [Documentation Wiki](https://github.com/yourusername/ai-tools-directory/wiki)
- [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- [Contributing Guidelines](CONTRIBUTING.md)

### Support Channels
- GitHub Issues
- Email: support@aitools-directory.com
- Twitter: [@AIToolsDir](https://twitter.com/AIToolsDir)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [Your Name](https://github.com/yourusername)