# RINslider

Un slider Vanilla JavaScript volontairement léger pour les sites web modernes : rapide, accessible et sans dépendances.

Ce dépôt fournit les **fichiers précompilés CDN** de RINslider.

👉 **Documentation complète et exemples :**  
[https://rinslider.com](https://rinslider.com)

---

## ✨ Fonctionnalités (Résumé)

- 🚀 Vanilla JavaScript pur – sans dépendances
- 📱 Totalement responsive et tactile
- 🖱️ Glisser avec la souris et 💨 défilement avec inertie
- ♾️ Support du bouclage infini
- ⏯️ Lecture automatique avec barre de progression
- 🎯 Navigation par points, flèches et vignettes
- ♿ Accessible (ARIA, support clavier, réduction du mouvement)
- 🎭 Support de `prefers-reduced-motion`
- 🎢 Support des sliders imbriqués
- 🌍 Support complet RTL (Right-to-Left)
- 🎬 Effets parallaxe optionnels
- 🖼️ Chargement différé, légendes et gestion des espacements (gap)

---

## 📦 Installation via CDN (Recommandée)

### CSS
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.css">
```
### JavaScript
```
<script src="https://cdn.jsdelivr.net/gh/DEINUSER/rin-slider-cdn@v1.0.0/rin-slider.min.js"></script>
```
## 🚀 Démarrage rapide
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
La documentation complète inclut :

- référence complète de la configuration

- méthodes de l’API publique

- détails sur l’accessibilité

- sliders RTL, imbriqués, parallaxe et chargement différé

- intégrations avec frameworks (React, Vue, WordPress, etc.)

👉 Documentation complète de RINslider
https://rinslider.com

## 🔖 Versioning
RINslider suit le Versionnage Sémantique :

- PATCH – corrections de bugs

- MINOR – nouvelles fonctionnalités (compatibles)

- MAJOR – changements non compatibles

## ❤️ Soutien / Support
RINslider est un projet open-source maintenu bénévolement.
Si vous le trouvez utile, vous pouvez soutenir son développement :

- Patreon : https://www.patreon.com/rinslider

- Ko-fi : https://ko-fi.com/rinws

Toutes les fonctionnalités restent disponibles gratuitement. Le soutien est optionnel.

## Licence
MIT
