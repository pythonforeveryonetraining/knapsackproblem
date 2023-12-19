Watch the [tutorial on youtube](https://www.youtube.com/watch?v=JK4RklA8dkk)

# Solve the Knapsack Problem with a Genetic Algorithm in Python

From a list with the following weights:

```
mushroom_weights = [34, 101, 120, 86, 112, 76, 21, 212, 653, 234, 122, 84, 312, 77, 54, 21]
```

A selection of mushrooms with a maximum total weight of 1300 needs to be made. With brute force, 65536 combinations have to be tested. The code in `main.py` approximates a good solution in just 30 steps.

```
=== ROUND 0, population 20 ===
Best weight: 1200
=== ROUND 1, population 20 ===
Best weight: 1267
=== ROUND 2, population 20 ===
Best weight: 1267
.
.
.
=== ROUND 27, population 20 ===
Best weight: 1300
=== ROUND 28, population 20 ===
Best weight: 1300
=== ROUND 29, population 20 ===
Best weight: 1300

Bag contains:
Total weight: 1300
Mushroom selection: [120, 112, 21, 212, 653, 84, 77, 21]
```
