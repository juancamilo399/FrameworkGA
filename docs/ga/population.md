# Population Class

Esta clase define una función la poblacion del modelo, esta tiene como objetivo inicializar la población la cual se debe de realizar de forma aletoria, además la representación depende del problema.

la definición genérica de esta clase se presenta a continuación: 

````
 Population(size,num_genes,context,individuals)
````

### Arguments

- size: cantidad de cromosomas o individuos
- num_genes: número de genes o cantidad de valores de cada individuo
- context: arreglo que contiene el contexto para algun problema (opcional)
- individuals: arreglo que representa los individuos

## initialize_population Method

Metodo abstracto que inicializa la población de individuos (individuals)

# AllelesBasedPopulation Class

Esta clase extiende population añadiendo atributos relacionados a una poblacion basada en alelos donde estos definen los posibles valores que pueden tener los genes de los individuos.

la definición de esta clase se presenta a continuación: 

````
 AllelesBasedPopulation(size,num_genes,alleles,allow_repeated_alleles,context)
````

### Arguments

- alleles: arreglo que indica el dominio de los valores de los individuos
- allow_repeated_alleles: valor booleano que indica si un individuo puede o no tener valores duplicados