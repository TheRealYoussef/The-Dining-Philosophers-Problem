A solution for the dining philosophers problem.

Problem description:

Consider five philosophers (numbered 0 to 4) who spend their lives thinking and eating. The philosophers share a circular table surrounded by five chairs, each belonging to one philosopher. In the center of the table is a bowl of rice, and the table is laid with five single chopsticks. When a philosopher thinks (for a random amount of time between 1 and 3 seconds), she does not interact with her colleagues. From time to time, a philosopher gets hungry and tries to pick up the two chopsticks that are closest to her (the chopsticksthat are between her and her left and right neighbors). A philosopher may pick up only one chopstick at a time. Obviously, she cannot pick up a chopstick that is already in the hand of a neighbor. When a hungry philosopher has both her chopsticks at the same time, she eats (for a random amount of time between 1 and 3 seconds) without releasing the chopsticks. When she is finished eating, she puts down both chopsticks and starts thinking again.

Solution:

Odd numbered philosophers pick up the right chopstick first and then the left, while even numbered philosophers pick up the left chopstick first and then the right.

How to run:

1- Open the terminal
2- cd to the directory containing the file "The-Dining-Philosophers-Problem.c", for example, if the file is located in "/home/therealyoussef/Documents/Operating-Systems", run "cd /home/therealyoussef/Documents/Operating-Systems"
3- Run "gcc -pthread The-Dining-Philosophers-Problem.c -o The-Dining-Philosophers-Problem"
4- Run "./The-Dining-Philosophers-Problem"
5- Press ctrl-c to end execution
