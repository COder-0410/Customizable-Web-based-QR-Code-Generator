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

Simply open the HTML file in your web browser. No installation or setup required! For better performance, you can optionally run it through a local server using Python, Node.js, or PHP.

## 📖 How to Use

1. **Enter URL or Text** - Type or paste the URL/text you want to encode in the QR code
2. **Customize Colors** - Choose custom colors for dots and background using the color picker or hex input
3. **Select Styles** - Pick your preferred dot style and corner styles from the dropdown menus
4. **Add Logo (Optional)** - Upload an image to place in the center of your QR code, adjust its size and margin, and optionally remove the background
5. **Download** - Save your QR code as PNG or SVG format

## 🎨 Customization Options

### Colors
Choose any color for your QR code dots and background. Supports both color picker and manual hex color input in formats like #FFFFFF or FFF.

### Dot Styles
Select from six different dot styles: Square, Dots, Rounded, Extra Rounded, Classy, and Classy Rounded to give your QR code a unique appearance.

### Corner Styles
Customize the appearance of the three corner squares (finder patterns) with options for both outer and inner corners.

### Error Correction Levels
Choose from four error correction levels ranging from Low (7%) to High (30%). Higher levels allow the QR code to be scanned even if partially damaged or obscured, which is especially useful when adding logos.

## 🔧 Technical Details

### Built With
- **HTML5** - Page structure
- **Tailwind CSS** - Modern styling framework via CDN
- **Vanilla JavaScript** - Core logic and interactivity
- **QR Code Styling Library** - Advanced QR code generation
- **Canvas API** - Client-side background removal

### Browser Support
Works on all modern browsers including the latest versions of Chrome, Firefox, Safari, and Edge.

### External Libraries
All dependencies are loaded via CDN, including Tailwind CSS, QR Code Styling library, and Google Fonts (Inter).

## 🎯 Use Cases

Perfect for creating QR codes for business cards, marketing materials, event tickets, product labels, WiFi sharing, payment links, and much more.

## 🔒 Privacy & Security

All QR code generation and image processing happens locally in your browser. No data is sent to any server, ensuring complete privacy and security for your information.

## 🐛 Known Limitations

The background removal feature works best with images that have solid or uniform backgrounds. The algorithm may not be as accurate as AI-based solutions, but it provides good results for most use cases. The sensitivity threshold can be adjusted if needed.

## 💡 Best Practices

- Use high error correction (Quartile or High) when adding logos to ensure scannability
- Keep logos centered and sized between 30-40% for optimal results
- Always test your QR codes with multiple scanning apps before printing
- Use high contrast colors (dark dots on light background or vice versa) for better scanning
- Avoid very small QR codes, especially when including logos

## 📝 License

This project is open source and available under the MIT License. You are free to use, modify, and distribute this software for personal or commercial purposes.

## 🙏 Acknowledgments

Special thanks to the creators of QR Code Styling library, Tailwind CSS framework, and Google Fonts for making this project possible.

---

**Made with ❤️ for the community**
### Dependencies (Loaded via CDN)
- [Tailwind CSS](https://tailwindcss.com/) - v3.x
- [QR Code Styling](https://github.com/kozakdenys/qr-code-styling) - v1.5.0
- [Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)

## 📁 File Structure

