# 🍳 COOKER – Asistente de cocina por ingredientes

**Escribe lo que tienes, cocina lo que quieras.**

COOKER es una aplicación web que te permite introducir los ingredientes que tienes en casa y obtener al instante recetas que los aprovechan al máximo, ordenadas por coincidencia y tiempo de preparación. Elimina el bloqueo de "no sé qué cocinar" y reduce el desperdicio de alimentos.

![Versión MVP](https://img.shields.io/badge/versión-MVP-orange) ![estado](https://img.shields.io/badge/estado-en%20desarrollo-green)

---

## 🎯 Características del MVP

- 🔍 **Búsqueda por ingredientes:** escribe tus ingredientes separados por comas.
- ⏱️ **Filtro por tiempo máximo:** descarta recetas que no se ajustan a tu prisa.
- 📊 **Porcentaje de coincidencia:** cada receta muestra qué porcentaje de sus ingredientes tienes y cuáles te faltan.
- 📋 **Vista de detalle:** instrucciones paso a paso y dificultad.
- ⚡ **Funcionamiento 100% cliente:** sin backend, sin registro, sin dependencias externas.

---

## 🧱 Stack tecnológico (MVP)

| Componente       | Tecnología                           |
|------------------|--------------------------------------|
| Frontend         | HTML5, CSS3, JavaScript (vanilla)    |
| Datos            | JSON embebido (10 recetas de ejemplo)|
| Despliegue       | GitHub Pages o Vercel (futuro)       |

En fases posteriores se migrará a React + Node.js/Express + base de datos real.

---

## 🚀 Cómo ejecutar localmente

### Opción 1: Directamente en el navegador
1. Descarga o clona el repositorio.
2. Haz doble clic en `cooker.html`.
3. ¡Listo! Funciona sin servidor.

### Opción 2: Con un servidor local (recomendado para desarrollo futuro)
```bash
# Si tienes Python 3
python -m http.server 8000
# O con Node.js (npx)
npx serve .
