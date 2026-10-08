# Sauz Store 👕

Tienda de ropa en línea que permite a los clientes conocer el catálogo, registrarse, armar su carrito y comprar prendas de manera sencilla, y a la administración gestionar productos y pedidos.

## Problema que resuelve

Los pequeños negocios de ropa suelen vender solo por redes sociales y mensajes, lo que genera pedidos desordenados, poca visibilidad del inventario y una experiencia de compra lenta. **Sauz Store** centraliza el catálogo, las compras y la gestión de pedidos en una sola plataforma.

## Producto

Aplicación web de comercio electrónico (e-commerce) para una tienda de ropa, con catálogo de productos, cuentas de usuario, carrito de compras, pedidos y panel de administración.

## Equipo

| Integrante | Rol Scrum |
|------------|-----------|
| Juan Tirado Escobar | Product Owner |
| Josué Castro Bernal | Scrum Master |
| Juan Pablo Roman S. | Developer |
| Santiago Pérez | Developer |

## Tecnologías

### Desarrollo

| Capa | Tecnología | Uso en el proyecto |
|------|------------|--------------------|
| Frontend | HTML5 | Estructura de las páginas (catálogo, carrito, formularios). |
| Frontend | CSS3 | Estilos y diseño adaptable a computador y celular (responsive). |
| Frontend | JavaScript | Interactividad: validaciones, carrito, consumo de la API. |
| Backend | Node.js | Entorno de ejecución del servidor. |
| Backend | Express.js | API REST: usuarios, productos, carrito y pedidos. |
| Base de datos | MySQL | Almacenamiento de usuarios, productos, inventario y pedidos. |
| Seguridad | bcrypt + JWT | Cifrado de contraseñas y autenticación de sesiones. |

### Herramientas de trabajo

| Herramienta | Uso |
|-------------|-----|
| Git y GitHub | Control de versiones, documentación y repositorio del proyecto. |
| Jira | Gestión Scrum: backlog, Sprints y tablero. |
| Visual Studio Code | Editor de código y vista previa de Markdown. |
| Figma | Diseño de interfaces y prototipos. |
| Postman | Pruebas de la API. |
| Markdown | Formato de toda la documentación (`.md`). |

## Organización del repositorio

```
sauz-store/
├── README.md
├── .gitignore
├── docs/
│   ├── product-vision.md
│   ├── product-backlog.md
│   ├── user-stories.md
│   └── sprints/
│       └── sprint-01/
│           ├── sprint-backlog.md
│           └── sprint-review.md
└── src/
```

- `docs/product-backlog.md`: único Product Backlog, evoluciona durante todo el proyecto.
- `docs/user-stories.md`: detalle de las historias con criterios de aceptación.
- `docs/sprints/sprint-XX/`: documentación de cada Sprint (Sprint Backlog y Sprint Review).
- `src/`: código fuente del proyecto.

## Metodología

El proyecto se desarrolla utilizando **Scrum** y se organiza en diferentes **Sprints**. Cada Sprint tiene su propio Sprint Backlog y su Sprint Review.

## Estado actual

| Sprint | Estado | Versión |
|--------|--------|---------|
| Sprint 1 | En planificación (inicio: 19 de septiembre) | v0.1.0 |
