---
layout: page
title: "Adaptive Experimentation for Science: A more efficient alternative to design of experiments"
schedule: "October, 2022"
---

"Give me six hours to chop down a tree and I will spend the first four sharpening the axe." Design of experiments is a method for scientists to study the relationship between inputs and outputs for a complex system, however, it is limited in efficiency as it is typically “one-shot” approach that doesn’t leverage prior data to inform future decisions. On the other hand, adaptive experimentation relies on iteratively updating
beliefs about the behavior of a system to decide on the next experiment(s) to run. In this tutorial, we demonstrate how to apply state-of-the-art adaptive experimentation tools to a wide variety of tasks of increasing difficulty: closed-loop single-worker simulation optimization, machine learning model tuning, asynchronous/multi-worker optimization, multi-objective optimization, multi-fidelity optimization, offline (human-in-the-loop) batch optimization, and closed-loop robotic optimization (in-house demo provided!). The tutorial will largely focus on applying Bayesian optimization tools from Meta’s Adaptive Experimentation (Ax) Platform to scientific applications. By becoming proficient with the latest software and algorithms (“sharpening the axe”), you will be well-equipped to dramatically accelerate scientific discovery in your own research lab.

**Length:** Half day

**Intended Audience:** Intermediate

**Prerequisite Knowledge:** Python

### Presenters:
- [Sterling G. Baird](sterling.baird@utah.edu)
- [Dr. Taylor D. Sparks](sparks@eng.utah.edu)
- [Andrew Falkowski](AndrewRaineFalkowski@gmail.com)

### Biographies

Sterling is a PhD student in Dr. Taylor Sparks' materials informatics group at University of Utah focusing on materials discovery. He leverages state-of-the-art Bayesian optimization algorithms for a wide variety of materials science tasks, including model tuning, simulations, and wetlab experiments. Sterling taught Intro to Statistics for Metallurgical Engineers in 2021 virtually at the University of Utah and has had various roles as teaching assistant and as a writing tutor.

Dr. Sparks is the Associate Chair of Materials Science & Engineering at the University of Utah and co-host of Materialism Podcast. His research interests lie at the intersection of machine learning and materials science. Using materials informatics his group seeks to screen and synthesize exception candidate materials for energy applications such as batteries, thermoelectrics, and more. Dr. Sparks has taught many courses including Programming for Materials Science and Engineering, Materials Innovation, and Intro to Materials Informatics.

Andrew graduated from University of Utah with a master’s in Materials Science Engineering and works as a materials engineer for USNC-Tech. He has built machine learning models and optimization schemes such as genetic algorithms to accelerate the discovery of novel materials. He is also a co-creator of the Materialism Podcast with Dr. Sparks. Andrew has acted as a teaching assistant for various courses including Programming for Materials Science and Engineering taught at the University of Utah.

### Motivation

A popular logging saying goes "give me six hours to chop down a tree and I will spend the first four sharpening the axe." One interpretation of this saying is that investing time and capital into building up your skills and experience (“sharpen the axe”) is an important aspect of efficiently accomplishing tasks (“chop down a tree”). Unlike an axe which dulls with each blow, research skills are often transferable to other “research trees”. 
Have you ever been running a simulation or performing a wetlab experiment and felt overwhelmed by the sheer number of factors, both inside and outside of your circle of control, that influence the outcome? Common approaches might be to adjust one variable at a time or create a design of experiments table (for example, a full-factorial or gridded sampling of the input parameters). There are even online tools that aid with this, such as [https://www.desice.io](https://www.desice.io/) and [https://experimentaldesign.online](https://experimentaldesign.online). Perhaps surprisingly, these approaches can be far less efficient than even random search1. Fortunately, there are more efficient methods that are open-source, easy-to-use, and accessible to computational and experimental scientists alike. One such tool is Meta’s Adaptive Experimentation (Ax) Platform which provides extensive examples and tutorials while delivering state-of-the-art algorithms and performance. Like how you don’t need to know how to build a car to drive one, Ax makes it possible for you to use state-of-the-art Bayesian optimization tools without needing to understand the intricacies of Bayes theorem.

### Brief outline

In this tutorial, we will teach you how to implement adaptive experimentation for a wide variety of tasks using Meta’s Ax Platform:
- Simulations and wetlab experiment optimization
- Closed-loop (online), offline, and mixed online/offline optimization
- Single- and multi-fidelity optimization
- Single- and multi-objective optimization
- Integration with robotic systems

By becoming proficient with the latest software and algorithms (“sharpening the axe”), you will be well-equipped to dramatically accelerate scientific discovery in your own research lab.
