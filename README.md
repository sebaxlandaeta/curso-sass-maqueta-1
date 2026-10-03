# 🎨 Maquetación Responsive con SASS - Desafío CADIF1

Este repositorio contiene la solución al desafío práctico del curso de **SASS** de la academia **CADIF1**. Consiste en la maquetación web *responsive* de una plantilla educacional ("Education"), construida utilizando HTML5 semántico y CSS preprocesado con **SASS (SCSS)**.

---

## 🌐 Demo en Vivo

Puedes ver el resultado del proyecto desplegado en el siguiente enlace: 👉 **[Ver Live Demo](https://sebaxlandaeta.github.io/curso-sass-maqueta-1/)**

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructuración semántica de la página.
- **SASS / SCSS**: Preprocesamiento de estilos e implementación de buenas prácticas de CSS.
- **CSS3**: Resultado preprocesado y listo para producción.
  
---

## 🚀 Funciones de SASS Implementadas

En este proyecto se aplicaron los conceptos fundamentales de SASS para optimizar el código CSS, haciéndolo más modular y reutilizable:

- **Archivos Parciales (`_header.scss`)**: Modularización de estilos del encabezado.
- **Variables SASS (`$variable`)**: Manejo centralizado de la paleta de colores.
- **Herencia de Estilos (`@extend`)**: Reutilización de una clase base `.card` para los contenedores repetitivos.
- **Anidamiento (Nesting)**: Estructuración jerárquica limpia alineada con el HTML.
- **Media Queries Anidados**: Adaptación *responsive* integrada directamente en las reglas de estilo.

---

## 📋 Requerimientos del Desafío (CADIF1)

1. **Maquetación fiel**: Replicar de forma idéntica el diseño propuesto.
2. **Preprocesamiento**: Escribir en `styles.scss` y compilarlo a un archivo ejecutable `styles.css`.
3. **Variables de color**: Definir variables para los cuadros *"Learning"*, *"Philosophy"*, *"Practice"* y *"Games"*.
4. **Módulo Parcial para el Header**: Crear el archivo `_header.scss` e importarlo dentro de `styles.scss`.
5. **Uso de `@extend`**: Aplicar herencia de estilos en los 4 cuadros para compartir propiedades y diferenciar solo el fondo.
