# 🎨 Shader Studio

Convertí cualquier imagen en arte con shaders, en tiempo real y desde el navegador.
Una sola página HTML, sin dependencias ni instalación: cargás una imagen, elegís un
estilo y exportás el resultado en PNG a resolución completa.

> **[▶ Abrir la demo](https://marumusella.github.io/shader-studio/)**

## Cómo se usa

1. Abrí `index.html` (doble clic) o serví la carpeta con cualquier servidor estático.
2. Cargá una imagen con el botón, **arrastrándola** al lienzo, o **pegándola** (Ctrl/Cmd + V).
3. Elegí un estilo en la barra lateral — se aplica en vivo.
4. Ajustá los parámetros con los sliders.
5. **Exportar PNG** guarda el resultado a resolución completa (hasta 2048 px por lado).

## Estilos incluidos

| Grupo | Shaders |
|---|---|
| **Retro / Pixel** | Pixelado · CRT/Tube · Dithering (Bayer) · ASCII Art · Game Boy |
| **Artístico** | Pintura al óleo (Kuwahara) · Acuarela · Halftone CMYK · Posterización · Cross-hatch |
| **Glitch / Digital** | Aberración cromática · Glitch animado · VHS/Scanlines |
| **Detección / Líneas** | Bordes (Sobel) · Kuwahara · Curvas de nivel |

## Tecnología

- **WebGL2 + GLSL ES 3.00** (necesario para las operaciones bitwise del ASCII y `fwidth` del halftone).
- Sin librerías ni build: todo en un único archivo.
- UI estilo Apple, light mode.
- Glitch y VHS están animados (usan `u_time`).

## Licencia

MIT
