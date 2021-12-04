# FitnessFunction Class

Esta clase define la función de aptitud del modelo de algoritmo genetico. Esta función tiene como objetivo evaluar los individuos, las posibles soluciones al problema. Para esto se establece una métrica que permita evaluar que tan buena es una solución(individuo) para el problema propuesto, teniendo en cuenta que los mejores individuos deben tener valores más altos de esta métrica.

## apply Method

Metodo abstracto que calcula la función de aptitud para una población.

````
 apply(population)
````

### Arguments

- population: población para la que se le calculará la función de aptitud de cada individuo


Esta clase al ser abstracta debe ser extendida por otra donde se implemente el método apply, de esta manera se crea una clase que define la función de aptitud según el problema que se quiere resolver.
