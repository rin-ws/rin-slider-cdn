# RINslider

**Sprachen / Languages:**  🇩🇪 Deutsch | 🇬🇧 [English](readme.en.md) | 🇪🇸 [Español](readme.es.md) | 🇫🇷 [Français](readme.fr.md) | 🇯🇵 [日本語](readme.jp.md) | 🇰🇷 [한국어](readme.kr.md)

---

Ein bewusst schlanker Vanilla-JavaScript Slider für moderne Websites – performant, zugänglich und ohne externe Abhängigkeiten.

Dieses Repository stellt ausschließlich **die fertigen CDN-Builds** von RINslider bereit.

🔍 **Vollständiger, unminifizierter Quellcode (Open Source):**  
https://de.rinslider.com/open-code/

---

## ✨ Features

- 🚀 Reines Vanilla JavaScript – keine Abhängigkeiten
- 📱 Vollständig responsive & touch-fähig
- 🖱️ Mouse Drag & 💨 Swipe Momentum
- ♾️ Infinite Loop
- ⏯️ Autoplay mit Fortschrittsbalken
- 🎯 Dots-, Arrow- & Thumbnail-Navigation
- ♿ Barrierefrei (ARIA, Keyboard, Fokus)
- 🎭 Reduced Motion Support (`prefers-reduced-motion`)
- 🌍 RTL-Unterstützung
- 🎢 Nested Slider Support
- 🎬 Parallax-Effekte
- 🖼️ Lazy Loading
- 🎨 Einfach zu stylen

---

## 📦 CDN Installation (empfohlen)

### CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rin-ws/rin-slider-cdn@v1.0.0/slider.min.css">
```
### JavaScript
```
<script src="https://cdn.jsdelivr.net/gh/rin-ws/rin-slider-cdn@v1.0.0/slider.min.js"></script>
```

## 🚀 Quick Start
```
<div class="rin-slider" data-slider>
  <div class="slide">Slide 1</div>
  <div class="slide">Slide 2</div>
  <div class="slide">Slide 3</div>
</div>

<script>
  const slider = new Slider('.rin-slider', {
    infinite: true,
    autoplay: true,
    dots: true,
    arrows: true
  });
</script>
```
## 🔌 Public API (Auszug)
```
slider.next();
slider.prev();
slider.goTo(index);

slider.play();
slider.pause();

slider.addSlide(htmlOrElement);
slider.removeSlide(index);

slider.destroy();
```
## 📚 Dokumentation
Die vollständige Dokumentation mit:

- allen Konfigurationsoptionen

- API-Methoden

- Accessibility-Details

- RTL, Nested Slider, Parallax, Lazy Loading

- Framework-Integrationen (React, Vue, WordPress, etc.)

findest du hier: https://rinslider.com

## 🔖 Versionierung

RINslider folgt Semantic Versioning:

- PATCH – Bugfixes

- MINOR – neue Features (rückwärtskompatibel)

- MAJOR – Breaking Changes

## ❤️ Support
RINslider ist ein Open-Source-Projekt und wird in der Freizeit gepflegt.
Wenn du die Entwicklung unterstützen möchtest:

Patreon: https://www.patreon.com/rinslider

Ko-fi: https://ko-fi.com/rinws

Alle Features bleiben frei verfügbar – Support ist optional.

## 📄 Lizenz
MIT

## 🔗 Link
- RINslider WIki: https://de.rinslider.com/wiki/
