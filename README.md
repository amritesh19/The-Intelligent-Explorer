# The-Intelligent-Explorer
![image](https://github.com/amritesh19/The-Intelligent-Explorer/blob/main/known-map.jpg)

It is a project based on AI class

Agent: Intelligent-Explorer

Environment: map(graph)/forest 


Agent : unknown, maximize score according to positive and negative reward based system

Environment : Static, discrete, single agent type

Goal : maximize reward

Reward-based
 - Positive reward for node 7 (temple) : +100
 - Negative reward for node 2 (trap) : -10

Reward-matrix = 

[[ -1.   0.  -1.  -1.  -1.  -1.  -1.  -1.]
 
 [  0.  -1. -10.  -1.  -1.   0.  -1.  -1.]
 
 [ -1.   0. -10.   0.  -1.  -1.  -1. 100.]
 
 [ -1.  -1.   0.  -1.  -1.  -1.  -1.  -1.]
 
 [ -1.  -1.  -1.  -1.  -1.   0.  -1. 100.]
 
 [ -1.   0.  -1.  -1.   0.  -1.   0.  -1.]
 
 [ -1.  -1.  -1.  -1.  -1.   0.  -1.  -1.]
 
 [ -1.  -1.   0.  -1.   0.  -1.  -1. 100.]]
 
 
Traning

![image](https://github.com/amritesh19/The-Intelligent-Explorer/blob/main/training.jpg)

No. of iterations : 700


Final path

![image](https://github.com/amritesh19/The-Intelligent-Explorer/blob/main/output.jpg)

