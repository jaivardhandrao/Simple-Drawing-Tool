# 🎨 Simple Drawing Tool

A lightweight, responsive web-based drawing application built with vanilla HTML, CSS, and JavaScript. Perfect for quick sketches, doodles, and digital art creation.

## 🚀 Live Demo

**[Try it out here!](https://jaivardhandrao.github.io/Simple-Drawing-Tool/)**

## ✨ Features

### 🎯 Core Functionality
- **Freehand Drawing**: Smooth, responsive drawing with mouse or touch
- **Color Palette**: 10 vibrant colors to choose from
- **Adjustable Brush Size**: Customizable brush from 1px to 50px
- **Eraser Tool**: True transparency eraser (not white paint)
- **Clear Canvas**: One-click to clear entire drawing

### 📱 User Experience
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Touch Support**: Full touch and gesture support for mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Intuitive Controls**: Easy-to-use toolbar with visual feedback

## 🛠️ Technical Details

### Built With
- **HTML5 Canvas**: For drawing and rendering
- **Vanilla CSS3**: Modern styling with gradients and animations
- **Pure JavaScript**: No external dependencies

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎮 How to Use

1. **Select a Color**: Click any colored circle in the palette
2. **Adjust Brush Size**: Use the slider to change brush thickness
3. **Start Drawing**: Click and drag on the white canvas
4. **Use Eraser**: Click the eraser button to switch to erase mode
5. **Clear Canvas**: Use "Clear All" to start fresh

### 🖱️ Controls
- **Left Click + Drag**: Draw/Erase
- **Touch + Drag**: Draw/Erase (mobile)
- **Color Buttons**: Switch drawing colors
- **Size Slider**: Adjust brush size
- **Eraser Button**: Toggle eraser mode
- **Clear Button**: Reset canvas

## 📂 File Structure

```
drawing-tool/
├── index.html          # Complete application (HTML + CSS + JS)
└── README.md          # This file
```

## 🚀 Quick Start

### Option 1: Direct Use
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start drawing immediately!

### Option 2: Local Server
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 🎨 Color Palette

The tool includes these pre-selected colors:
- **Black** (`#000000`) - Default
- **Red** (`#ff0000`)
- **Green** (`#00ff00`)
- **Blue** (`#0000ff`)
- **Yellow** (`#ffff00`)
- **Magenta** (`#ff00ff`)
- **Cyan** (`#00ffff`)
- **Orange** (`#ffa500`)
- **Purple** (`#800080`)
- **Pink** (`#ffc0cb`)

## 🔧 Customization

### Adding New Colors
```javascript
// Add new color button in HTML
<div class="color-btn" style="background-color: #your-color" data-color="#your-color"></div>
```

### Changing Canvas Size
```javascript
// Modify canvas dimensions in HTML
<canvas id="canvas" width="1200" height="800"></canvas>
```

### Adjusting Brush Size Range
```javascript
// Change min/max values in HTML
<input type="range" id="brushSize" min="1" max="100" value="5">
```

## 📱 Mobile Features

- **Touch Drawing**: Full support for finger and stylus input
- **Pinch Prevention**: Prevents accidental zoom while drawing
- **Responsive Layout**: Adapts to different screen sizes
- **Touch-Friendly UI**: Larger buttons and controls for mobile

## 🎯 Use Cases

- **Digital Sketching**: Quick concept drawings and sketches
- **Educational Tools**: Teaching and learning activities
- **Presentations**: Live drawing during meetings or classes
- **Art Projects**: Simple digital art creation
- **Note Taking**: Visual note-taking and annotations

## 🔍 Performance

- **Lightweight**: Single HTML file (~8KB)
- **Fast Loading**: No external dependencies
- **Smooth Drawing**: Optimized canvas operations
- **Memory Efficient**: Minimal resource usage

## 🤝 Contributing

This is a simple, self-contained project. Feel free to:
- Fork and modify for your needs
- Add new features or colors
- Improve the UI/UX
- Report issues or suggestions

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌟 Acknowledgments

- Built with modern web standards
- Inspired by classic drawing applications
- Designed for simplicity and ease of use

---

**Enjoy drawing! 🎨**
