# Selection Class

Esta clase define la forma en la que se realiza la mutación dada una población, dicha mutación se ve representada mediante algun cambio en un gen o valor.

la definición genérica de esta clase se presenta a continuación: 

````
 Mutation(p_mutation)
````

### Arguments

- p_mutation: probabilidad de mutación.

## apply Method

Metodo abstracto que realiza la mutación para un individuo.

````
 apply(individual)
````

### Arguments

- individual: individuo sobre el que se realizaria la mutación.

# ReplaceWithRandomAlleleMutation Class

Esta clase extiende Mutation donde se implementa la mutación mediante una estrategia basada en alelos, aqui dada la probabilidad de mutación cuando se determina que esta se debe realizar el nuevo valor del gen está dado por el arreglo de alelos.