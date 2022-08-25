Git realiza un merge de tres vías, encontrando el ancestro común (también conocido como "merge base") de las dos ramas que estas mergeando.
Cuando invoque git mergetool en un conflicto, producirá estos archivos adecuados para alimentar una herramienta típica de combinación de 3 vías. De este modo:

Local: el lado "nuestro" del conflicto, es decir, nuestra rama (HEAD) que contendrá los resultados del merge.
Base: el ancestro común. útil para alimentar una herramienta de combinación de tres vías
Remote: El lado "suyo" del conflicto - la rama que estás mergenado con el HEAD.