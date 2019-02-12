# combinatorial-bandit
A method for selecting a subset of best performing items wrt black-box reward function: Given a set of 𝑁 items, the algorithm finds an optimal 𝑠𝑢𝑏𝑠𝑒𝑡 of a maximum number of 𝑘 items that maximizes a blackbox reward function 𝑓(𝑠𝑢𝑏𝑠𝑒𝑡).

The algorithm selects subsets based on the novelty of the selection while also considering what is the ratio of presence of an item that exist among the top previously tried subsets (by sorting them according to the rewards obtained).
