# RINslider

Un slider de Vanilla JavaScript deliberadamente ligero para sitios web modernos: rápido, accesible y sin dependencias.

Este repositorio proporciona los **archivos precompilados CDN** de RINslider.

👉 **Documentación completa y ejemplos:**  
[https://rinslider.com](https://rinslider.com)

---

## ✨ Funcionalidades (Resumen)

- 🚀 Vanilla JavaScript puro – sin dependencias
- 📱 Totalmente responsive y táctil
- 🖱️ Arrastre con ratón y 💨 deslizamiento con inercia
- ♾️ Soporte para bucle infinito
- ⏯️ Reproducción automática con barra de progreso
- 🎯 Navegación con puntos, flechas y miniaturas
- ♿ Accesible (ARIA, soporte de teclado, reducción de movimiento)
- 🎭 Soporte de `prefers-reduced-motion`
- 🎢 Soporte para sliders anidados
- 🌍 Soporte completo RTL (Right-to-Left)
- 🎬 Efectos de paralaje opcionales
- 🖼️ Carga diferida, subtítulos y soporte de espacios (gap)

---

## 📦 Instalación vía CDN (Recomendada)

### CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.css">
```
### JavaScript
```
<script src="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.min.js"></script>
```
## 🚀 Inicio rápido
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
## 📚 Documentación
La documentación completa incluye:

referencia completa de configuración

métodos de la API pública

detalles de accesibilidad

sliders RTL, anidados, paralaje y carga diferida

integraciones con frameworks (React, Vue, WordPress, etc.)

👉 Documentación completa de RINslider
https://rinslider.com

## 🔖 Versionado
RINslider sigue Versionado Semántico:

- PATCH – corrección de errores

- MINOR – nuevas funcionalidades (compatibles hacia atrás)

- MAJOR – cambios que rompen compatibilidad

## ❤️ Apoyo / Soporte
RINslider es un proyecto de código abierto mantenido en tiempo libre.
Si lo encuentras útil, puedes apoyar su desarrollo:

- Patreon: https://www.patreon.com/rinslider

- Ko-fi: https://ko-fi.com/rinws

Todas las funcionalidades permanecen disponibles gratuitamente. El apoyo es opcional.

## 📄 Licencia
MIT
