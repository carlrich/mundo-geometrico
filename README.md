# 📐 Mundo Geométrico - Suite Educativa Interactiva

![Estado](https://img.shields.io/badge/Estado-Terminado-success?style=for-the-badge)
![Tecnología](https://img.shields.io/badge/HTML5-TailwindCSS-blue?style=for-the-badge)
![Lógica](https://img.shields.io/badge/JavaScript-SVG_Dinámico-yellow?style=for-the-badge)

Una colección de **4 juegos matemáticos interactivos** diseñados para estudiantes de primaria (6º grado). Este proyecto se enfoca en la enseñanza de la **Geometría** (clasificación, relación y medición de ángulos) utilizando tecnologías web modernas para crear una experiencia lúdica y visualmente atractiva.

🔗 **[Ver Demo en Vivo](TU_LINK_DE_GITHUB_PAGES_AQUI)**

## ✨ Características Destacadas

* **🎨 Gráficos SVG Dinámicos:** A diferencia de los juegos tradicionales que usan imágenes estáticas, este proyecto genera los ángulos y figuras **matemáticamente en tiempo real** usando JavaScript y SVG. ¡Los ejercicios nunca se repiten!
* **📏 Herramientas Virtuales:** Implementación de un transportador virtual con física de "acople" (*snapping*) para simular la medición real.
* **📱 Diseño "Soft UI" & Responsive:** Interfaz limpia, con colores suaves y sombras agradables, totalmente funcional en PC, Tablets y Móviles.
* **🧠 Feedback Inmediato:** Retroalimentación visual y sonora para reforzar el aprendizaje (aciertos y errores).

## 🎮 Lista de Juegos

### 1. 📐 Clasificador de Ángulos
* **Objetivo:** Aprender a identificar tipos de ángulos visualmente.
* **Mecánica:** Arrastrar tarjetas generadas dinámicamente a su categoría: Agudo, Recto, Obtuso o Cóncavo.
* **Nivel:** Básico.

### 2. 🤝 Parejas de Ángulos
* **Objetivo:** Entender la relación entre dos ángulos.
* **Conceptos:** Ángulos Complementarios (suman 90°) y Suplementarios (suman 180°).
* **Mecánica:** Clasificar pares de ángulos dibujados con precisión matemática.
* **Nivel:** Intermedio.

### 3. 📏 El Maestro Transportador
* **Objetivo:** Aprender a medir ángulos usando una herramienta.
* **Tecnología:** Uso de un transportador SVG semitransparente que se puede arrastrar y que se "adhiere" automáticamente al vértice del ángulo para facilitar la lectura.
* **Nivel:** Práctico.

### 4. 🕵️‍♂️ Detective de Ángulos (Encuentra la X)
* **Objetivo:** Aplicar lógica y álgebra simple para hallar valores desconocidos.
* **Mecánica:** Resolver ecuaciones visuales ($x + 30 = 90$) con un sistema de vidas y puntuación.
* **Nivel:** Desafío Lógico.

## 🛠️ Tecnologías Utilizadas

Este proyecto es una **Single Page Application (SPA)** ligera que no requiere backend.

* **Core:** HTML5 Semántico, CSS3, JavaScript (ES6+).
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/) (vía CDN) para un diseño rápido y consistente.
* **Gráficos:** **SVG (Scalable Vector Graphics)** generados proceduralmente mediante funciones trigonométricas en JS.
* **Librerías Externas:**
    * `SweetAlert2`: Para alertas y modales estéticos.
    * `Canvas Confetti`: Para efectos de celebración.
    * `Mobile Drag Drop`: Polyfill para garantizar el funcionamiento táctil en dispositivos móviles.

## 📦 Instalación y Uso

No requiere instalación de servidores ni dependencias complejas.

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/mundo-geometrico.git](https://github.com/carlrich/mundo-geometrico.git)
    ```
2.  **Ejecutar:**
    Simplemente abre el archivo `index.html` en tu navegador web favorito (Chrome, Firefox, Edge, Safari).

## 📄 Licencia

Este proyecto es de código abierto y está diseñado con fines educativos. Siéntete libre de usarlo y modificarlo.

---

Desarrollado con ❤️ para aprender matemáticas jugando.
