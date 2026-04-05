Aquí tienes una propuesta de archivo `README.md` basada en el análisis técnico del archivo `index.html` proporcionado.

---

# Constelación de Atributos de Moles · Análisis Tipográfico

Este proyecto es una herramienta educativa interactiva diseñada para el **Curso de Tipografía (Semana 3)**. Permite a los estudiantes y profesionales del diseño identificar, interpretar y analizar diversos especímenes tipográficos bajo la metodología de los "Atributos de Moles".

## 🚀 Características Principales

* **Exploración Multi-Tipográfica:** Paneles dedicados para diferentes familias y estilos (EPIC, Gift, RUBY, START).
* **Visualización por Capas:** Sistema interactivo de control de capas para analizar:
    * **Capa 1:** Efecto visual y estética.
    * **Capa 2:** Forma y anatomía tipográfica.
    * **Capa 3:** Estructura de la "Constelación".
* **Puntos de Interés (Hotspots):** Marcadores interactivos que despliegan información técnica detallada sobre remates, ejes de modulación, contraste y proporciones.
* **Tablas de Atributos:** Resúmenes técnicos que desglosan la semántica y la morfología de cada fuente.
* **Formulario de Evaluación:** Sección integrada para el análisis y envío de conclusiones.
* **Soporte PWA (Progressive Web App):** Configurado para ser instalado como una aplicación en dispositivos móviles y de escritorio.
* **Optimización para Impresión:** Estilos CSS específicos (`@media print`) para generar informes en PDF o papel de alta calidad.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica avanzada.
* **CSS3:** * Uso de **Variables CSS** (Custom Properties) para una gestión eficiente de colores y tipografías.
    * **Flexbox y CSS Grid** para un diseño responsivo y adaptable.
    * Animaciones y efectos de desenfoque (*backdrop-filter*).
* **JavaScript (Vanilla):** Lógica interactiva para el manejo de pestañas, control de visibilidad de capas y gestión del formulario.
* **Google Fonts:** Integración de las familias *Playfair Display*, *Space Mono* y *Outfit*.

## 📂 Estructura de Archivos Necesarios

Para que el proyecto funcione correctamente, se requieren los siguientes recursos mencionados en el código:

```text
/
├── index.html          # Archivo principal
├── manifest.json       # Configuración de PWA
├── icon-192.png        # Icono para la aplicación
├── Epic.jpg            # Imagen Capa 1 (Efecto) - Ejemplo EPIC
├── Epic_1.jpg          # Imagen Capa 2 (Anatomía) - Ejemplo EPIC
├── Epic_2.png          # Imagen Capa 3 (Constelación) - Ejemplo EPIC
└── ...                 # (Resto de imágenes para Gift, RUBY y START)
```

## ⚙️ Instalación y Uso

1.  Clona o descarga este repositorio.
2.  Asegúrate de contar con los archivos de imagen correspondientes en el mismo directorio.
3.  Abre el archivo `index.html` en cualquier navegador moderno.
4.  (Opcional) Si se sirve a través de HTTPS, aparecerá la opción "Instalar app" para usarlo sin conexión como PWA.

## 🎓 Contexto Académico

Desarrollado para la plataforma educativa de la **UTP (2026)**. El objetivo es facilitar el aprendizaje de la anatomía tipográfica y la interpretación de los valores comunicativos de la letra.

---
*Este archivo README fue generado automáticamente basado en el código fuente del proyecto.*