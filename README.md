# Esperanza y Misericordias de Jesucristo

Sitio web oficial de la congregación **Esperanza y Misericordias de Jesucristo**, ubicada en Poza Rica de Hidalgo, Veracruz, México.

🌐 **[esperanzaymisericordias.mx](https://esperanzaymisericordias.mx)**

---

## Descripción

Sitio estático (HTML + CSS) publicado con **GitHub Pages**. Presenta la información de la iglesia: horarios de reunión, quiénes somos, nuestro pastor, obras de caridad, ubicación y opciones de contacto y donación.

## Estructura del proyecto

```
├── index.html          # Página principal
├── styles.css          # Estilos
├── CNAME               # Dominio personalizado para GitHub Pages
└── imagenes/
    ├── imagen1.webp/png  # Hero — foto principal
    ├── imagen2.webp/png  # Sección comunidad
    ├── imagen3.webp/png  # Sección caridad
    ├── imagen4.webp/png  # Foto del pastor
    └── og-preview.jpg    # Imagen para Open Graph (redes sociales)
```

## Tecnologías

- HTML5 semántico
- CSS3 (sin frameworks)
- [Font Awesome 6.5](https://fontawesome.com/) — íconos
- Google Maps Embed — ubicación
- GitHub Pages — hospedaje

## Características

- **Diseño responsivo** — adaptado para móvil, tablet y escritorio
- **Imágenes optimizadas** — formato WebP con fallback PNG (`<picture>`)
- **SEO** — meta tags, Open Graph y Twitter Card
- **Modales** — contacto (WhatsApp / teléfono) y donación (MercadoPago)
- **Menú hamburguesa** — navegación accesible en móvil
- **Carga rápida** — Font Awesome asíncrono, `loading="lazy"` en imágenes secundarias, preload del hero

## Secciones

| Sección | Descripción |
|---------|-------------|
| Hero | Horarios de reunión y botón de ubicación |
| ¿Quiénes somos? | Descripción de la comunidad |
| Nuestro Pastor | Semblanza del Pbro. Luis Alberto Vicencio Ibarra |
| Conócenos | Valores: Biblia, Evangelio, Comunidad, Oración |
| Caridad | Obras: apoyo en hospitales, donación de ropa, ayuda comunitaria |
| Ubicación | Mapa interactivo de Google Maps |
| Contacto | Modal con WhatsApp y teléfono |
| Donar | Modal con enlace a MercadoPago |

## Reuniones

| Día | Hora |
|-----|------|
| Domingos | 10:00 AM |
| Jueves | 7:00 PM |

📍 C. 5 Oriente, Independencia, 93300 Poza Rica de Hidalgo, Ver., México

## Despliegue

El sitio se publica automáticamente en GitHub Pages desde la rama `main`. El dominio personalizado se configura mediante el archivo `CNAME`.

## Redes sociales

- **Facebook:** [facebook.com/EYMJ2018](https://www.facebook.com/EYMJ2018)
