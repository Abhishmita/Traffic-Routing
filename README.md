# Hybrid Traffic Routing Algorithm for shortest path
Shortest path for traffic

This project is to find the shortest path for traffic in case of any non-recurring incidents. Most research paper on this subject is not based on Neural network. So, for this project, a neural network is created and its performance is evaluated with regards to Djikstra's Algorithm and Bellman-Ford algorithm. The non-recurring events are the ones which have no regularity. It comprises of accidents, road construction, locked roads, etc.

The idea is to take one souce and destination and find the shortest road from source to destination with addition of non-recurring incidents.

For this project: 
* A graph with 100 nodes are created and a source and destination node is allocated. 
* A neural nework is created to find the shortest distance from the source to destination and road accidents are simulated.
* There are three models created - 
  1. Using Djikstra's Algorithm
  2. Using Bellman-Ford Algorithm
  3. A neural network.
* These models are compared in normal traffic conditions and in conditions interrupted by road accidents.

After comparison of the results, it can be seen that the neural network outperforms both Djikstra's Algorithm and Bellman-Ford algorithm without accidents. Once accidents are introduced, theresults vary.
