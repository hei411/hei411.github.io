---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#
#layout: post
title: 'Wait-Free Task Solvability of Asynchronous Distributed Models'

#exclude: true
---
Status: In Progress  
Year: 2022  
Supervisors: [Prof. Marcelo Fiore](https://www.cl.cam.ac.uk/~mpf23/)

## Abstract
As modern programs become more concurrent, we need to design good mathematical models to reason about distributed algorithms. This report concerns two **incompatible** models studied by two separate lines of research on asynchronous distributed systems. On the one hand, we have [**HKR's model**](https://www.sciencedirect.com/book/9780124045781/distributed-computing-through-combinatorial-topology), whose task solvability power is well-studied and has deep connections with combinatorial topology, as captured by  the [Asynchronous Computability Theorem](https://cs.brown.edu/people/mph/HerlihyS99/p858-herlihy.pdf). On the other hand, we have [**GMT's model**](https://www-apr.lip6.fr/~tasson/doc/recherche/views.pdf), which is proven to possess a range of elegant geometric semantics. 

The contributions of this report are twofold. 

Firstly, we develop a **novel unified mathematical framework** that enables us to reason about both models at the same time. This framework is powerful enough to model various aspects of the distributed system, e.g. protocol types, execution traces, and solvability properties. 

Secondly, as a significant proof of concept, we utilize this framework to prove the Fundamental Theorem of Asynchronous Distributed Models, a **new result** that shows that a task description specification is solvable by HKR's model if and only if it is solvable by GMT's model. This fundamental theorem is the first result to unite the results of the two lines of research, allowing results on task solvability  of one model to be shared with the other. For example, the Asynchronous Computability Theorem can  be trivially extended to describe the task solvability power of GMT's model, in addition to HKR's model. 



## Results
You might be interested in the [report]({% link  projects/docs/adm.pdf %}) itself.