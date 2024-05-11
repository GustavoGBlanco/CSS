### Formas de agregar CSS a nuestra pagina web ###

* Actualmente existen 3 maneras:

    #### 1. Estilos en Linea ####
    <p align="justify">Con este método, las instrucciones de diseño se integran directamente en el código fuente mediante una <strong>etiqueta de estilo</strong>.</p>
  
    ✅ Ventajas ✅
    * Mayor precedencia.

    ⛔ Desventajas ⛔
    * Difícil de mantener.
    * Difícil de escalar.

    ⌨️ Ejemplo - Código ⌨️
  
    `<h1 style="color:red">Hola mundo</h1>`

    🖥️ Ejemplo - funcional 🖥️

    [hacer click para ver el ejemplo funcional](https://plnkr.co/edit/UCKMjlHXfDqx9Vjs?open=lib%2Fscript.js)

    #### 2. Añadir CSS al principio del HTML ####
    <p align="justify">En este caso, se incluye el CSS en la cabecera del documento HTML. La <strong>etiqueta de estilo</strong> se convierte así en <strong>parte del elemento de cabecera</strong> y se aplica a todo el archivo.</p>
  
    ✅ Ventajas ✅
    * Mejor mantenibilidad y mejor escalabilidad a diferencia de los estilos en linea.

    ⛔ Desventajas ⛔
    * Difícil de mantener con respecto a integrar el CSS con un archivo externo.
    * Difícil de escalar con respecto a integrar el CSS con un archivo externo.
    * Por cada archivo HTML es necesario definir los estilos en la cabecera.

    ⌨️ Ejemplo - Código ⌨️
  
    `<style>
       h1 {color:blue;}
     </style>`

    🖥️ Ejemplo - funcional 🖥️

    [hacer click para ver el ejemplo funcional](https://plnkr.co/edit/jdVXUSwgpkdEjAg7?open=lib%2Fscript.js)

  #### 3. Integrar el CSS con un archivo externo ####
    <p align="justify">Este es posiblemente el mejor método para enlazar CSS en HTML. Un sitio web suele constar de muchas páginas, por lo que tiene sentido guardar las instrucciones de diseño en un archivo separado. Esto permite una separación limpia entre el contenido y el diseño y facilita el mantenimiento. El archivo exportado está simplemente vinculado al documento HTML. Se guarda la hoja de estilos externa con la extensión <i>.css</i> y luego se utiliza una etiqueta de enlace para incluirla en el archivo HTML.</p>
  
    ✅ Ventajas ✅
    * Mejor mantenibilidad y mejor escalabilidad.

    ⌨️ Ejemplo - Código ⌨️
  
    `<link rel="stylesheet" href="stylesheet.css">`

    🖥️ Ejemplo - funcional 🖥️

    [hacer click para ver el ejemplo funcional](https://plnkr.co/edit/TIJyaQOYRB9X7Hr4?open=lib%2Fscript.js)
