# genetic programming
A simple sample of genetic programming

#Just a summary about the first assignment of AI.

I used genetic algorithm to achieve a simple TLU to solve the binary classification problem. The training set has 49 instances that each instance has 9 variables and 1 label named "training-set.csv".

Generally, one genetic algorithm includes several parts: 
1) Fitness function. This is the most important part and it infulence the accuracy of result directly. But to this question, it's simple. Just the proportion of the correct classfication.
2) Initialization function. Give the population one appropriate size and initialize all individuals by the random value in the solution space.
3）Copy function. Copy part of individuals to the next population. There are several way to choose these luky guys. In my program, I used binary tournament selection.
4) Crossover function. Chose parents and get children by crossover. I chose parents by binary tournament selection again and generate children by randomly choosing one position then exchange the genes of father's and mother's.
5) Mutation function. After copy and crossover, we get the new population. The individuals have the probibility to mutate. If mutation happen, giving a random value at random position of this individual.

P.S. If someone see it accidently and think there are mistakes on the readme or code, please tell me. Think you so much ;-)
