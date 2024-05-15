---
title: "Autonomous agents for multiplayer SuperTuxCart"
collection: projects
urlslug: "ut-mscs-deep-learning-project"
type: "Academic"
permalink: /projects/2020-12-14-ut-mscs-deep-learning-project
contributors: "Abhishek Paul, Ayush Kumar, Mahir Moran"
contribution: "Generated about 2000 games in order to train the imitation learning model implementation. Worked on the Q-reinforcement learning algorithm that trained on the imitation model in order to create the final agent"
date: 2020-12-14
teaserurl: 'autonomous-agents-ice-hockey.png'
reporturl: 'https://abhi-p.github.io/files/SuperTuxKart_Report.pdf'
excerpt: 'This project consisted of training an agent to
play SuperTuxKart to compete with the other trained agents in a 2v2 hockey game. Our strategy was to utilize reinforcement learning to minimize the player-puck and puck-goal distance. Our initial attempt at using Q Reinforcement Learning had trouble learning optimal strategies. Imitation Learning was then used to train the model on the winning strategies of over 2000 games. Our reinforcement learning model was then improved by using the imitation model as its initialization in order to further refine the agent's strategy. Future work can involve utilizing data augmentation during training in order to randomize initialization. A hand-crafted internal state controller could also be designed to see if it is superior to the AI models.'
---

Abhishek Divekar, Jason Housman, Ankita Sinha, Alex Stoken

**Description:**
We design an automated agent to play 2-on-2 games in SuperTuxKart IceHockey. Our two-stage system composes of a &quot;vision&quot; stage which takes as input the image of the player&apos;s Field of View and predicts world-state attributes. For vision, we train a multi-task CenterNet model (with U-Net backend), to predict whether hockey puck was on-screen (classification), puck&apos;s x-y coordinates (aimpoint regression) and distance from player (regression). These are consumed by a &quot;controller&quot; stage which return actions that update the world-state by &quot;dribbling&quot; puck towards goal, or defending against the opposing AI team.

**My contribution:**
Generated training dataset of 40k images, coded and trained multi-task CenterNet model for vision stage of pipeline, wrote sections of report.

**Resources:** [[Technical report](https://adivekar-utexas.github.io/files/UTCS-Deep-Learning-Final-Autonomous-agents-for-realtime-multiplayer-ice-hockey.pdf)]
