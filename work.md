---
layout: work
title: Work
slug: /work
items:
  - title: Learning the Boltzmann distribution with Normalizing Flows
    image:
      src: /assets/img/work/water.png
      alt: water
    description: 
        Train normalizing flows to sample directly from the Boltzmann distribution, using only the energy function.
        Rather than using expensive samples generated from molecular dynamics.


- title: Reinforcement learning for process synthesis
  image:
    src: /assets/img/work/sand.png
    alt: sand
  description: 
        Chemical engineering process design within a simulator can be framed as a reinforcement learning (RL) problem,
        whereby an RL agent iteratively designs a process flowsheet in order to achieve a goal, such as maximising the 
        profitability of the process.
        Actions that the RL agent could take include adding units/streams (e.g. add reactor with a specific temperature, pressure catalyst etc)
         as well as changing the existing process by changing its topolicy (e.g. create recycle loop) and editing the parameters of existing unit operations.
        The key benifit of RL relative to conventional techniques is that it can tackle broader and more open ended problems that classic optimization approaches  
        that can only be applied to more narrow problems.
        For example, if provided with a fast and accurate simulator, and a large database of material compounds prices,
        .
        .
        .
        .
        Extended this to perform design using the COCO/ChemSep simulators, as well as Aspen simulator.
        Overall, commercial simulators are poorly designed for optimization with ML.
        Solution would be something along the lines of code a simulator in jax. 
        
---

<br />
<br />
