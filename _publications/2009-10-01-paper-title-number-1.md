---
title: "Data-Driven Reinforcement Learning-based Forgetting Factor Iterative Learning Control"
collection: publications
category: manuscripts
permalink: /publication/2025-01-01-data-driven-rl-ff-ilc
excerpt: 
date: 2025-01-01
venue: "IEEE Transactions on Automation Science and Engineering"
slidesurl: ""                       # add URL if you have slides
paperurl: "https://ieeexplore.ieee.org/abstract/document/10879362"
bibtexurl:  
citation: 
---


-Abstract: 
In this paper, a data-driven control scheme is proposed by integrating both reinforcement learning (RL) and iterative learning control (ILC) methodologies. To address the limitations of conventional ILC and extend its applicability, a new approach called Forgetting Factor ILC (FFILC) has been introduced. The FFILC exhibits improved performance in the presence of non-repetitive noise, disturbances, and system uncertainties compared to traditional ILC.
This improvement is attributed to its ability to incorporate past data, enhancing adaptability to changing conditions. The paper provides a mathematical proof to analyze the convergence of FFILC. RL is utilized to determine the optimal forgetting factor. During initial iterations, larger errors are common, and a dynamic forgetting factor expedites convergence. In addition, RL equips the system with intelligence, facilitating superior adaptive performance and resilience as the environment changes throughout iterations. Simulations involving a quadrotor system and a drum-type boiler turbine plant demonstrate the superior performance of RL-FFILC compared to some advanced control methods.\\


-Note to Practitioners:
Industrial automation frequently involves repetitive processes, for which ILC is a suitable method to enhance performance. However, conventional ILC methods can be limited by special systems, non-repetitive disturbances and noise. For practitioners, RL-FFILC, as an intelligent robust control, offers a practical solution to enhance control performance in dynamic settings. This method is data-driven, meaning it does not require accurate model identification prior to implementation, making it suitable for applications where obtaining precise system models is difficult or impractical.

The effectiveness of RL-FFILC is demonstrated through simulations on two distinct systems, a quadrotor and a drum-type boiler turbine plant. The quadrotor, an autonomous system with six degrees of freedom, showcases the method's applicability to other autonomous systems with similar or fewer degrees of freedom. The drum-type boiler turbine plant, crucial in many industrial processes, highlights the relevance of the method in maintaining system stability and efficiency despite variable operational conditions. These applications fall within Cyber-Physical Systems (CPS), where intelligent data-driven control enhances adaptability and resilience.
