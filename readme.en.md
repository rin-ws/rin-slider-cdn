# RINslider

A deliberately lightweight Vanilla JavaScript slider for modern websites – performant, accessible, and dependency-free.

This repository provides the **prebuilt CDN files** for RINslider.

👉 **Full documentation & examples:**  
https://rinslider.com

---

## ✨ Features (Excerpt)

- 🚀 Pure Vanilla JavaScript – no dependencies
- 📱 Fully responsive & touch-enabled
- 🖱️ Mouse drag & 💨 swipe momentum
- ♾️ Infinite loop support
- ⏯️ Autoplay with progress bar
- 🎯 Dots, arrows & thumbnail navigation
- ♿ Accessible (ARIA, keyboard support, reduced motion)
- 🎭 `prefers-reduced-motion` support
- 🎢 Nested slider support
- 🌍 Full RTL support
- 🎬 Optional parallax effects
- 🖼️ Lazy loading, captions & gap support

---

## 📦 CDN Installation (Recommended)

### CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.css">
```
### JavaScript
```
<script src="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.min.js"></script>
```
## 🚀 Quick Start
```
<div id="mySlider" data-slider>
  <div class="slide">Slide 1</div>
  <div class="slide">Slide 2</div>
  <div class="slide">Slide 3</div>
</div>

<script>
  new Slider('#mySlider', {
    infinite: true,
    autoplay: true,
    dots: true,
    arrows: true
  });
</script>
```
## 📚 Documentation
The full documentation includes:

complete configuration reference

public API methods

accessibility details

RTL, nested sliders, parallax & lazy loading

framework integrations (React, Vue, WordPress, etc.)

👉 RINslider Full Documentation
https://rinslider.com/wiki/

## 🔖 Versioning
RINslider follows Semantic Versioning:

- PATCH – bug fixes

- MINOR – new features (backwards compatible)

- MAJOR – breaking changes

## ❤️ Support
RINslider is an open-source project maintained in spare time.
If you find it useful, you can support its continued development:

- Patreon: https://www.patreon.com/rinslider

- Ko-fi: https://ko-fi.com/rinws

All features remain freely available. Support is optional.

## 📄 License
MIT

