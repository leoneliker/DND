# ⚔ Grimoire - D&D Character Sheet

Una hoja de personaje interactiva y moderna para D&D 5e, diseñada como proyecto personal para mejorar la experiencia de juego con una interfaz intuitiva y completamente personalizable.

## 📋 Descripción

**Grimoire** es una aplicación web de hoja de personaje para Dungeons & Dragons 5ª edición. Combina una estética medieval oscura con funcionalidad moderna, permitiendo gestionar todos los aspectos de tu personaje de forma ágil y eficiente.

### Características principales

- 📊 **Gestión completa de estadísticas**: Puntuaciones de capacidad, modificadores automáticos y bonificaciones
- ⚔️ **Sistema de combate**: Defensa, iniciativa, puntos de golpe y seguimiento de armas
- 🪄 **Magia**: Espacios de conjuro, hechizos, características especiales y modificadores
- 🎒 **Inventario**: Seguimiento de objetos, peso total y valores
- 🎭 **Habilidades**: Sistema de pericia con bonificaciones por competencia
- 📖 **Trasfondo**: Información personal, relaciones y características del personaje
- 💾 **Importar/Exportar**: Guarda tu personaje en JSON y cárgalo cuando lo necesites

## 🚀 Instalación

### Requisitos
- Un navegador moderno (Chrome, Firefox, Safari, Edge)
- No requiere instalación ni dependencias externas

### Uso

1. Descarga o clona los archivos del proyecto
2. Abre `index.html` en tu navegador
3. ¡Comienza a crear tu personaje!

## 📁 Estructura del Proyecto

```
DND/
├── index.html              # Archivo principal
├── styles.css              # Estilos globales
├── README.md              # Este archivo
├── ikael_ember.json       # Ejemplo de personaje guardado
├── js/
│   ├── data.js            # Funciones de datos y utilidades
│   └── ui.js              # Funciones UI y navegación
└── paginas/
    ├── general/
    │   └── general.js     # Identidad y estadísticas base
    ├── combate/
    │   └── combate.js     # Armadura, armas y combate
    ├── magia/
    │   └── magia.js       # Hechizos y características mágicas
    ├── inventario/
    │   └── inventario.js  # Objetos y equipo
    ├── habilidades/
    │   └── habilidades.js # Pericia y tiradas de salvación
    └── trasfondo/
        └── trasfondo.js   # Información personal y relaciones
```

## 🎮 Cómo usar

### Crear un nueva hoja
1. Abre `index.html`
2. Rellena los campos de identidad (nombre, raza, clase, etc.)
3. Introduce tus estadísticas de capacidad
4. Completa cada sección según sea necesario

### Guardar tu personaje
- Haz clic en el botón **"↑ Exportar"** en la cabecera
- Se descargarán los datos en un archivo JSON con el nombre de tu personaje

### Cargar un personaje existente
- Haz clic en el botón **"↓ Cargar"** en la cabecera
- Selecciona un archivo JSON guardado anteriormente

### Navegar entre secciones
Usa los botones de pestañas en la parte superior:
- **General**: Información básica y estadísticas
- **Combate**: Defensa, HP, iniciativa y armas
- **Magia**: Hechizos, espacios de conjuro y características mágicas
- **Inventario**: Objetos, equipo y seguimiento de peso
- **Habilidades**: Pericia y tiradas de salvación
- **Trasfondo**: Información personal y relaciones

## 🎨 Diseño

La aplicación utiliza:
- **Paleta de colores**: Temática medieval oscura con dorados y carmesí
- **Tipografía**: Cinzel para títulos, Crimson Pro para texto
- **Responsive**: Optimizado para dispositivos móviles
- **Animaciones suaves**: Transiciones y efectos visuales elegantes

## 🔧 Tecnología

- **HTML5**: Estructura semántica
- **CSS3**: Estilos avanzados con variables CSS
- **JavaScript vanilla**: Sin dependencias externas

## 📊 Formato de datos

Los personajes se guardan en formato JSON con la siguiente estructura:

```json
{
  "nombre": "Personaje",
  "raza": "Raza",
  "clase": {
    "tipo": "Clase",
    "subtipo": "Subtipo",
    "descripcion": "Descripción"
  },
  "nivel": 1,
  "estadisticas": {
    "fuerza": 10,
    "destreza": 10,
    ...
  },
  "CA": { "total": 10, "fuentes": [] },
  "vida": { "actual": 0, "maxima": 0, "temporal": 0 },
  "armas": [],
  "objetos": [],
  "habilidades_conjuros": [],
  ...
}
```

## 🚀 Mejoras futuras

Este es un proyecto en constante evolución. Posibles mejoras incluyen:

- [ ] Sistema de tiradas automáticas (con sonidos)
- [ ] Cálculo automático de CA según armadura
- [ ] Editor visual de hechizos
- [ ] Sincronización en la nube
- [ ] Modo oscuro/claro
- [ ] Soporte multiidioma
- [ ] Reporte PDF de hoja de personaje
- [ ] Integración con bases de datos de hechizos
- [ ] Generador aleatorio de personajes
- [ ] Historial de cambios

## 🤝 Contribuciones

Como proyecto personal, estoy abierto a sugerencias y mejoras. Si tienes ideas:

1. Prueba la aplicación
2. Envía feedback o mejoras
3. Sugiere nuevas características

## 📝 Notas

- Los datos se guardan localmente en tu navegador (localStorage)
- No se almacenan datos en servidores externos
- Los archivos JSON exportados son completamente portátiles

## ⚖️ Licencia

Proyecto personal. Hecho con ❤️ para disfrutar del juego de rol.

---

**Versión**: 1.0  
**Última actualización**: Abril 2026  
**Plataforma**: Navegador web

---

*¡Que disfrutes tu aventura!* ⚔️🐉
