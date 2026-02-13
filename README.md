# Landing San Valentín - Amor en Páginas

Este proyecto contiene las landing pages personalizadas para San Valentín, creadas como regalos románticos con experiencia profesional de marca AEP (Amor en Páginas).

## 📁 Estructura del proyecto

```
Maxi-Aldana/
├── generar-qr.html          # Generador automático de códigos QR
├── Hugo_Milagros/
│   ├── start.html           # Página intermedia (entrada desde QR)
│   ├── index.html           # Landing principal
│   └── assets/
│       └── aep-icon.png     # Isotipo AEP
├── Matias_Isis/
│   ├── start.html
│   ├── index.html
│   └── assets/
│       └── aep-icon.png
├── Ezequiel_Ingrid/
│   ├── start.html
│   ├── index.html
│   └── assets/
│       └── aep-icon.png
└── Nicolas_Laura/
    ├── start.html
    ├── index.html
    └── assets/
        └── aep-icon.png
```

## 💑 Parejas incluidas

- **Hugo → Milagros**: Hugo creó algo especial para Milagros
- **Matias → Isis**: Matias creó algo especial para Isis
- **Ezequiel → Ingrid**: Ezequiel creó algo especial para Ingrid
- **Nicolas → Laura**: Nicolas creó algo especial para Laura

## 🎯 Flujo de experiencia

1. **QR Code**: Se escanea el código QR en la tarjeta física
2. **Página Intermedia** (`start.html`): Entrada cinematográfica con branding AEP
   - Mensaje personalizado: "[Nombre], hay una historia esperándote"
   - Watermark AEP con efecto de opacidad
   - Animación de fade out profesional
3. **Landing Principal** (`index.html`): Experiencia completa romántica
   - Juego de memoria interactivo con emojis
   - Línea de tiempo con momentos especiales
   - Carta de amor personalizada
   - Generación de tarjetas descargables
   - Capítulos secretos expandibles

## ✨ Características técnicas

- **Diseño responsivo**: Mobile-first, optimizado para todos los dispositivos
- **Animaciones suaves**: CSS keyframes con easing cinematográfico
- **Canvas API**: Generación dinámica de imágenes descargables
- **Tema oscuro**: Paleta romántica (#0e0e0e, #d2aa5a, #ff6b81)
- **Sin dependencias**: HTML/CSS/JavaScript vanilla puro
- **Autocontenido**: Cada carpeta es independiente y desplegable

## 📱 Generar códigos QR

1. Abrí [generar-qr.html](generar-qr.html) en tu navegador
2. Ingresá la URL base donde alojarás el proyecto (ej: `https://tudominio.com/sanvalentin`)
3. Los QR se generarán automáticamente para cada pareja
4. Descargá cada QR con el botón correspondiente
5. Imprimí los QR en las tarjetas físicas

Los QR apuntan a: `[URL_BASE]/[Pareja]/start.html`

## 🚀 Deployment

Subí la carpeta completa a tu servidor/hosting, asegurándote de que:

- La estructura de carpetas se mantenga intacta
- Los archivos `start.html` e `index.html` estén accesibles
- Las rutas relativas a `assets/aep-icon.png` funcionen

Ejemplo con GitHub Pages:

```
https://usuario.github.io/sanvalentin/Hugo_Milagros/start.html
```

## 💝 Propósito

Parte del proyecto "Regalables" - regalos digitales hechos con código y amor, con experiencia de marca profesional AEP.
