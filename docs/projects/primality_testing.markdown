---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#
layout: post
title: 'Simple Primality Testing Algorithms for Undirected, Connected Graphs'

exclude: true
---
Status: Completed  
Year: 2019  
<!--(This was a project I did in high school, before I had any formal training in Algorithms. Therefore, this project may not be as impressive as the others...)-->


## Details

This is a report I wrote on primality testing algorithms for undirected connected graphs. 

In Graph Theory, we say that a subset of vertices in a graph is a [module](https://en.wikipedia.org/wiki/Modular_decomposition) if all members of the module have the same set of neighbors among vertices not in the set. We say a module is trivial if it is not the empty set, a singleton set or the set of all vertices. A graph is prime if all its modules are trivial. I designed and implemented a number of randomized algorithms for testing the primality of a graph and analyzed their soundness and time complexity. I also proposed an effective determinisitic algorithm that combines techniques from two randomized algorithms that runs in O(N²). The report and code can be found [here](https://github.com/hei411/HLMA).

## Results

The report was submitted to the Scientific Commuttee of Hang Lung Mathematics Award. Though I was not able to win any of the grand prizes, I was awarded a certificate for the academic standard achieved by the submitted research report.