# tienda-comercio – Repositorio Base

Este repositorio contiene un proyecto funcional en PHP que simula una tienda de comercio electrónico básica. Está estructurado para ser utilizado como base en trabajos colaborativos usando Git y GitHub.

## Funcionalidades Incluidas

- Visualización de productos
- Agregado de productos al carrito
- Visualización de carrito
- Eliminación de productos del carrito

## Estructura de Carpetas

```
tienda_web_completa_v2/
├── index.php
├── conexion.php- 
├── estilo.css
├── .gitignore
└── README.md
```

## Requisitos

- PHP 7 o superior
- Servidor local (XAMPP, MAMP, WAMP)
- Navegador moderno

## Uso en Trabajo Colaborativo

Este repositorio puede ser **forkeado o clonado** por varios colaboradores. Se recomienda seguir el siguiente flujo de trabajo:

### Flujo de Trabajo en GitHub

1. Fork del repositorio original
2. Clonar el repositorio a local
3. Crear una rama de desarrollo: `git checkout -b dev`
4. Crear ramas temáticas: `git checkout -b carrito`, `git checkout -b pago`, etc.
5. Realizar commits claros y frecuentes
6. Crear Pull Requests hacia `dev`
7. Revisar código en equipo
8. Fusionar cambios y actualizar `main`

## Roles Sugeridos

| Rol             | Tareas                                       |
|----------------|----------------------------------------------|
| Backend Dev     | Integración PHP, validación, seguridad       |
| Frontend Dev    | CSS, diseño responsive                       |
| DB Designer     | Normalización e implementación de modelo BD  |
| QA Tester       | Pruebas de carrito, pagos, filtros, sesiones |

## Buenas Prácticas en Git

- Utiliza `.gitignore` para excluir archivos innecesarios
- Realiza `commits` temáticos (`feat:`, `fix:`, `docs:`, `refactor:`)
- Nunca trabajes directamente en `main`
- Documenta decisiones en `issues` y `pull requests`
- Usa etiquetas para organización (`bug`, `enhancement`, `question`, etc.)

## ¿Cómo descargar este proyecto?

- **Como ZIP**: Click en el botón verde “Code” y luego “Download ZIP”
- **Como Fork**: Click en “Fork” para replicar en tu cuenta GitHub

## Licencia

MIT License – uso libre con atribución

## Autor

Tienda – Comercio – 2025
