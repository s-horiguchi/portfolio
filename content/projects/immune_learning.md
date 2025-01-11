---
title: "Theory of The Immune System"
date: "2020-06-05T12:41:05-05:00"
image: "/img/immune.png"
link: ""
description: "Understanding the immune system with the learning theory."
tags: ["machine learning", "immune system"]
fact: ""
featured: true
sitemap:
    priority: 0.8
---


I built a mathematical model of the adaptive immune system by applying and extending the theories of machine learning. This project was a part of my master's thesis under the supervision of Tetsuya J. Kobayashi at the University of Tokyo. I received the Poster Award in [Annual Meeting of JSMB2020](/publications/jsmb2020/). The paper is still under preparation.


Kato and Kobayashi proposed a model of the adaptive immune system based on the reinforcement learning theory ([Phys. Rev. Research (2021)](https://doi.org/10.1103/PhysRevResearch.3.013222)).
They supposed that the immune system solves the following sequential decision-making problem: take the most effective action (activate the most effective immunological pathway) by observing the current state (self-antigens and/or pathogen-derived antigens).
One of the crucial ideas was to regard the helper T-cell clone-size distribution as the learnable parameter of this input-output relation. Then, the Burnet's clonal selection can be interpreted as the gradient descent of a loss function in a reinforcement learning algorithm.


I started the project to develop a model that incorporates the effect of the immigration of the T cells from the thymus to the peripheral pool. In terms of Marr's three levels in computational neuroscience, there are three questions to be answered:
 1. What is the task to be solved? What is the functional significance?
 2. Which algorithm is used to solve the task?
 3. How is the algorithm implemented?

The previous work by Kato and Kobayashi can be summarized as 
 1. Learning the current environment through interactions
 2. Reinforcement learning
 3. Clonal selection (proliferation and death of the peripheral T-cells)

My hypothesis is that
 1. Learning from the prior knowledge
 2. Transfer learning
 3. Thymic selection and export (immigration in the peripheral T-cell pool)
