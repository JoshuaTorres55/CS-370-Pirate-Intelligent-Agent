# Pirate Intelligent Agent (Treasure Hunt Project)

## Author
Joshua Torres  
Southern New Hampshire University  
CS 370 Current Emerging Trends in Computer Science  

## Overview
This project focuses on building an intelligent agent that learns how to navigate a maze environment to reach a goal using reinforcement learning. The agent improves its performance over time by interacting with the environment and learning from the outcomes of its actions rather than following a predefined path.

## Brief Explanation of Work Completed
For this project, I worked with a partially developed codebase that included the structure of the maze environment, the rules of the game, and the representation of states and possible actions. The provided code established the foundation for how the agent interacts with the environment but did not include the learning logic.

I was responsible for implementing the reinforcement learning components that allow the agent to learn from experience. This included developing the deep Q learning algorithm, defining how the agent selects actions using an epsilon greedy policy, and implementing experience replay to improve training stability. I also contributed to the training process by structuring how the agent updates its knowledge over time using rewards and state transitions.

## Connection to Computer Science

### What Computer Scientists Do and Why It Matters
Computer scientists design systems that solve problems by processing data, automating decision making, and building algorithms that can operate efficiently at scale. This work is important because many real world problems involve large amounts of data or complexity that cannot be handled effectively through manual methods. In this project, the use of reinforcement learning demonstrates how machines can learn optimal behavior through interaction rather than explicit programming.

### How I Approach a Problem as a Computer Scientist
I approach problems by first understanding the structure of the system and identifying the key components involved. From there, I break the problem into smaller parts and determine which algorithms or techniques are most appropriate. In this case, instead of trying to hard code a solution to the maze, I focused on implementing a learning based approach where the agent improves through experience. This reflects a shift from static problem solving to adaptive systems.

### Ethical Responsibilities to the End User and Organization
When developing intelligent systems, I have a responsibility to ensure that they operate accurately, fairly, and transparently. This includes making sure that decisions made by the system can be understood and justified, especially in cases where outcomes affect users directly. There is also a responsibility to protect data and ensure that systems do not introduce bias or unintended consequences. In reinforcement learning systems, this means carefully designing reward structures and monitoring how the agent behaves during training to avoid harmful or misleading outcomes.

## Repository Link
https://github.com/JoshuaTorres55/CS-370-Pirate-Intelligent-Agent
