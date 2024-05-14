---
title: "Autonomous agents for realtime multiplayer ice-hockey"
collection: projects
urlslug: "ut-mscs-deep-learning-project"
type: "Academic"
permalink: /projects/2020-12-14-ut-mscs-deep-learning-project
contributors: "Abhishek Divekar, Jason Housman, Ankita Sinha, Alex Stoken"
contribution: "Generated training dataset of 40k images, coded and trained multi-task CenterNet model for vision stage of pipeline, wrote sections of report."
date: 2020-12-14
teaserurl: 'autonomous-agents-ice-hockey.png'
reporturl: 'https://adivekar-utexas.github.io/files/UTCS-Deep-Learning-Final-Autonomous-agents-for-realtime-multiplayer-ice-hockey.pdf'
excerpt: 'We design an automated agent to play 2-on-2 games in SuperTuxKart IceHockey. Our two-stage system composes of a &quot;vision&quot; stage which takes as input the image of the player&apos;s Field of View and predicts world-state attributes. For vision, we train a multi-task CenterNet model (with U-Net backend), to predict whether hockey puck was on-screen (classification), puck&apos;s x-y coordinates (aimpoint regression) and distance from player (regression). These are consumed by a &quot;controller&quot; stage which return actions that update the world-state by &quot;dribbling&quot; puck towards goal, or defending against the opposing AI team.'
---

Abhishek Divekar, Jason Housman, Ankita Sinha, Alex Stoken

**Description:**
We design an automated agent to play 2-on-2 games in SuperTuxKart IceHockey. Our two-stage system composes of a &quot;vision&quot; stage which takes as input the image of the player&apos;s Field of View and predicts world-state attributes. For vision, we train a multi-task CenterNet model (with U-Net backend), to predict whether hockey puck was on-screen (classification), puck&apos;s x-y coordinates (aimpoint regression) and distance from player (regression). These are consumed by a &quot;controller&quot; stage which return actions that update the world-state by &quot;dribbling&quot; puck towards goal, or defending against the opposing AI team.

**My contribution:**
Generated training dataset of 40k images, coded and trained multi-task CenterNet model for vision stage of pipeline, wrote sections of report.

**Resources:** [[Technical report](https://adivekar-utexas.github.io/files/UTCS-Deep-Learning-Final-Autonomous-agents-for-realtime-multiplayer-ice-hockey.pdf)]
