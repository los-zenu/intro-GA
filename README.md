# Introducción a los Algoritmos Geneticos

## Algoritmos geneticos

### Algoritmo genetico tradicional

A Continuación se muestra el pseudocodigo de un algoritmo genetico

```
BEGIN /* genetic algorithm */
  generate initial population
  compute fitness of each individual
  
  WHILE NOT finished DO
  BEGIN /* produce new generation */
    
    FOR population_size / 2 DO
    BEGIN /* reproductive cycle */
      select two individuals from old generation for mating
      /* biassed in favour of the fitter ones */
      recombine the two individuals to give two offspring
      compute fitness of the two offspring
      insert offspring in new generation
    END
    
    IF population has converged THEN
    finished := TRUE
  END
  
END
```


## Frameworks

1. **DEAP - Distributed Evolutionary Algorithms In Python** ([link](https://github.com/deap))
2. **PyGAD - Python Genetic Algorithm!** ([link](https://pygad.readthedocs.io/en/latest/#))
3. **sklearn-genetic** ([link](https://github.com/manuel-calzolari/sklearn-genetic))
4. **10 Python library for evolutionary and genetic algorithm** ([link](https://www.kaggle.com/getting-started/112297))

## Otros

1. https://www.kaggle.com/
2. https://datos.gob.es/es/blog/kaggle-y-otras-plataformas-alternativas-para-aprender-ciencia-de-datos
3. https://datascientest.com/es/kaggle-todo-lo-que-hay-que-saber-sobre-esta-plataforma
4. https://algodaily.com/lessons/introduction-to-genetic-algorithms-in-python
5. https://pymoo.org/
