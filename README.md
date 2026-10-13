# Pokémon Chirl Mythos — WikiDex & Guía Maestra Oficial

WikiDex interactiva, base de datos integral y guía paso a paso para **Pokémon Chirl Mythos**, diseñada para su publicación directa en **GitHub Pages**.

---

## 🌟 Características Principales

- **📖 Pokédex Completa e Interactiva:** Fichas técnicas detalladas de especies (Gen 1-9), tipos, estadísticas base, habilidades oficiales, movimientos por nivel y árboles evolutivos completos.
- **🗺️ Rutas & Encuentros Salvajes:** Mapa interactivo de Johto y Kanto con probabilidades de aparición, niveles y objetos por zona.
- **🛡️ Sistema de Level Caps & Líderes:** Niveles máximos por gimnasio, equipos de líderes y Altos Mandos.
- **🎒 Tiendas & Objetos Clave:** Catálogo de objetos competitivos, evolutivos y mentas de naturaleza.
- **📜 Guía Paso a Paso:** Recorrido detallado capítulo a capítulo de la aventura principal y postgame.
- **⚡ Búsqueda Universal:** Buscador en tiempo real por nombre de Pokémon, movimiento, habilidad, objeto o ruta.

---

## 🚀 Despliegue en GitHub Pages

1. Sube los cambios a la rama `main`:
   ```bash
   git add .
   git commit -m "feat: Guía oficial Chirlidex de Pokémon Chirl Mythos v0.2.5"
   git push origin main
   ```
2. En GitHub: entra a **Settings** &rarr; **Pages**.
3. En **Build and deployment**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `/ (root)`
4. Haz clic en **Save**. En 1-2 minutos tu guía estará visible en `https://chirl89.github.io/Pokemon-Chirl-Mythos-Guia/`.

---

## 💻 Vista Previa Local

Al ser una aplicación 100% estática (HTML5 / CSS3 / Vanilla JavaScript ES6), no requiere Node.js ni compilación:
- Puedes abrir directamente `index.html` con cualquier navegador web.
- O servirla con un servidor ligero:
  ```bash
  python -m http.server 8000
  ```
