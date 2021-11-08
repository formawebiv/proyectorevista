1. Creé index.html, styles.css, etc.
2. Busqué las imágenes necesarias y las puse en la carpeta img.
3. Busqué las fuentes y las descargué a la carpeta fonts o coìé el @import.
4. Creé la estructura en index.html.
5. Inserté el contenido en el html.
6. Escribí el css. 
7. Como la web no permité poner el 2º div del main a la dcha del 1º ni poner el texto del 3º div en su posición creé una nueva versión: indexb.html y stylesb.css.
8. En el indexb.html quité las clases e ids y solo dejé las más básicas.
9. En stylesb.css puse colores para distinguir los componentes de la web (divs, main, etc.).
10. Le di las proporciones a los divs (no pueden sumar 100% porque no deja que se alineen, hay que dejarle un % sobrante) de main y al footer.
11. Los divs solo se alinean uno al lado del otro si pongo inline-block pero se alinean en la base, para que se alineen en la parte superior en vez de eso le puse "display: flex; align-items: flex-start;".
12. El 3º div permite rotarse pero el texto no se escribe seguido. No responde a width ni height. Tampoco a text-orientation (sin rotarlo previamente).