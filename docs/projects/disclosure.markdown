---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#
#layout: post
title: 'DisClosure: Decentralized Semantics and Verification for Languages with Closures'

#exclude: true
---
Status: Completed  
Year: 2022  
Supervisors: [Prof. Derek Dreyer](https://people.mpi-sws.org/~dreyer/) and [Mr. Michael Sammler](https://people.mpi-sws.org/~msammler/)

## Details
This project started during my internship at the [MPI-SWS](https://www.mpi-sws.org/).

DimSum (to be published in POPL 2023), developed by Michael, presents a novel way of reasoning about multi-language systems which addresses the limitations other methods incur. It provides a library of combinators, linkers, and wrappers which enables us to reason about the correctness of the overall system by first reasoning about individual components, and then linking them together. This method is considered decentralized as when we link components together, we only care about the events of interacting components, not the inner workings and memory model within each component. 

DimSum currently supports the interaction of two languages, an Assembly-like language with jumps and a C-like language with recursive functions. During my internship, I worked on using DimSum to verify systems that might contain a third kind of language: a ML-like functional language which supports closures. Currently, I am working on implementing a verified compiler from the ML functional language to the C-like language together with the wrappers that relates the source and target code.


-------------------
A [gem]({% link  projects/docs/closuremessage.jpg %}) I sent when I was still a young undergrad... 
