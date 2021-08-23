## Collaborative Filtering Recommender Systems


El texto Collaborative Filtering Recommender Systems se basa en explicar qué es Collaborative Filtering (CF), definiéndolo como un proceso de filtrado o evaluación utilizando el rating de otras personas. Inicia contextualizando el proceso, destacando su naturaleza cotidiana, ya que, es un algoritmo que realizamos casi día a día con la simple recomendación boca-a-boca.

En general, el texto introduce al lector a las tareas en las que se ocupa CF, sus distintas funcionalidades, sus clases (memory-based y model-based), organizaciones (non-probabilistic y probabilistic), entre otras. De la misma forma, se describen las propiedades en que se basa CF para su correcto funcionamiento, las dificultades que enfrenta y el trade-off que existe entre rating explicito e implícito.

El capitulo Evaluation fue el que más me interesó, ya que describe los métodos de evaluación de los sistemas CF. Esto, básicamente, nos entrega parámetros o rúbricas para saber si el sistema está cumpliendo con sus objetivos. Sin embargo, me llamó la atención que no se ahondara en términos de sensibilidad y especificidad en el capítulo. Con esto me refiero, por ejemplo, a tasas de falsos positivos (FP) o falsos negativos (FN).

Entiendo que, en general, lo anterior se realiza en clasificadores de clases, en donde el dominio es discreto y limitado, por lo que en términos de rating sería más complejos. No obstante, sería interesante conocer qué existe hoy para evaluar estos casos. En particular, una idea muy básica que me surge es utilizar un thershold de rating que considere la predicción como correcta o incorrecta.

Lo descrito anteriormente me parece importante al pensarlo como usuario de un sistema CF. Ya que, tomando el mismo ejemplo que menciona el texto con MovieLens, me gustaría elegir el sistema que tienda a recomendarme menos películas que no me gustarán (menor FP), pero tampoco me gustaría que no me recomendara las películas que si me gustarían (menor FN).

Por otro lado, destaco positivamente del texto el capitulo Ongoing Challenges to Collaborative Filtering, en particular el apartado de Privacy and Security. Si bien es un tópico muy debatido últimamente, y,por lo tanto, conocido por muchos, me parece necesario que el lector conozca el problema ético detrás de la recopilación de datos. Además, esto destaca la necesidad de mantener y velar por la seguridad de los mismos sistemas.

En conclusión, creo que el texto tiene información valiosa para cualquier persona sin conocimientos en CF y, en particular, en cualquier sistema recomendador. Por lo tanto, es un buen punto de partida para los estudiantes, ya que entrega la información necesaria para comenzar a cuestionar, criticar o hasta filosofar entorno a la materia.
