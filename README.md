CarWashSimulation Summary:

A car wash simulator that emulates throughput to measure washing efficiency based off a variable set of data.
 
This assignment was mediated by the professor and teaching assistants of the class (Dr. Gerry Howser) who aided with the coding at varying points. THE FRAMEWORK FOR THE PROGRAM WAS PROVIDED BY KALAMAZOO COLLEGE and the students were assigned to fill in the missing pieces. It was written in Java using Eclipse.

The classes are described in detail below:

CarWashApplication - the main program that executes the other classes and prints the data.

CarWashSimulation - the main console that runs the simulation and holds the parameters of the model such as: opening and closing times, wash time per car, average wait time per car, and how many cars were in the queue after closing. Cars were placed in the queue based off random number generation and the "probability" of a car arriving at any given minute.

Car - an object that contains its arrival time to be used in determining relevant statistics.

Bay - keeps track of the one-car wash in terms of time till completion and queues the next one in line.

LLQueue - the queue class I created in a previous assignment that implements KQueue.

KQueue - the class provided by Kalamazoo College from which I implemented the LLQueue class.
