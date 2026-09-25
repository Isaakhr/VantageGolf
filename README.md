<p align="center"><img src="og-image.jpg" alt="VantageGolf" width="720"></p>

# VantageGolf

Sitio oficial de **Vantage Golf · Performance Rope Golf Cap** — *Hecha para elevar tu juego.*

🔗 **En vivo:** https://isaakhr.github.io/VantageGolf/

## Qué incluye

| Sección | Qué hace |
|---|---|
| **Hero** | Carrusel automático entre los 4 colores (blanca, negra, gris claro, gris oscuro) con selector manual |
| **Pelota 3D** | Pelota de golf en Three.js que acompaña el scroll y aterriza en el punto del logo |
| **Pieza por pieza** | Modelo 3D real de la gorra que se arma con el scroll (7 piezas) + vista libre (arrastrar, pellizcar para zoom) |
| **360°** | Video de ensamblaje controlado por el scroll y luego giro de la gorra en 4 vistas y 4 colores |
| **Galería** | Carrusel horizontal con tarjetas en 3D |
| **Ficha técnica** | Especificaciones completas y diagrama del bordado (48 × 60 mm) |
| **Legal** | Aviso de privacidad, términos y condiciones, envíos y devoluciones |

## Tecnología

- HTML + CSS + JavaScript sin build (sitio estático)
- [GSAP 3 + ScrollTrigger](https://gsap.com) · [Lenis](https://lenis.darkroom.engineering) · [Three.js r128](https://threejs.org)
- Modelo 3D y video generados con Higgsfield (Meshy 7 / Seedance 2.5) a partir de las fotos de producto
- PWA básica: `site.webmanifest`, íconos para iOS/Android, color de barra del navegador
- SEO: meta description, Open Graph, Twitter Card, JSON-LD (Organization, WebSite, Product), `sitemap.xml`, `robots.txt`
- Accesible: textos alternativos, foco visible, respeta *reducir movimiento*

## Estructura

```
index.html                 página principal
privacidad.html            aviso de privacidad
terminos.html              términos y condiciones
envios-devoluciones.html   envíos, cambios y devoluciones
404.html                   página no encontrada
img/                       fotos de producto
seq/                       97 cuadros del video de ensamblaje
models/                    modelo 3D de la gorra (glTF)
favicon.* icon-*.png apple-touch-icon.png og-image.jpg site.webmanifest
robots.txt sitemap.xml
```

## Ver en local

```bash
python -m http.server 8080
# abre http://localhost:8080
```

## Publicar cambios

GitHub Pages publica automáticamente la rama `main`. Haz commit y push; en ~1 minuto se actualiza el sitio.

## ⚠️ Pendiente antes de lanzar

Las páginas legales son **plantillas** basadas en la legislación mexicana (protección de datos personales y Ley Federal de Protección al Consumidor). Los datos marcados en dorado como `[...]` deben completarse con la información real del negocio (razón social, domicilio, correo, WhatsApp, plazos, métodos de pago, ciudad) y **revisarse con un abogado** antes de vender.

## Derechos

© 2026 Vantage Golf. Todos los derechos reservados. Ver [NOTICE.md](NOTICE.md).
