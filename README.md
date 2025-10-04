# QR Code Generator

A beautiful and functional QR code generator built with vanilla JavaScript and Tailwind CSS. Create customizable QR codes with logos, various styles, and colors - all running locally in your browser.

![QR Code Generator](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- 🎨 **Customizable Colors** - Choose custom colors for QR code dots and background with hex color support
- 🖼️ **Logo Support** - Add your own logo/image to the center of the QR code
- 🎯 **Multiple Dot Styles** - Square, Dots, Rounded, Extra Rounded, Classy, and Classy Rounded
- 🔲 **Corner Customization** - Customize outer and inner corner styles
- 🛡️ **Error Correction Levels** - Low, Medium, Quartile, and High error correction
- 🖱️ **Background Removal** - Built-in canvas-based background removal for logos (works locally)
- 📥 **Multiple Export Formats** - Download as PNG or SVG
- 🌓 **Dark Mode Support** - Automatic theme based on system preferences
- ⚡ **No Server Required** - Runs completely in the browser
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile devices

## 🚀 Quick Start

### Option 1: Direct Use
Simply open the `Test.html` file in your web browser. No installation or setup required!

### Option 2: Local Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📖 Usage

1. **Enter URL or Text**: Type or paste the URL/text you want to encode
2. **Customize Colors**: Choose colors for dots and background
3. **Select Styles**: Pick dot style and corner styles from dropdowns
4. **Add Logo (Optional)**: 
   - Click "Upload Image" to add a logo
   - Adjust logo size and margin with sliders
   - Optionally remove background from logo
5. **Download**: Click "Download PNG" or "Download SVG"

## 🎨 Customization Options

### Colors
- **Dot Color**: Color of the QR code dots/modules
- **Background Color**: Background color of the QR code
- Supports hex color input (#FFFFFF or FFF format)

### Dot Styles
- Square
- Dots
- Rounded
- Extra Rounded
- Classy
- Classy Rounded

### Corner Styles
- **Outer Corner**: Square, Dot, Extra Rounded
- **Inner Corner**: Square, Dot

### Error Correction Levels
- **Low (L)**: ~7% error correction
- **Medium (M)**: ~15% error correction (default)
- **Quartile (Q)**: ~25% error correction
- **High (H)**: ~30% error correction

Higher error correction allows the QR code to be read even if partially damaged or obscured (useful when adding logos).

## 🔧 Technical Details

### Built With
- **HTML5** - Structure
- **Tailwind CSS** - Styling via CDN
- **Vanilla JavaScript** - Logic and interactivity
- **QR Code Styling Library** - QR code generation
- **Canvas API** - Background removal

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Dependencies (Loaded via CDN)
- [Tailwind CSS](https://tailwindcss.com/) - v3.x
- [QR Code Styling](https://github.com/kozakdenys/qr-code-styling) - v1.5.0
- [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)

## 📁 File Structure

