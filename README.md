# Aplicación SIG en la Gestión del Riesgo

Este repositorio contiene el código fuente y los recursos multimedia del libro digital **"Aplicación SIG en la Gestión del Riesgo"**, desarrollado por la **Unidad Nacional para la Gestión del Riesgo de Desastres (UNGRD)** de Colombia. 

Este libro está diseñado como una guía técnica y práctica orientada a fortalecer las capacidades de las administraciones municipales y departamentales en el uso y la implementación de los Sistemas de Información Geográfica (SIG) aplicados a la Gestión del Riesgo de Desastres (GRD).

---

## 📖 Estructura del Libro

El libro se organiza en capítulos conceptuales y metodológicos, seguidos por anexos prácticos de aprendizaje paso a paso con diversas herramientas de software libre y de uso común:

### Capítulos Principales
1. **Introducción:** Introducción al rol de la tecnología geográfica en la gestión del riesgo.
2. **Marco Teórico de los SIG:** Evolución histórica mundial y nacional, definiciones y marco normativo colombiano aplicable.
3. **Usos y Aplicaciones de los SIG:** Conceptos de geodesia y cartografía (sistemas de referencia), modelos digitales (DEM, DSM, DTM) y tipos de datos (vector y raster).
4. **Fuentes de Información:** Repositorios y geoportales de descarga de imágenes satelitales (ópticas y radar) y geodatos gratuitos (Colombia en Mapas, Colombia OT, visores de emergencias).
5. **SIG Aplicado a la Gestión del Riesgo:** Implementación del análisis geoespacial en los tres procesos de la GRD: Conocimiento del Riesgo, Reducción del Riesgo y Manejo de Desastres.
6. **¿Cómo realizar un SIG en GRD a nivel municipal?:** Hoja de ruta para entes locales paso a paso (diagnóstico institucional, recolección de insumos, estandarización de la información y despliegue cartográfico).
7. **Recomendaciones Generales:** Directrices estratégicas para la sostenibilidad, el fortalecimiento de capacidades técnicas y la colaboración interinstitucional.
8. **Checklist de Seguimiento:** Herramienta práctica de control para la implementación de un SIG a nivel municipal.
9. **Insumos de Interés:** Enlaces y recursos de consulta adicional.
10. **Referencias:** Bibliografía y fuentes documentales del libro.

### Anexos Prácticos
* **Anexo 1: Descarga Imágenes Satelitales (QGIS):** Tutorial práctico paso a paso de uso de QGIS para descargar y procesar imágenes satelitales.
* **Anexo 2: Google Earth:** Guía de configuración básica, digitalización de capas (puntos, líneas y polígonos), perfiles de elevación e importación/exportación de archivos KML.
* **Anexo 3: Magna Pro:** Guía de instalación y conversión/transformación de coordenadas geográficas empleando el software MAGNA-SIRGAS Pro de la UNGRD/IGAC.
* **Anexo 4: KoboToolbox:** Configuración de encuestas digitales, recolección de datos georreferenciados en campo y descarga de registros.
* **Anexo 5: Avenza Maps:** Uso de la aplicación móvil Avenza Maps para la lectura cartográfica, orientación y levantamiento de información en terreno.

---

## 🛠️ Tecnologías y Estructura del Proyecto

El libro digital está desarrollado bajo la tecnología **[Quarto](https://quarto.org/)**, un sistema de publicación científica y técnica de código abierto basado en Pandoc.

### Archivos Clave del Repositorio:
* `_quarto.yml`: Archivo de configuración global de Quarto (título del libro, orden de capítulos, barra lateral, descargas en PDF, metadatos e inclusión de cabeceras).
* `index.qmd`: Página de inicio del libro interactivo con el párrafo de bienvenida, la portada flotante y la grilla interactiva de capítulos.
* `anexos.qmd`: Sección interactiva con tarjetas unificadas para acceder a los diferentes tutoriales.
* `custom.css`: Archivo de estilos personalizados CSS donde se definen los efectos hover, transiciones y la paleta de colores de la UNGRD (Azul `#223764` y Amarillo `#FAC718`).
* `caption-bold.html`: Fragmento HTML para dar un formato destacado en negrita a las etiquetas de figuras y tablas.
* `media/`: Directorio que contiene todas las imágenes, mapas y portadas utilizadas en cada uno de los capítulos.

---

## 🚀 Compilación y Visualización Local

Para compilar y visualizar este libro digital en tu entorno local, asegúrate de tener instalado **Quarto CLI** en tu equipo.

### Paso 1: Clonar el Repositorio
```bash
git clone https://github.com/scr-ungrd/aplicacion-sig-grd.git
cd aplicacion-sig-grd
```

### Paso 2: Vista Previa en Vivo (Hot-reload)
Este comando compila el proyecto de forma temporal y levanta un servidor de desarrollo en local para previsualizar los cambios en tiempo real en tu navegador web:
```bash
quarto preview
```
_Por defecto estará accesible en http://localhost:5427/_

### Paso 3: Renderizar / Generar la Versión Final HTML
Para compilar y empaquetar de forma definitiva todos los capítulos del libro digital en formato de sitio web HTML estático ejecute:
```bash
quarto render
```
Los archivos web generados listos para distribución o hosting en plataformas como GitHub Pages se guardarán en la carpeta:
* `_book/`

---

## 🏢 Créditos e Institución

Este proyecto es producido por la **Subdirección para el Conocimiento del Riesgo de Desastres** de la **Unidad Nacional para la Gestión del Riesgo de Desastres (UNGRD)** de Colombia. 

Para reportar problemas, proponer mejoras o contribuir en los contenidos, por favor abre un **Issue** o envía una solicitud de extracción (**Pull Request**) en el repositorio oficial.
