
Problem Definition:

You are a house painter that is available from day 1 . . . n (inclusive). You can only paint one
house in a day. It also only takes one day to paint a house. You are given m houses. For each
house i, you are also given startDay i and endDay i for i = 1, . . . , m. The house i can only be
painted on a day between startDay i and endDay i (inclusive). The given houses are already
sorted primarily on startDay and secondarily on endDay (in case of equality of the startDay).
You are tasked to find the maximum number of houses that you can paint.

Greedy Strategies:
For each of the following greedy strategies, you must i) design a O(n + m log(m)) algorithm; ii)
provide an instance where the strategy yields an optimal solution; iii) provide an instance where
the strategy does not yield an optimal solution or prove that it is an optimal strategy. Your
algorithm for Strat1 must have a Θ(n) running time. The remaining strategies must have a
Θ(n + m log(m)) running time.
Strat1 Iterate over each day starting from day 1 . . . n. For each day, among the unpainted houses
that are available to be painted on that day, paint the house that started being available
the earliest.
Strat2 Iterate over each day starting from day 1 . . . n. For each day, among the unpainted houses
that are available that day, paint the house that started being available the latest.
Strat3 Iterate over each day starting from day 1 . . . n. For each day, among the unpainted houses
that are available that day, paint the house that is available for the shortest duration.
Strat4 Iterate over each day starting from day 1 . . . n. For each day, among the unpainted houses
that are available that day, paint the house that will stop being available the earliest.
Hint:- While iterating over each day, maintain a priority queue that contains the unpainted
houses that are available to be painted on the current day.


Programming Tasks:
Once you complete the algorithm design tasks, you should have an implementation for each of
the following programming procedures:
Task1 Give an implementation of Strat1.
Task2 Give an implementation of Strat2.
Task3 Give an implementation of Strat3.
Task4 Give an implementation of Strat4.
