# Sleep & Calm App

MVP de una aplicación web de sueño y calma: alarma personalizada y rutina mañanera.

## Descripción

`Sleep & Calm` es una app web pensada para acompañar el descanso y el despertar.
La primera versión se centra en una pantalla de inicio que presenta el producto y
prepara el terreno para dos funciones principales:

- **Alarma personalizada:** configurar horarios y sonidos de despertar suaves.
- **Rutina mañanera:** una secuencia guiada para empezar el día con calma.

El proyecto es estático (HTML, CSS y JavaScript sin frameworks) para mantener el
MVP simple y fácil de ejecutar.

## Estructura

```text
.
├── index.html      Pantalla de inicio
├── src/
│   ├── styles.css  Estilos de la interfaz
│   └── app.js      Lógica de la aplicación (vacío por ahora)
├── docs/           Documentación del proyecto
├── mockups/        Diseños y referencias visuales
└── README.md
```

## Cómo ejecutarlo

No hay dependencias ni pasos de instalación. Abre `index.html` directamente en tu
navegador, o sirve la carpeta con un servidor local estático:

```bash
python3 -m http.server 8000
```

Después visita <http://localhost:8000>.

También puedes usar cualquier otro servidor estático, por ejemplo
`npx serve .`.
