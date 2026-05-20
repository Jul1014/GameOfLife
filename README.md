# 🧬 Game of Life — Conway

Implementación interactiva del **Juego de la Vida de Conway** en HTML/CSS/JS puro.  
Sin dependencias, sin frameworks, sin build steps. Un solo archivo.

## 🎮 Demo

👉 **[Jugar ahora](https://TU-USUARIO.github.io/game-of-life/)**  
*(reemplaza `TU-USUARIO` con tu nombre de usuario de GitHub)*

---

## ✨ Características

| Feature | Detalle |
|---|---|
| 🖱️ Dibujo interactivo | Clic o arrastra para añadir células, incluso con la simulación corriendo. Clic derecho para borrar. |
| 📱 Touch | Compatible con móviles y tablets |
| 📊 Stats en tiempo real | Generación actual y cantidad de células vivas |
| ⏸ Pausa / Play | Botón en pantalla o tecla `Espacio` |
| ⏭ Paso a paso | Avanza generación por generación manualmente |
| ↺ Reset | Botón en pantalla o tecla `R` |
| ⚡ Velocidad ajustable | Deslizador: 1 → 2 → 5 → 10 → 20 → 30 → 60 fps |
| ⊞ Grilla | Mostrar u ocultar la grilla de fondo |
| 🧩 Patrones | Glider, LWSS, Blinker, Beacon, Pulsar, Gosper Gun, Aleatorio |

### Controles de teclado
| Tecla | Acción |
|---|---|
| `Espacio` | Pausar / Reanudar |
| `R` | Reiniciar |
| `→` | Avanzar un paso (solo pausado) |
| `↑` / `↓` | Aumentar / reducir velocidad |

---

## 📐 Reglas de Conway

1. Toda célula viva con menos de 2 vecinas vivas **muere** (sub-población).
2. Toda célula viva con 2 o 3 vecinas vivas **sobrevive**.
3. Toda célula viva con más de 3 vecinas vivas **muere** (sobre-población).
4. Toda célula muerta con exactamente 3 vecinas vivas **nace** (reproducción).

---

## 🚀 Cómo publicar en GitHub Pages

### Opción A — Interfaz web de GitHub
1. Crea un repositorio nuevo (ej. `game-of-life`)
2. Sube el archivo `index.html`
3. Ve a **Settings → Pages**
4. En *Source*, selecciona `main` branch → `/ (root)`
5. Guarda. En ~30 segundos tendrás tu link:  
   `https://TU-USUARIO.github.io/game-of-life/`

### Opción B — Línea de comandos
```bash
git init
git add index.html README.md
git commit -m "Game of Life"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/game-of-life.git
git push -u origin main
# Luego activa GitHub Pages en Settings
```

---

## 🛠 Tecnologías

- HTML5 Canvas API
- Vanilla JavaScript (sin dependencias)
- CSS3 con variables personalizadas
- Fuentes: [Orbitron](https://fonts.google.com/specimen/Orbitron) + [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono)

---

*Grilla toroidal — los bordes se conectan entre sí.*
