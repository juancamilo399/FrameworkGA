# Selection Class

Esta clase define la forma en la que se seleccionan los individuos que se van a reproducir para crear una nueva generación, para esto se tiene en cuenta la aptitud de cada individuo, donde los mejores individuos tienen más probabilidades de ser seleccionados.

## apply Method

Metodo abstracto que retorna los padres de la nueva generación según la estrategia utilizada

````
 apply(population,fitness)
````


### Arguments

- population: población sobre la cual se seleccionaran los individuos padres.
- fitness: arreglo conformado por el valor de aptitud de cada individuo.

# RouletteSelectionOperator Class

Esta clase extiende Selection donde se implementa la selección mediante un mecanismo conocido como selección por ruleta, este mecanismo selecciona los individuos simulando la tirada de uan ruleta donde los mejores individuos tienen más probabilidades de ser seleccionados.

# TournamentSelectionOperator Class

Esta clase extiende Selection donde se implementa la selección mediante un mecanismo conocido como selección por torneo, este mecanismo selecciona los individuos sometiendolos a un torneo de k participantes seleccionando al mejor, es decir el individuo con la mayor aptitud, formando de esta forma los padres de la nueva generación.
