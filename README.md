# Appliance-scheduling-and-optimization
Using an artificial intelligence approach with metaheuristic algos to schedule interruptible power loads

# Problem representation

We create a curtailment schedule that specifies when an appliances should be turned off. The goal is to use meta-heuristic algorithms to generate an ideal schedule that will be our solution. 

The Solution is a (t,n) shaped matrix where t = number of hours and n = number of appliances. Solution(t, i) is equal to 1 if the i th appliance is being curtailed during the hour t.


![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/17d7c6eb-c06f-4e76-b06e-307df95648c6)

Each of the appliances is given a capacity and a curtailment rate which is indicative of the cost incurred from curtailing the appliance. The appliances also have an associated maximum off duration and minimum on duration that they must adhere to. They are also assigned a priority level which determines how often they are allowed to be interrupted.

![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/ef87133f-5e89-4011-99e0-e7d7708569c2)

# Objective function
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/00351c14-ad84-48e9-9417-a91867f66740)

## Components

![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/99c65090-2f23-4a7c-93a9-e9305d4f0df6)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/fa00023a-b407-4030-bfae-8137802e1210)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/f116fa04-1da4-425c-b8ce-d6ccc2d4d837)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/9edc40fb-c44b-49a3-a4d2-3af2441f75a4)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/48c28ec7-2d9c-41ab-92b7-921fc5440f75)

# Algos used
- Binary particle swarm optimization (BPSO)
- Differential evolution (DE)
- Harmonic search algorithm (HSA)

# Results
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/13bb44f4-78df-45ab-a2a8-5531ba4246fe)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/64b5ad0f-6a54-4a40-812c-f0b933d0b531)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/6cf164cb-df16-404b-a48b-427639d29b8a)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/c060aae3-0a07-40a2-9b5c-f62aad711d8d)
![image](https://github.com/Rohit-Annamaneni-1207/AI-Appliance-scheduling-and-optimization/assets/82631318/861cd99c-aa8e-4b58-a68c-358dc77ceb19)






