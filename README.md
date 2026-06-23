# Plantilla Metodológica de Investigación

Una aplicación web interactiva y autoguardable para diseñar, planificar y documentar investigaciones mediante encuestas. Permite estructurar tu proyecto de investigación desde la formulación del problema hasta la presentación de resultados, con generación automática de documentos Word.

## 🎯 ¿Qué hace?

Esta herramienta te guía a través de las **6 fases metodológicas** de un estudio basado en encuestas:

1. **Fase I — Planteamiento** (Problema y objetivos + Población objetivo)
2. **Fase II — Diseño muestral** (Tipo de muestreo, tamaño de muestra)
3. **Fase III — Instrumento** (Diseño del cuestionario y variables)
4. **Fase IV — Campo y análisis** (Recolección de datos, análisis estadístico)
5. **Fase V — Resultados** (Conclusiones e informe final)

## ✨ Características principales

- **Interfaz intuitiva de navegación lateral** con barra de progreso en tiempo real
- **Guardado automático** en el navegador (localStorage) — tu trabajo persiste entre sesiones
- **Múltiples tipos de campos**: 
  - Texto, números, áreas de texto
  - Selecciones (radio buttons, checkboxes, dropdowns)
  - Tags con Enter (para listas de items)
  - Calculadora integrada de tamaño de muestra
- **Exportación a Word (.docx)** — genera un documento profesional con toda la información
- **Indicador de progreso visual** — sabe cuándo has completado suficientemente cada sección
- **Diseño responsivo** — funciona en navegadores modernos (Chrome, Firefox, Edge)
- **Modo oscuro** — adapta automáticamente al tema de tu sistema

## 🚀 Cómo usar

1. **Descarga** el archivo `plantilla_investigacion.html`
2. **Abre en tu navegador** (doble clic en Windows/Mac, o clic derecho → Abrir con → Chrome/Firefox)
3. **Ingresa el nombre de tu proyecto** en el campo "Proyecto actual"
4. **Presiona "Comenzar"** para ir a la primera sección
5. **Completa cada sección** a tu ritmo — se guarda automáticamente
6. **Navega** con los botones "Anterior/Siguiente" o haz clic en las secciones en la barra lateral
7. **Cuando termines**, presiona "Exportar a Word" para descargar el documento final

### Puntos clave de cada sección

**Sección 1 — Problema y Objetivos:**
- Define tu pregunta de investigación central
- Establece objetivos general y específicos
- Plantea hipótesis y alcance del estudio

**Sección 2 — Población Objetivo:**
- Describe a quién va dirigida tu investigación
- Define criterios de inclusión/exclusión
- Especifica el tamaño del universo (si lo conoces)

**Sección 3 — Diseño Muestral:**
- Elige el tipo de muestreo más adecuado (aleatorio, estratificado, conglomerados, etc.)
- Usa la **calculadora integrada** para determinar el tamaño de muestra con base en:
  - Nivel de confianza (95%, 99%, 90%)
  - Error máximo permitido
  - Tamaño de la población (0 = infinita)

**Sección 4 — Instrumento:**
- Define tus variables principales a medir
- Especifica tipo y modalidad del cuestionario
- Selecciona las escalas de medición (Likert, dicotómica, etc.)
- Planifica la prueba piloto

**Sección 5 — Campo y Análisis:**
- Planifica el trabajo de campo (período, encuestadores, capacitación)
- Define mecanismos de control de calidad
- Especifica el tipo de análisis estadístico (frecuencias, correlaciones, regresiones, etc.)
- Lista variables de cruce para segmentación

**Sección 6 — Conclusiones:**
- Define la audiencia del informe final
- Estructura el documento (capítulos/secciones)
- Establece indicadores de éxito del estudio

## 📦 Contenido descargado

**Archivo único:** `plantilla_investigacion.html`

- Contiene toda la aplicación: interfaz, lógica, estilos y librería de exportación Word
- No requiere instalación ni dependencias externas
- Funciona offline (no necesita conexión a internet)
- Todo se guarda en tu navegador, tu datos son privados

## 🛠️ Tecnologías utilizadas

- **HTML5 / CSS3** — interfaz responsiva y moderna
- **JavaScript vanilla** — sin dependencias externas
- **localStorage API** — guardado automático
- **docx.js** — generación de documentos Word en el navegador
- **Matemática estadística** — cálculo de tamaño de muestra (fórmula de muestreo aleatorio simple)

## 📋 Bases teóricas

Esta plantilla se basa en metodologías de encuestas de fuentes reconocidas:

- **Manual para la elaboración de encuestas** — Gobierno de Cantabria
- **Encuestas: elementos para su diseño y análisis** — Grupo Editor

Cada fase está documentada con justificación metodológica y ejemplos.

## 🔄 Guardado automático

Tu trabajo se guarda automáticamente cada vez que escribes o cambias un valor. Verás un indicador "✓ Guardado" en la barra lateral que confirma cada guardado. 

**Para borrar todo el contenido**, usa el botón "🗑 Borrar todo" en la pantalla inicial (requiere confirmación).

## 📊 Exportación a Word

El botón "⬇ Exportar a Word" genera un documento profesional que incluye:

- Portada con nombre del proyecto y fecha
- 6 capítulos (uno por fase metodológica)
- Encabezados con el nombre del proyecto
- Pie de página con numeración
- Formato coherente (títulos azules, viñetas, espaciado profesional)
- Campos vacíos se exportan como líneas para completar a mano si es necesario

El archivo se descarga como `[NombreDelProyecto].docx` y se puede editar en Microsoft Word, Google Docs, LibreOffice, etc.

## ❓ Preguntas frecuentes

**¿Necesito conectarme a internet?**
No. La aplicación funciona completamente offline una vez que abres el archivo HTML.

**¿Mis datos son seguros?**
Sí. Todo se guarda localmente en tu navegador (localStorage), no se envía a ningún servidor.

**¿Puedo usar esto en mi teléfono?**
Sí, funciona en navegadores móviles (Chrome Mobile, Firefox Mobile), aunque la pantalla pequeña puede ser incómoda.

**¿Qué navegadores funcionan?**
Chrome, Firefox, Edge, Safari — cualquier navegador moderno (2020 en adelante).

**¿Puedo editar el Word generado?**
Completamente. Es un archivo .docx estándar que abre en cualquier editor de documentos.

**¿Cómo recupero mi trabajo si cierro la pestaña?**
Siempre está guardado. La próxima vez que abras el archivo, tu proyecto se recargará automáticamente.

## 📝 Notas de uso

- **Sé específico:** Cada campo es una oportunidad para precisar tu investigación. Cuanto más detallado, mejor será tu documento final.
- **Usa los ejemplos:** Los placeholders te dan ideas del tipo de información esperada.
- **La calculadora es una guía:** El tamaño de muestra recomendado es una base; ajusta según tu contexto y recursos.
- **Revisa antes de exportar:** El Word generado refleja exactamente lo que ingresaste, así que revisa la ortografía y consistencia.

## 🎓 Ideal para

- Estudiantes de investigación / tesis
- Investigadores independientes
- Profesionales en estudios de mercado
- Evaluadores de proyectos sociales
- Equipos de consultoría
- Cualquiera que necesite estructurar una investigación por encuesta

## 📄 Licencia

Este proyecto está disponible bajo licencia abierta. Úsalo, modifica y comparte libremente.

---

**Última actualización:** Junio 2026  
**Soporte:** Para errores o sugerencias, abre un issue en este repositorio.
