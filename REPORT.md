# MLG - Practical Work 4

_Julien Biefer et Johanna Melly, juin 2019_

## Introduction

Dans ce laboratoire, nous devions configurer un algorithme génétique afin de résoudre le [Traveling Salesman Problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem). Pour ce faire, nous avons configuré un algorithme génétique et avons modifié sa configuration afin d'obtenir les meilleurs résultats.

## Best route

La meilleure route que nous avons trouvée passe par les villes suivantes :



Cela fait une distance de 

## Fitness function

La fonction de fitness que nous avons utilisée se base sur le calcul de la distance sphérique entre deux points consécutifs. Pour cela, nous avons donc parcouru la liste des chromosomes dans l'ordre et avons additionné la distance entre deux points consécutifs. Pour que cela soit satisfaisant, nous avons également défini notre algorithme génétique afin qu'il cherche non pas à maximiser le score mais à le minimiser.

## Solution encoding



## GA configuration



## Plots



## Conclusion

