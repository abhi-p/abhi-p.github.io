---
title: "Autonomous agents for multiplayer SuperTuxCart"
collection: projects
urlslug: "ut-mscs-deep-learning-project"
type: "Academic"
permalink: /projects/2020-12-14-ut-mscs-deep-learning-project
contributors: "Autonomous agents for multiplayer SuperTuxCart"
contribution: "Generated about 2000 games in order to train the imitation learning model implementation. Worked on the Q-reinforcement learning algorithm that trained on the imitation model in order to create the final agent"
date: 2023-03-14
teaserurl: 'autonomous-agents-ice-hockey.png'
reporturl: 'https://abhi-p.github.io/files/SuperTuxKart_Report.pdf'
excerpt: "<br /> \
**Project Goal:** The goal of this project was to train an AI agent to play SuperTuxKart, competing with other trained agents in a 2v2 hockey game.<br /> \ <br /> \


**Project Description:**<br /> \

1) Approach: <br /> \ 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   i) Reinforcement Learning: Initially, we used Q-Learning for training. However, it struggled to learn optimal strategies. <br /> \ 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   ii) Imitation Learning: To overcome this, we trained the model using imitation learning on winning strategies derived from over 2000 games. <br /> \
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    iii) Hybrid Model: We then improved the reinforcement learning model by using the trained imitation model for initialization. This helped further refine the agent's strategy. <br /> \  <br /> \

2) Future Work:<br /> \ 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    i) Data Augmentation: Incorporate data augmentation during training to randomize initialization and improve robustness. <br /> \ 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ii) Internal State Controller: Explore the design of a hand-crafted internal state controller to compare its effectiveness against AI models.<br /> \ <br /> \

**Outcome:** Our project successfully demonstrated the application of a hybrid approach, combining imitation learning with reinforcement learning, to train an AI agent for SuperTuxKart. The refined agent showed improved performance in minimizing player-puck and puck-goal distances, paving the way for future enhancements and comparative studies with hand-crafted controllers.

This project consisted of training an agent to play SuperTuxKart to compete with the other trained agents in a 2v2 hockey game. Our strategy was to utilize reinforcement learning to minimize the player-puck and puck-goal distance. Our initial attempt at using Q Reinforcement Learning had trouble learning optimal strategies. Imitation Learning was then used to train the model on the winning strategies of over 2000 games. Our reinforcement learning model was then improved by using the imitation model as its initialization in order to further refine the agent's strategy. Future work can involve utilizing data augmentation during training in order to randomize initialization. A hand-crafted internal state controller could also be designed to see if it is superior to the AI models."
---
