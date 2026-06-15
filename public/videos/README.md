# Carpeta de Videos

Coloca aquí tus videos locales en formato MP4.

## Pasos:

1. Coloca tus archivos de video en esta carpeta (ej: `demo1.mp4`, `demo2.mp4`)
2. En `src/components/galeria.astro`, añade la ruta en el array `imagenes`:

```javascript
const imagenes = [
  { img: "URL_IMAGEN", video: "/videos/demo1.mp4" },
  { img: "URL_IMAGEN", video: "/videos/demo2.mp4" }
];
```

## Formatos soportados:
- `.mp4` (recomendado)
- `.webm`
- `.ogg`

## Notas:
- Los videos son responsivos en móvil, tablet y desktop
- El video se abre en un modal cuando el usuario hace clic en "Ver Trabajo"
- Máximo recomendado: 10MB por video para carga rápida
