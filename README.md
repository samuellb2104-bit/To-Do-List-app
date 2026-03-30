# 📝 To-Do List App

Una aplicación web moderna y responsiva para gestionar tus tareas diarias de forma eficiente.

![To-Do List Screenshot](screenshot.png)

## 🎯 Objetivo del Proyecto

Este proyecto fue creado para aprender y practicar:
- ✅ Manipulación del DOM con JavaScript vanilla
- ✅ Almacenamiento local con localStorage
- ✅ Diseño UI/UX moderno y responsivo
- ✅ Arquitectura de código limpio y mantenible
- ✅ Gestión de estados de aplicación

## ✨ Características Principales

- ✔️ **Agregar tareas** con prioridad (Baja, Media, Alta)
- ✔️ **Marcar tareas como completadas** con checkbox
- ✔️ **Eliminar tareas** individualmente
- ✔️ **Filtrar tareas** por estado (Todas, Pendientes, Completadas, Alta Prioridad)
- ✔️ **Estadísticas en tiempo real** (Total, Completadas, Pendientes)
- ✔️ **Almacenamiento persistente** - Las tareas se guardan en localStorage
- ✔️ **Diseño responsivo** - Se adapta a cualquier dispositivo
- ✔️ **Animaciones suaves** - Transiciones visuales atractivas
- ✔️ **Interfaz intuitiva** - Fácil de usar para cualquiera

## 🛠️ Tecnologías Utilizadas

```
Frontend:
- HTML5
- CSS3 (Grid, Flexbox, Gradientes, Animaciones)
- JavaScript Vanilla (ES6+)
- LocalStorage API

Herramientas:
- Visual Studio Code
- Git & GitHub
```

## 📋 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Sin dependencias externas
- Sin instalación requerida

## 🚀 Cómo Usar

### Opción 1: Descargar y abrir

1. Descarga el archivo `index.html`
2. Haz doble clic para abrirlo en tu navegador
3. ¡Listo! La app está lista para usar

### Opción 2: Clonar el repositorio

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/todo-list-app.git

# Navega a la carpeta
cd todo-list-app

# Abre el archivo en tu navegador
open index.html
```

### Opción 3: Servidor local (recomendado)

```bash
# Con Python 3
python -m http.server 8000

# Con Python 2
python -m SimpleHTTPServer 8000

# Con Node.js (si tienes http-server instalado)
npx http-server
```

Luego accede a `http://localhost:8000` en tu navegador.

## 💡 Cómo Funciona

### Agregar una tarea:
1. Escribe tu tarea en el campo de texto
2. Selecciona el nivel de prioridad
3. Presiona "Agregar" o Enter
4. ¡La tarea aparecerá en la lista!

### Marcar como completada:
- Haz clic en el checkbox junto a la tarea
- La tarea se tachará automáticamente

### Filtrar tareas:
- Usa los botones de filtro en la parte superior
- Opciones: Todas, Pendientes, Completadas, Alta Prioridad

### Eliminar tareas:
- Pasa el mouse sobre una tarea
- Haz clic en el botón "Eliminar"
- O usa "Limpiar completadas" para eliminar todas las completadas

## 🏗️ Estructura del Código

```
index.html
│
├── HEAD
│   └── Estilos CSS (inline)
│       ├── Variables CSS (colores, sombras)
│       ├── Estilos globales y responsive
│       ├── Componentes UI
│       └── Animaciones
│
└── BODY
    ├── HTML semántico
    │   ├── Header
    │   ├── Input & Filters
    │   ├── Stats
    │   └── Todo List
    │
    └── JavaScript
        ├── Variables globales
        ├── Event Listeners
        ├── Funciones principales
        │   ├── addTodo()
        │   ├── deleteTodo()
        │   ├── toggleTodo()
        │   ├── clearCompleted()
        │   └── renderTodos()
        └── Persistencia con localStorage
```

## 🎨 Características de Diseño

- **Gradientes modernos** - Colores vibrantes y atractivos
- **Tipografía clara** - Legibilidad óptima
- **Espaciado consistente** - Diseño limpio y ordenado
- **Animaciones suaves** - Transiciones de 0.3s
- **Estados interactivos** - Hover, focus, active bien definidos
- **Modo responsive** - Breakpoint en 600px para móviles
- **Scroll personalizado** - Scrollbar con estilo personalizado

## 📊 Estadísticas en Tiempo Real

La app muestra automáticamente:
- **Total de tareas** - Todas las tareas creadas
- **Completadas** - Tareas marcadas como hecho
- **Pendientes** - Tareas sin completar

## 💾 Almacenamiento Local

Los datos se guardan automáticamente en `localStorage` con la clave `todos`. Los datos persisten incluso después de cerrar el navegador.

### Estructura de datos:
```javascript
[
  {
    id: 1234567890,
    text: "Mi tarea importante",
    completed: false,
    priority: "high",
    createdAt: "30/3/2026"
  }
]
```

## 🔒 Validaciones

- ✅ No permite tareas vacías
- ✅ Previene inyección de HTML
- ✅ Confirmación antes de eliminar
- ✅ Confirmación antes de limpiar completadas

## 📱 Responsividad

Optimizado para:
- 📱 Móviles (320px+)
- 📱 Tablets (768px+)
- 💻 Escritorio (1024px+)

## 🚀 Mejoras Futuras

- [ ] Exportar tareas a PDF
- [ ] Sincronizar con backend/nube
- [ ] Categorías de tareas
- [ ] Recordatorios por email
- [ ] Tema oscuro/claro toggle
- [ ] Drag & drop para reordenar
- [ ] Tags/etiquetas
- [ ] Búsqueda avanzada

## 📸 Screenshots

### Vista Desktop
![Desktop View](screenshot-desktop.png)

### Vista Mobile
![Mobile View](screenshot-mobile.png)

## 🐛 Bugs Conocidos

Por el momento, ninguno conocido. Si encuentras alguno, por favor abre un **Issue**.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Ver archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Tu Nombre**
- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- LinkedIn: [tu-perfil](https://linkedin.com/in/tu-perfil)
- Email: tu-email@ejemplo.com

## 📚 Lecciones Aprendidas

Durante el desarrollo de este proyecto aprendí:

1. **Manipulación del DOM** - Cómo acceder, crear y modificar elementos HTML
2. **Event Handling** - Cómo responder a eventos del usuario (click, keypress, etc)
3. **Métodos de Array** - Uso de `.filter()`, `.find()`, `.map()` para manipular datos
4. **LocalStorage** - Cómo persistir datos en el navegador
5. **Diseño Responsivo** - Media queries y Flexbox/Grid para layouts adaptativos
6. **Animaciones CSS** - Transiciones y keyframes para efectos visuales
7. **Seguridad** - Escapar HTML para prevenir XSS
8. **Buenas Prácticas** - Código limpio, comentado y mantenible

## 🎓 Recursos Utilizados

- [MDN Web Docs - DOM](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model)
- [MDN Web Docs - LocalStorage](https://developer.mozilla.org/es/docs/Web/API/localStorage)
- [CSS Tricks - Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Tricks - Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [JavaScript.info](https://javascript.info/)

## 🙏 Agradecimientos

Gracias a todos los que proporcionan recursos de aprendizaje gratuito en internet.

---

⭐ Si te gusta este proyecto, considera darle una estrella en GitHub!

**Última actualización:** 30 de Marzo de 2026