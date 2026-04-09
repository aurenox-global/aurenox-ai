# Aurenox-AI

Landing web premium para servicios de consultoria, desarrollo y formacion en Inteligencia Artificial.

![HTML5](https://img.shields.io/badge/HTML5-Ready-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS CDN](https://img.shields.io/badge/TailwindCSS-CDN-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-Animations-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Desktop%20%26%20Mobile-111827?style=for-the-badge)

## Vision

Este proyecto representa una experiencia web de alto impacto para una marca de IA orientada a negocio.
Combina storytelling comercial, animaciones avanzadas y una estructura de conversion pensada para:

- Captar leads de consultoria y auditoria IA
- Presentar servicios y especialidades de forma clara
- Mostrar prueba social con casos de exito y resultados
- Guiar al usuario con CTAs y modales de accion directa

## Que Incluye

- Hero cinematografico con particulas, tipografia dinamica y KPIs animados
- Secciones de servicios, especialidades, proyectos y planes de inversion
- Modales completos para consultoria, auditoria, implementacion y enterprise
- Chat asistente embebido con respuestas rapidas
- Ventanas flotantes informativas por tarjeta (card info modal)
- Navegacion mobile con menu fullscreen
- Diseno visual glassmorphism + gradientes + microinteracciones

## Stack Tecnologico

- HTML5
- TailwindCSS via CDN
- CSS custom para identidad visual y animaciones
- JavaScript vanilla
- GSAP + ScrollTrigger (con fallback de seguridad)
- Font Awesome para iconografia

## Estructura del Proyecto

```text
.
|- Aurenox-Global.html   # Version principal premium
|- index.html            # Variante/landing alterna
|- README.md
|- kd                    # Archivo reservado
```

## Ejecucion Local

No requiere build ni dependencias.

1. Clona el repositorio
2. Abre `Aurenox-Global.html` directamente en tu navegador

Para una experiencia mas estable (recomendado):

```bash
# Opcion 1: Python
python3 -m http.server 8080

# Opcion 2: Node (si tienes npx)
npx serve .
```

Luego entra a `http://localhost:8080`.

## Personalizacion Rapida

- Contenido comercial: editar textos en secciones `Servicios`, `Especialidades`, `Proyectos` y `Precios`
- Branding: ajustar paleta en `tailwind.config` dentro del `<head>`
- Interacciones: modificar catalogo `cardInfoCatalog` en el script final
- Contacto: actualizar email, WhatsApp y redes sociales
- Conversion: adaptar textos y CTA en modales

## Objetivo de Producto

Este sitio esta optimizado para funcionar como:

- Web corporativa de marca IA
- Landing de captacion de auditorias IA
- Presentacion comercial para clientes B2B
- Base para escalar a sitio multi-idioma y multi-servicio

## Roadmap Sugerido

- Integrar backend de formularios con validacion real
- Conectar CRM para seguimiento de leads
- Implementar analitica de conversion por evento
- Añadir CMS para edicion sin tocar codigo
- Version PWA optimizada para mobile sales

## Contacto

- Email: aurenox-ai@proton.me
- Marca: Aurenox-AI

## Licencia

Uso interno/comercial segun politicas del propietario del proyecto.
