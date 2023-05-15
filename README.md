# W5_Data_visualization

Proyecto realizado para el curso de Data Analysis de Abril de 2023 en IronHack Madrid.

Objetivo: Búsqueda, descarga, preparación y presentación de una base de datos mediante interfaz gráfica, en este caso Tableau.

Elementos usados: Archivos .csv y .xlxs. Conexiones creadas manualmente, dado que ambos elementos provenían de fuentes diferentes.

Resultados: 2 Dashboards presentes en Tableau Public

-------------------------------------------------------------------------------------------------------------------


¡Bienvenido al mundo Pokémon!

![pokemon-professors-featured](https://github.com/Hrodward88/W5_Data_visualization/assets/129097999/fc5dc810-30f5-460d-b18f-9349a463788d)

¿Quieres ser todo un Profesor? ¿Un experto Combatiente? ¿Qué tal un Criador de renombre?

¡Pues has llegado al lugar apropiado!

Estás a punto de comenzar un viaje lleno de información, colores y gráficas que no van a estar donde corresponden una vez hagas click en los enlaces.

Pero lo primero es lo primero:

Para nutrir estas gráficas, han sido necesarias 2 bases de datos. Una en formato .csv, y otra en formato .xlxs.

Ambas tienen sus puntos fuertes y débiles, y no estaban hechas por las mismas personas.

Inicialmente, se comenzó con el archivo .csv. Contenía 3 enormes tablas: Evolution, Pokémon y TypeChart, cada una con elementos tanto categóricos como cuantificables. 

El principal problema de este archivo es su límite, puesto que solo abarcaba 718 Pokémon originales (778 incluyendo formas alternativas) y a priori parecía que las relaciones que podían establecerse no eran muy complejas.

Sin embargo,usando la Evolución como nexo común, se crearon una serie de Campos Calculados nuevos que nos permitieron:
- Contar todos los pokemon diferentes
- El número de ellos capaces de evolucionar
- El porcentaje que estos representaban sobre el total
- Aquellos incapaces de evolucionar
- El nivel medio de evolución.

Con estos campos como núcleo, y usando categrías preexistentes como el tipo, se han creado diversas gráficas que contabilizan el número de especies que evolucionan según el tipo, o las distintas condiciones necesarias para evolucionar. Ambas condiciones están includias como filtros, pudiendo así ver de manera más clara únicamente los datos que nos interesen. 
Además, se ha incluído un gráfico de pastel mostrando la distribución por tipos, y una gráfica mostrando todas las especies clasificadas en varios grupos o bins en base a sus características. Todo ello interactivo.

Todo ello puede encontrarse (O no, depende de cómo le de al servidor) en https://public.tableau.com/app/profile/eduardo.goicoechea/viz/PokemonDashboard-1/Dashboard3?publish=yes

Pero por si acaso, se puede encontrar una imagen del Dashboard en este mismo repositorio.

Sin embargo,no contento con esto, y teniendo en cuenta la información proporcionada por el archivo .xlxs, nos adentramos en otra aventura para extraer aún más información, esta vez teniendo en cuenta ya no solo el mayor número de especies disponible, si no también su rareza, y si su nombre ha cambiado desde la edición original al nombre internacional.

Para ello de nuevo creamos nuevos campos calculados, separamos en base a tipos, estatus de rareza de la especie, y características numéricas. Todo ello, ya no solo con más especies, pero a la vez con más detalle en las categorías, sabiendo ahora tanto los segundos tipos, como el porcentaje total que representan de las 898 especies diferentes.

De nuevo, todos los diagramas son controlables mediante los 3 sets de filtros, y los colores de las leyendas son uniformes a través de todo el dashboard. 

Esta herramienta proporcionará información tanto para aquellos que tratan de crear un equipo imbatible, como para aquellos que quieren saber todo lo posible sobre su especie favorita, o simplemente, conocer datos curiosos, como por ejemplo: ¿De que tipo es el pokemon con la defensa más alta de todas las generaciones?

https://public.tableau.com/app/profile/eduardo.goicoechea/viz/PokemonDashboard-Analytics2/Dashboard1?publish=yes

De nuevo, un screenshot está disponible en este repositorio.

Una vez hecho esto, solo queda jugar con los datos.

¡A por ello!


https://github.com/Hrodward88/W5_Data_visualization/assets/129097999/89967eb3-de7f-41ee-a977-3fa11aab6e80


