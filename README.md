Demo Area: Implement a Test Generator
# 1 What you would like to achieve?
I want to implement a scenario where a self-driving car will travel from point A to point B. I wouldlike my implementation to work in such a way that, this self-driving car can safely reach the targetposition. My implementation will consist of two phases. In the first phase, I would like to traversethe car on an empty road and try to implement this without any traffic involved. In the secondphase, I will try to implement the same process including traffic. I will generate different types oftraffic (heavy, light, none, ”stau”) and test that the ego-car reaches safely to the respective targetdestination without any collision or it may fail to reach due to collisions. I will generate test scenariosthat will try to cause an ego-car to collide at the Intersection.'

# 2 Why is this relevant/important?
For a self-driving car to successfully reach its destination without any collision is the basic require-ment of Autonomous Vehicles. In this Seminar, we have studied many techniques where tests aregenerated to train the self-driving car to reach its destination without crashes. I would like toperform a practical test using tools where I can try and learn the existing methods and techniques.

# 3 How you plan to implement this?
I will manually select the map and spawn the ego-car using BeamNG. In the next step, I will give astart and target position for the ego-car to reach its destination with an intersection in the middle ofthe road. In the next step, I will generate traffic using a new Traffic API. I will also try to implementthat the ego-car reduces its speed in case there is a leading car ahead to avoid collisions.

# 4 Is this something that you invented or are you trying to replicate astudy in a paper?s
At first, I will try to replicate a study of a paper. Later on, if I have time, I would like to experimentmore in generating other scenarios that might be closed to real-world scenarios such as causing theego-car to drive off the lane
