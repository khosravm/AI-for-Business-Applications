- Optimizing the Flows in an E-Commerce Warehouse:

As the orders are placed by the customers online, an Autonomous Warehouse Robot is moving around the warehouse to collect the products for future deliveries. Briefly, our mission is to build an AI that will always take the shortest route to the top priority location, whatever the location it starts from.

- Minimizing Costs in Energy Consumption of a Data Center:

For this purpose, we will set up our own server environment, and we will build an AI that will be controlling the cooling/heating of the server so that it stays in an optimal range of temperatures while saving the maximum energy, therefore minimizing the costs.

To solve the problem we use a Deep Q-Learning model. Deep Q-Learning consists of combining Q-Learning to an Artiﬁcial Neural Network. Inputs are encoded vectors, each one deﬁning a state of the environment. These inputs go into an Artiﬁcial Neural Network, where the output is the action to play. More precisely, let’s say the game has n possible actions, the output layer of the neural network is comprised of n output neurons, each one corresponding to the Q-values of each action played in the current state. Then the action played is the one associated with the output neuron that has the highest Q-value (argmax), or the one returned by the softmax method. In our case we will use argmax. And since Q-values are real numbers, that makes our neural network an ANN for Regression.

Step 1: Building the Environment.

Step 2: Building the Brain.

Step 3: Implementing the DQN model.

Step 4: Training the AI.

Step 5: Testing the AI.

- Maximizing Revenue of an Online Retail Business:

Imagine an Online Retail Business that has million of customers. The board of executives has decided to take some action plan to maximize revenue even more. In our example, we will be facing n diﬀerent strategies, and our AI will have no idea of which is the best one, and absolutely no prior information on any of their conversion rates. However we will make the assumption that each of these n strategies does have a ﬁxed conversion rate. These strategies were carefully and smartly elaborated by the marketing team, and each of them has the same goal: convert the maximum clients to the premium plan. However, these n strategies are all diﬀerent. They have diﬀerent forms, diﬀerent packages, diﬀerent ads, and diﬀerent special deals to convince and persuade the clients to subscribe to the premium plan. Of course, the marketing team has no idea of which of these n strategies is the best one. But they want to ﬁgure it out as soon as possible, and by saving the maximum costs, which one has the highest conversion rate, because they know how ﬁnding and deploying that best strategy can signiﬁcantly maximize the revenues.

Online Learning is a special branch of Artiﬁcial Intelligence, where there is not much need of deﬁning the states and actions. Here, a state would simply be a speciﬁc customer onto whom we deploy a strategy, and the action would simply be the strategy selected.

The regret curve of a model is the plot of the diﬀerence between the best strategy and the deployed model, with respect to the rounds. [Each time a new customer connects to the online retail business website, that’s a new round i and we select one of our n strategies to attempt a conversion (subscription to the premium plan). The goal is to select the best strategy at each round, over many rounds.]
