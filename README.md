# 🧬 Game of Life — Conway

Implementación interactiva del **Juego de la Vida de Conway** en HTML/CSS/JS puro.  
Sin dependencias, sin frameworks, sin build steps. Un solo archivo.

## 🎮 Demo

👉 **[Jugar ahora](https://Jul1014.github.io/game-of-life/)** 

---

## ✨ Características

| Feature | Detalle |
|---|---|
| 🖱️ Dibujo interactivo | Clic o arrastra para añadir células, incluso con la simulación corriendo. Clic derecho para borrar. |
| 📊 Stats en tiempo real | Generación actual y cantidad de células vivas |
| ⏸ Pausa / Play | Botón en pantalla o tecla `Espacio` |
| ⏭ Paso a paso | Avanza generación por generación manualmente |
| ↺ Reset | Botón en pantalla o tecla `R` |
| ⚡ Velocidad ajustable | Deslizador: 1 → 2 → 5 → 10 → 20 → 30 → 60 fps |
| ⊞ Grilla | Mostrar u ocultar la grilla de fondo |

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

## 🛠 Tecnologías

- HTML5 Canvas API
- Vanilla JavaScript (sin dependencias)
- CSS3 con variables personalizadas
- Fuentes: [Orbitron](https://fonts.google.com/specimen/Orbitron) + [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono)

---

