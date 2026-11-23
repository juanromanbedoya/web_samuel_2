# 🥗 NutriGuard

Aplicación web de **planes nutricionales para personal policial**, pensada para quienes trabajan por turnos. Recomienda comidas según el turno (mañana, tarde o noche), calcula las necesidades calóricas y permite armar planes diarios y semanales.

## ✨ Funcionalidades

- **Recomendaciones por turno**: comidas sugeridas para turnos de mañana (06–14), tarde (14–22) y noche (22–06).
- **Filtros y búsqueda**: por calorías y por nombre de comida o plan.
- **Detalle de cada comida**: calorías, macronutrientes (proteína, carbohidratos, grasa), porción, tiempo de preparación, ingredientes y pasos.
- **Planes predefinidos**: por ejemplo *Plan Básico Policial* o *Plan Alto Rendimiento*.
- **Calculadora** de necesidades calóricas.
- **Mis planes**: crear planes diarios y semanales y guardar favoritos (se guardan en el navegador con `localStorage`).
- **Modo claro / oscuro**, que respeta la preferencia del sistema.

## 🛠️ Tecnologías

HTML5 · CSS3 · JavaScript (sin frameworks ni dependencias)

## 🚀 Cómo ejecutarlo

No necesita instalación: clona el repositorio y abre `index.html` en el navegador.

```bash
git clone https://github.com/juan2052H/web_samuel_2.git
cd web_samuel_2
```

Si el navegador bloquea la carga de `planes_nutricionales.json` al abrir el archivo directamente, sírvelo con un servidor local:

```bash
npx serve .
# o
python -m http.server 8000
```

## 📁 Estructura

| Archivo | Contenido |
|---|---|
| `index.html` | Estructura de la página y secciones (Inicio, Planes, Calculadora, Mis planes) |
| `styles.css` | Estilos, incluido el tema oscuro |
| `script.js` | Lógica de la interfaz: navegación, filtros, modales, planes y tema |
| `data.js` | Base de datos de comidas por turno |
| `planes_nutricionales.json` | Planes nutricionales predefinidos |

## ⚠️ Aviso

La información nutricional es orientativa y no reemplaza la recomendación de un profesional de la salud.
