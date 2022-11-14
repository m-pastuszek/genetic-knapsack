Knapsak Genetic Algorihm 
The knapsack problem is a problem in combinatorial optimization.Given a set of items, each with a weight and a value, determine the number of each item to include in a collection so that the total weight is less than or equal to a given limit and the total value is as large as possible

capacity.txt is capasicty of knapsack problem.(Maximum limit of weight total of genes.)
weight.txt is weight of geness.
values.txt is values of genes.
out.txt ist the output of the individual with the most ideal gene adhering to the limit.


How to run

1)First you should write the size of the population and how many times it will generation.
2)Decide the choice of parent to use: Roulette-wheel or k-tournamet.
3)How many genes will be crossover.(n-point crossover
4)The possibility of mutation is written.(bit-flip mutation)
5)One survival selection is decided: Age-based or Fitness-based
6)Optionally elitism is selected or not.
7)in the last step, the algorithm writes the individual with the best gene according to this scenario and constraint to the out.txt file.