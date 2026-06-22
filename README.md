<h1 align="center">ScreenPencil</h1>

<p align="center">
  Dibuja y anota sobre toda la pantalla — Windows, macOS y Linux. Gratis.
</p>

<p align="center">
  <a href="https://github.com/gepres/screenpencil-releases/releases/latest">
    <img alt="Descargar la última versión"
         src="https://img.shields.io/github/v/release/gepres/screenpencil-releases?label=Descargar&style=for-the-badge">
  </a>
</p>

---

## Descargar

### Windows

Ve a **[Releases](https://github.com/gepres/screenpencil-releases/releases/latest)**
y descarga el instalador más reciente (el badge de arriba muestra la versión actual):

```
ScreenPencil-Setup-X.Y.Z.exe
```

> El instalador aún **no está firmado** con certificado de código, así que Windows
> SmartScreen puede mostrar un aviso la primera vez. Pulsa *Más información →
> Ejecutar de todos modos*. El binario es self-contained (no necesitas instalar .NET).

### macOS

Disponible en la **[Mac App Store](https://apps.apple.com/pe/app/screenpencil/id6778615274?l=en-GB&mt=12)**.

### Linux (experimental)

Descarga **`ScreenPencil-0.2.1-linux-x64.tar.gz`** desde **[Releases](https://github.com/gepres/screenpencil-releases/releases/latest)** (self-contained, no necesitas instalar .NET):

```bash
tar -xzf ScreenPencil-0.2.1-linux-x64.tar.gz
chmod +x ScreenPencil
./ScreenPencil
```

> Para **X11** (GNOME, KDE, XFCE). El overlay, el dibujo y los atajos funcionan; la **captura de
> pantalla** es **experimental** (con compositor activo el fondo puede salir negro — en progreso).
> Mantén `ScreenPencil`, `libSkiaSharp.so` y `libHarfBuzzSharp.so` en la misma carpeta.

## Qué es

App de escritorio para Windows que coloca un lienzo transparente sobre toda la
pantalla para dibujar, resaltar, escribir texto, y usar spotlight, lupa, pizarra,
badges numerados y más. Pensada como alternativa gratuita estilo *ScreenBrush* para Windows.

> **¿Otra plataforma?** **macOS** en la [Mac App Store](https://apps.apple.com/pe/app/screenpencil/id6778615274?l=en-GB&mt=12) · **Linux** (experimental) en [Releases](https://github.com/gepres/screenpencil-releases/releases/latest) · **Android** próximamente.

## Enlaces

- 🌐 **Web:** https://gepres.github.io/screenpencil-landing/
-  **macOS (Mac App Store):** https://apps.apple.com/pe/app/screenpencil/id6778615274?l=en-GB&mt=12
- 💛 **Apóyalo (PayPal):** https://www.paypal.com/paypalme/gepresdonacion

---

<sub>Este repositorio solo aloja las descargas oficiales. El desarrollo es privado.</sub>
