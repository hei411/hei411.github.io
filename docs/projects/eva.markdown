---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#
#layout: post
title: 'Eva: Type Systems for Functional Reactive Programming'
#exclude: true
---
Status: Completed 
Year: 2021  
Supervisor: [Prof. Alan Mycroft](https://www.cl.cam.ac.uk/~am21/)

## Details
This project is my undergraduate dissertation project at Cambridge. It concerns the design, implementation, and evaluation of a practical FRP language called *Eva*, whose type system is an enhanced version of a recent theoretical calculus called [Lively RaTT](https://arxiv.org/abs/2003.03170). Eva’s type system addresses the limitations of modern reactive programming languages by:

1. Certifying that all programs possess certain statically-known guarantees 
2. Ensuring no data resides in the heap for more than one time step during a program’s execution. Programs need to be explicit in their retention of data and, hence, do not exhibit any implicit space leaks.
3. Supporting polymorphism and treating all data as first-class citizens, making Eva expressive enough to implement a wide spectrum of programs.
4. Providing information on both safety and liveness properties of certain reactive programs via their types, a feature not provided by any other programming language.

As a significant proof of concept, I embedded [Lustre](https://www-verimag.imag.fr/The-Lustre-Programming-Language-and), an established dataflow programming language for implementing critical control software, as a domain-specific language within Eva via a program
transformation process called *Lust4Eva*.

## Results
You might be interested in the current version of the [source code](https://github.com/hei411/eva), or the [dissertation report]({% link  projects/docs/eva.pdf %}) itself.