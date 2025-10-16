# Presupuestos Lindos 🧾

Una simple pero poderosa herramienta web para convertir el JSON del carrito de compras de Mexx en una tabla de presupuesto clara y fácil de compartir.

<br>

<p align="center">
  <a href="https://lautit.github.io/presupuesto-lindo/" target="_blank">
    <img src="https://img.shields.io/badge/Abrir%20Web-Presupuestos%20Lindos-blue?style=for-the-badge&logo=githubpages" alt="Abrir Web App">
  </a>
</p>

-----

### \#\# ¿Qué hace esta web?

Esta aplicación resuelve un problema simple: tomar los datos de un carrito de compras de la web de **Mexx Computación** y transformarlos en una "tablita linda" con productos, precios, cantidades y subtotales calculados.

El resultado final es una tabla limpia que se puede **copiar como imagen** para compartirla fácilmente por WhatsApp o cualquier otra red social.

-----

### \#\# ✨ Características Principales

  * **Procesador de JSON**: Pega el JSON del carrito de Mexx y la tabla se genera al instante.
  * **Cálculos automáticos**: Calcula el subtotal por cada producto y el **TOTAL** del presupuesto.
  * **Instrucciones Claras**: Un modal te guía paso a paso para crear un *bookmarklet* y extraer los datos de la web de Mexx sin errores.
  * **Exportar como Imagen**: Con un solo clic, se genera una imagen JPG/PNG de la tabla, que se copia a tu portapapeles, lista para pegar en cualquier chat.

-----

### \#\# 🚀 Cómo se usa

1.  **Genera el JSON**: Abre la web y sigue las **"Instrucciones para generar el JSON"**. Esto te guiará para crear un marcador especial (bookmarklet) en tu navegador.
2.  **Visita Mexx**: Ve a la página de tu carrito de compras en Mexx y haz clic en el marcador que creaste. El JSON se copiará automáticamente a tu portapapeles.
3.  **Pega el JSON**: Vuelve a la web de "Presupuestos Lindos" y pega el contenido en el recuadro de la izquierda. La tabla se generará al instante.
4.  **Copia la Imagen**: Haz clic en el botón **"Copiar como imagen"**. La tabla se guardará como una imagen en tu portapapeles.
5.  **Comparte**: ¡Pega la imagen en WhatsApp, Discord o donde quieras\!

-----

### \#\# 🛠️ Tecnologías Utilizadas

Este proyecto fue construido de la manera más sencilla posible, sin *frameworks* complejos ni pasos de compilación.

  * **HTML5**: Para la estructura básica de la web.
  * **Tailwind CSS (Play CDN)**: Para un diseño moderno y responsivo sin necesidad de escribir CSS tradicional.
  * **JavaScript (Vanilla)**: Para toda la lógica de la aplicación, desde procesar el JSON hasta manejar los eventos de los botones.
  * **`html2canvas`**: Una librería de JavaScript que permite "dibujar" el contenido de la tabla en una imagen para poder copiarla.