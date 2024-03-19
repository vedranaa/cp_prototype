---
layout: default
---

Note to teacher: here we loop and plot in each iteration. Next week, we use this as a motivation to introduce the concept of a lists.

We will work with discrete population models, which are mathematical models used to predict the future population size, and to investigate the effects of different factors on the population growth. When using such models, it is practical to plot the population size as a function of time. While we have not yet covered the topic of plotting, we have provided you with some code that you can use to visualize the population growth.


# SHEEP
10,000 sheep are to be released on two islands: 5,000 sheep are released on Lilleø and 5,000 sheep are released on Storø. Carrying capacity for Lilleø is estimated at 20,000 sheep, while carrying capacity for Storø is estimated at 50,000 sheep. Furthermore, it is known that with unlimited food resources the sheep population doubles every 10 years. Set up a mathematical model for the sheep population on Lilleø and one for the sheep population on Storeø. Use matplotlib to visualize the development of the sheep population over 100 years. Also examine two other alternatives. In the first scenario 1000 sheep will be released on Lilleø and 9000 sheep on Storeø. In the second, 9,000 sheep are released on Lilleø and 1,000 sheep on Storeø. Is there a difference between the two scenarios after 50 years? Is there a difference in the long run?


# WINE FLIES
The exercise is about wine flies and their reproduction. Theoretically, wine fly reproduction follows a discrete monopopulation model. To test this, an experiment is carried out which investigates how quickly wine flies reproduce. The experiment is carried out in a closed container with a capacity of 500 wine flies. At the start of the experiment, the container contains 150 flies and it is estimated that with unlimited resources the flies will multiply so that the component grows by 35% daily. An additional 10% of the flies are removed from the container each day.

Implement your mathematical model in a python function wine_fly_model with the following specifications.
def wine_fly_model(N_today, r, K, a, T) -> N_tommorow:
Input: N0, a number, the number of wine flies on day 0; r, a number, the daily per capita growth rate of houseflies; K, a number, the carrying capacity of the container; a, a number, percentage removal of wine flies; T, an integer, the number of days. Output: N, a length T+1 vector containing the number of wine flies for days 0 to T calculated using the model.
Make a script where you use the implemented function to calculate the population size of the flies over 14 days, and where you visualize the development. (Hint: use function bar.) Also use the function to confirm your conclusion about the equilibrium.