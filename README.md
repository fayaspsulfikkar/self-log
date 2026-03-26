# FAYAS — System Log: Human v1.0

A personal portfolio website with a terminal-style UI, interactive animations, and smooth performance optimizations.

## 🎯 Features

- **Terminal-Style Interface**: Command-line inspired design with system-like aesthetic
- **Interactive Cursor**: Custom cursor with smooth, GPU-accelerated animations
- **Terminal Panel**: Hidden portfolio accessed via "> Portfolio" button with typing animations
- **Smooth Animations**: Optimized transitions using transform-based animations and cubic-bezier easing
- **Responsive Design**: Fully mobile-optimized with breakpoints at 900px and 600px
- **Performance**: GPU-accelerated animations, transform-based cursor, and will-change optimizations
- **Pure Web Stack**: No frameworks—just vanilla HTML, CSS, and JavaScript

## 🚀 Getting Started

### Basic Usage
Simply open `index.html` in your browser:
```bash
open index.html
```

### Project Structure
```
/Users/fayas/Desktop/Self-/
├── index.html          # Main file with all HTML, CSS, and JS
├── package.json        # Project metadata
├── .gitignore         # Git configuration
└── README.md          # This file
```

## 🎨 Design System

### Color Palette
- **Base**: `#050507` - Dark background
- **Accent**: `#60a5fa` - Bright blue highlights
- **Text**: `#f0f0f2` - Primary text
- **Muted**: `#4b5563` - Secondary text

### Typography
- **Syne**: Headers and bold text (800, 700, 600, 500, 400 weights)
- **DM Mono**: Body text and terminal commands

## 🎬 Animation Features

### Cursor Animations
- Custom circular cursor that follows mouse movement
- Smooth tracking with elastic easing (cubic-bezier)
- GPU-accelerated using `transform` instead of position properties
- Expands on interactive element hover

### Section Animations
- **fadeUp**: Elements fade in and slide up on scroll
- **orbFloat**: The hero orb floats with smooth breathing motion
- **Slide Transitions**: Content slides in with smooth easing

### Performance Optimizations
- `will-change` properties for GPU hints
- `transform: translateZ(0)` for hardware acceleration
- `backface-visibility: hidden` to prevent flicker
- Event throttling on mousemove
- RequestAnimationFrame for smooth 60fps animations

## 📱 Responsive Breakpoints

### Desktop (900px+)
- Full layout with timeline spine
- 2-column philosophy/signals grid
- Large terminal panel

### Tablet (600px - 900px)
- Single column layouts
- Adjusted padding and font sizes
- Streamlined terminal panel

### Mobile (< 600px)
- Mobile-optimized spacing
- Adjusted button sizes
- Full-width terminal panel

## 🖱️ Interactive Elements

### Portfolio Button ("> Portfolio")
- Located at bottom-right corner
- Subtle when inactive (60% opacity)
- Glows on hover
- Opens terminal panel with interactive portfolio information

### Terminal Panel
- Typing animation effect for commands
- Interactive sections: Experience, Projects, Skills
- Glassmorphism design with backdrop blur
- Smooth slide-in animation

### Custom Cursor
- Smooth tracking without lag
- Expands on hover over interactive elements
- Blends with page using screen mix-blend-mode

## 🔧 Technical Specifications

### Browser Support
- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support (including iOS)

### Performance Targets
- **60 FPS** animations
- **<100ms** cursor latency
- **Smooth scrolling** with GPU acceleration

### File Size
- Single HTML file: ~85KB (minified)
- No external dependencies
- Fonts loaded from Google Fonts CDN

## 📝 Create/Update Mode

To modify the portfolio content:
1. Edit the terminal content in the JavaScript section
2. Update timeline events in the `D` array
3. Modify philosophy/realization sections in HTML
4. Update contact info in the footer

## 🎓 Learning Resources

This project demonstrates:
- Custom cursor implementation
- Performance-optimized animations
- Terminal UI design principles
- Responsive CSS Grid layouts
- Intersection Observer API
- Modern JavaScript patterns

## 📄 License

MIT License - Feel free to use this as a template for your own portfolio.

## 👤 Author

**Fayas P Sulfikkar**
- Location: Wayanad, India
- Repository: https://github.com/fayaspsulfikkar/self-log

---

**Last Updated:** March 26, 2026
**Version:** 1.0.0
