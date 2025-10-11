# Custom PDF Viewer with Color Modes

A modern, web-based PDF viewer with multiple color modes designed to reduce eye strain during extended reading sessions. Features a dark-themed interface with 12 different viewing modes.

![PDF Viewer Screenshot](<img width="1024" height="1024" alt="image" src="https://lh3.googleusercontent.com/gg-dl/AJfQ9KSkekDZr9u9WtZxc44-DoM9xqWVUpYjdGIV6dW2pxjQ4MqnXMfgJ9KAVvyM5u31u6TwsQwYuRv6t6tzizG5tt2dhRKjeieEG7G0wK1wP3pByCdwhh-wAc462TWVbqPo2hz7ZE-o_doCAkB-reSnI68ZmNwb2bjNdLUG667MesfWupm9aA=s1024-rj" />
)

## Features

- 🌙 **3 Color Modes**: Dark, Reading, Sepia, Blue Light Filter, High Contrast, and more
- 🔍 **Zoom Controls**: Adjust zoom level for comfortable reading
- 📄 **Page Navigation**: Easy navigation between pages
- 🌐 **Universal PDF Loader**: Load any PDF from URL
- ⛶ **Fullscreen Mode**: Maximize viewing area
- 📱 **Responsive Design**: Works on desktop and mobile devices
- 🎨 **Custom Interface**: Dark-themed, eye-friendly design

## Color Modes

1. **Dark Mode** - Classic dark theme with inverted colors
2. **Reading Mode** - Yellowish tint optimized for extended reading
3. **Sepia Tone** - Warm, paper-like appearance
For now, these are the only colours (More coming soon)

## Installation

### Method 1: Direct Usage (Recommended)
Simply download the `index.html` file and open it in your web browser. No additional setup required!

### Method 2: Web Hosting
1. Upload the `index.html` file to your web server
2. Access it via your domain (e.g., `https://yourdomain.com/pdf-viewer.html`)

### Method 3: Local Development
1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required

## Usage

### Loading PDFs
1. Enter a PDF URL in the input field
2. Click "Load PDF" or press Enter
3. The PDF will render with the selected color mode



### Controls
- **Zoom In/Out**: Use the zoom buttons to adjust document size
- **Page Navigation**: Use Previous/Next buttons to navigate pages
- **Color Modes**: Select from dropdown to change viewing mode
- **Fullscreen**: Click the fullscreen button for maximum viewing area
- **Open Original**: Opens the original PDF in a new tab

### Troubleshooting

#### PDF Not Loading?
1. **Check URL**: Ensure the URL points directly to a PDF file
2. **CORS Issues**: Some servers block cross-origin requests
3. **File Accessibility**: Verify the PDF is publicly accessible
4. **Use Sample**: Try the "Load Sample PDF" button for testing

#### Color Modes Not Working?
- Ensure JavaScript is enabled in your browser
- Try refreshing the page
- Check browser console for errors (F12)

## Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Technical Details

### Built With
- **PDF.js** - Mozilla's PDF rendering library
- **Vanilla JavaScript** - No frameworks required
- **CSS3** - Modern styling with CSS variables
- **HTML5** - Semantic markup

### Dependencies
- [PDF.js](https://mozilla.github.io/pdf.js/) - PDF rendering engine
- CDN-hosted for easy deployment

  ## Contributing

We welcome contributions! Please feel free to submit issues, feature requests, or pull requests.

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Areas for Improvement
- Add PDF search functionality
- Implement text selection and copying
- Add bookmark support
- Support for local file upload
- Custom color mode creation

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary:
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ✅ Include license and copyright notice

## Support

If you encounter any issues or have questions:

1. **Check Issues**: Look through existing GitHub issues
2. **Create Issue**: Open a new issue with details about the problem
3. **Provide Information**: Include browser version, PDF URL, and error messages

## Acknowledgments

- [Mozilla PDF.js](https://mozilla.github.io/pdf.js/) - For the excellent PDF rendering library
- Contributors and testers who help improve this project

## Changelog

### v1.0.0 (Current)
- Initial release
- 3 color modes
- Basic PDF viewing functionality
- Responsive design

---

**Enjoy comfortable PDF reading!** 🌟

If this project helps you reduce eye strain, please consider giving it a star ⭐ on GitHub.
