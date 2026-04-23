# CS 370 – Pirate Intelligent Agent (Reinforcement Learning)

## Project Overview
For this project, I worked on building a pirate intelligent agent using reinforcement learning. The goal was to train an agent to navigate an environment and make decisions based on rewards, similar to how real-world systems learn from outcomes over time.

I was provided with the base environment, including the maze/grid setup, reward structure, and some starter functions for training. The core reinforcement learning loop and environment interactions were already outlined. My work focused on implementing and tuning the learning model itself. I built out the neural network using Keras, handled the training process, adjusted parameters like exploration vs. exploitation, and worked through issues with performance and stability. I also added logic to improve how the agent learns from past experiences using replay memory.

## What I Learned
This project helped connect a lot of concepts from the course. At the start, reinforcement learning felt very similar to game examples, but this showed how it applies more broadly to decision-making problems. The biggest takeaway for me was that these systems don’t “think” — they learn patterns based on rewards and feedback over time. Getting the model to improve wasn’t just about writing code, it was about tuning how it learns.

It also reinforced how important data and feedback loops are. If the rewards or inputs aren’t set up correctly, the model won’t learn the right behavior. I saw this firsthand when the agent would get stuck or make poor decisions until I adjusted parameters.

## What Computer Scientists Do (and Why It Matters)
Computer scientists solve problems by building systems that can process data, make decisions, and improve over time. This matters because these systems are used everywhere — from automation on the shop floor to financial systems and AI tools. The work isn’t just about writing code, it’s about designing solutions that actually work in real-world conditions.

## How I Approach Problems
From this course, my approach is more structured than before. I break problems down into smaller parts, understand the inputs and outputs, and then figure out how the system should learn or respond. I also test and adjust instead of expecting things to work the first time. With reinforcement learning especially, iteration is a big part of the process.

## Ethical Responsibilities
There are definitely ethical responsibilities when building systems like this. One of the biggest is making sure the system is making decisions for the right reasons. In reinforcement learning, that comes down to how the reward function is designed. If it’s wrong, the system can learn behavior that looks correct but causes problems.

There’s also responsibility around transparency and trust. Users should understand what the system is doing and not rely on it blindly. From an organizational standpoint, data privacy and system reliability are also important. AI should support decision-making, not replace accountability.

## Repository Contents
- Jupyter Notebook: Pirate Intelligent Agent implementation
- README: Project summary and reflection (this file)

