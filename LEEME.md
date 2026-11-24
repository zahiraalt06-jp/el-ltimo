# El último secreto de Carlos

Aventura de plataformas 2D en HTML, CSS y JavaScript puro. Incluye una portada ilustrada navideña rosa pastel con los dos protagonistas. No necesita servidor ni dependencias para jugar.

## Probar en local
1. Descomprime el ZIP.
2. Abre `index.html` en un navegador moderno. Para evitar restricciones locales de algunos navegadores, también puedes usar la extensión Live Server de VS Code.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `style.css`, `script.js` y la carpeta `assets`.
3. En Settings → Pages, elige Deploy from a branch.
4. Selecciona `main` y `/ (root)`, guarda y espera a que GitHub publique la página.

## Controles
- Ordenador: flechas o A/D para moverse; Espacio, W o flecha arriba para saltar; Escape para pausar.
- Móvil: botones táctiles inferiores.
- Reinicio de mundo: botón ↻.

## Acceso
Contraseña: `Cádiz21`

## Personalización
- El mensaje final se puede cambiar en `script.js`, en `window.CARLOS_GAME_CUSTOM.finalMessage` y en el texto inicial de `#finalMessage`.
- Las preguntas y respuestas de cada mundo están en el array `worlds` al principio de `script.js`.
- Para añadir recuerdos, edita el array `extraQuestions` de `window.CARLOS_GAME_CUSTOM` y la lógica de preguntas.
- Los sprites del gatito se encuentran en `assets/` y se han recortado de la imagen de referencia facilitada.

## Nota de desarrollo
El juego incluye cinco mundos, física de salto y gravedad, cámara lateral, plataformas, enemigos, coleccionables, llave, puerta, cofre, punto de control, preguntas, prueba Morse, vidas, pausa, reinicio y controles táctiles. La música no se reproduce automáticamente; los efectos y sonidos pueden añadirse sin depender de archivos externos.


## Portada ilustrada
La portada está en `assets/portada-navidad.png`. La pantalla de acceso tiene un campo y botón reales superpuestos a la ilustración en ordenador; en móvil aparecen debajo de la imagen para que sean cómodos de usar.
