# <center>NEURAL-RUBIK</center>
### NEURAL RUBIK’S – SOLVING RUBIK’S CUBE USING NEURAL NETWORK  (HEURISTIC LEARNING)
### BY GUNASEGARRAN MAGADEVAN
### FACULTY OF COMPUTER SCIENCE AND INFORMATION TECHNOLOGY
### UNIVERSITY MALAYA
### 2019

## <center>CHAPTER 1</center>

## <center>INTRODUCTION</center>

### 1.3	Research Background
Neural networks have already proven to be able to cope with noisy and unstructured data like hand-written texts, images, sounds, classification of real-world objects based on incomplete description, and many others.
Recently, they also succeeded in several purely combinatorial domains like the game of AlphaGo. Nowadays, the program AlphaGo (D.Silver, 2016) that utilizes a deep neural net can beat top-class human players which was impossible just two years ago. No other approach is currently known to be able to play AlphaGo on such level. Neural Networks are also a key component of the best Poker engine DeepStack (Matej Moravcˇík, 2017) and several attempts have been made to use them for solving instances of Travelling Salesman Problem and other combinatorial problems (HieuPham, 2017).
In development, the machine learning approaches are already being used in several ways, for example to select the best search algorithm, preprocess the problem or to promote searching of promising areas.
Some attention has also been dedicated to heuristic learning, where the task is to automatically induce a heuristic function from training samples using a machine learning model. Models typically used in this area are very simple and are not finetuned for the specific problem. In most cases, they are only used as a black box.
With recent rapid development of deep learning models, many new possibilities are now available in this area. Learning algorithms now exist for efficient training of deep feed-forward networks and also many other types of Neural Networks have been developed and successfully used. For instance, there are Deep Recurrent Networks like Long Short – Term Memory (LSTM) (Francisco Javier Ordóñez,2016), Deep Convolutional Networks, and Neural Turing Machines (Ariel Felner, 2017).

### 1.4	Motivation
Rubik's Cube makes use of mathematical group theory, which has helped deduce certain algorithms. Furthermore, the fact that there are well-defined subgroups in the Rubik Cube group enables the puzzle to be learned and mastered by moving through different " difficulty levels " in itself. These subgroups are the principle underlying the computer cubing methods by Thistlethwaite and Kociemba, which solve the cube by further reducing it to another subgroup. (Boris Gorshenev, 2018)
There are now a number of solutions that can solve the cube in less than 100 steps. David Singmaster first published his solution in 1981, which solves the cube layer by layer. A team of researchers who worked with Google in July 2010 has proved that the so- called " number of God” (minimum number of moves to solve any) was 20. The Herbert Kociemba's Two-Phase Algorithm is the used for the most move optimal online Rubik's Cube solver programs, which typically calculates a solution of 20 steps or less.
Since all these types of solutions require very tough mathematics to fully understand why they work and needs tremendous amount of mathematical logics to develop new solutions, it is very difficult for ordinary people and even impossible for computers to develop these solutions automatically.
With the hope that computer systems will learn how to solve Rubik's Cube with some general algorithm and after carefully searching previous work online, finally found that the most popular methods that is used to solve Rubik's Cube problem are reinforcement learning. However, this technique requires so much computer power, therefore, finding alternatives. Since not found any neural network methods, believe that this is because the objective function space is too large for neural networks to learn, but it's still worth attempting because there's no relevant experiment to prove it - and at least this method to solve Rubik's Cube with neural networks could also fill the gap and provide data for this method.

### 1.5	Research Problem
•	Implementing heuristic learning to solve a given instance Rubik’s cube problem.
•	Minimal number of predictions of moves to solve a given instance Rubik’s cube.

### 1.6	 Objective
•	Using heuristic learning to construct a automatically solve a given instance Rubik’s cube problem.
•	Train neural network to predict a minimal number of moves required to solve a given case of Rubik’s cube.
•	Trained neural network as a heuristic distance estimator with a standard forward-search algorithm and compare the results with other heuristics.

### 1.7	Research Question
•	This research and experiment will show that the neural network, heuristic learning approach is competitive with state-of-the-art and might be the best choice in some use-case scenarios.



### 1.8	Research Delivery
•	To prove this research and experiment of neural network using heuristic learning is the best choice in some use-case scenarios to solve Rubik’s Cube.

### 1.9	Research Signification
•	Train a neural network to predict a minimal number of moves required to solve a given example of Rubik's cube. At that point utilize the trained system as a heuristic distance estimator with a standard forward-search algorithm and compare the results with other heuristics.
