# Algoritmo genetico

## Genetic Algorithm Class

A continuación se detalla la definición de la clase GeneticAlgorithm. Esta clase tiene como atributos otros objetos de otras clases que representan los distintos componentes y operadores geneticos del modelo.

````
 GA(population,crossover,mutation,selection,fitnessFunction)
````

### Arguments

- population: Objeto de tipo Population que define la inicializacion de la población del algoritmo genetico.
- crossover: Objeto de tipo Crossover que define como se realiza el cruce de los individuos.
- mutation: Objeto de tipo Mutation que define como se realiza la mutación.
- selection: Objeto de tipo Selection que define como se realiza la selección.
- fitnessFunction: Objeto de tipo FitnessFunction que define la función de aptitud.

## Run Method

Metodo encargado de iniciar el algoritmo genetico.
    
````
 GA.run(iterations)
````

### Arguments

- iterations: Número de iteraciones.