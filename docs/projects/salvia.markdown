---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#
layout: post
title: 'Salvia: Secure Aggregation for Flower'

exclude: true
---
Status: Completed  
Year: 2021  
Supervisors: [Dr. Nicolas Lane](http://niclane.org/) and [Dr. Pedro Porto Buarque de Gusmao](https://www.cst.cam.ac.uk/people/pp524)

## Details
This project was completed as part of the [Undergraduate Research Opportunities Programme](https://www.cst.cam.ac.uk/teaching/urop) internship at the [CaMLSys Lab](https://mlsys.cst.cam.ac.uk/). Secure Aggregation(SA) protocols in common Federated Learning(FL) frameworks have various limitations, including vulnerability to client dropouts or configuration difficulties. During the internship, I implemented [Salvia](https://github.com/hei411/flower/tree/secagg_experimental), a Secure Aggregation feature implemented within the open-source FL framework [Flower](https://flower.dev/), that aims to address those limitations:

1. Leveraging Flower's machine learning(ML) framework-agnositc property, Salvia can be used in a FL setting where clients run different ML platforms and pipelines independently.
2. Salvia exposes an intuitive and easy-to-use API, allowing uses to freely specify parameters to customize the SA protocol to match their deployment goals.
3. Using [SecAgg](https://research.google/pubs/pub47246/) and [SecAgg+](https://research.google/pubs/pub49303/) as the underlying protocol, Salvia is robust against client dropouts and has asymptotically low theoretical communication and computation overhead.


## Results
Experiment results show that Salvia's performance matches the expected complexities. Future work includes improving the secret sharing functions' efficiency, and enabling users to customize the weights factor and aggregation computation. A  [writeup](https://dl.acm.org/doi/10.1145/3488659.3493776 ) of the project has been accepted to appear in the [2nd International Workshop on Distributed Machine Learning](https://distributedml.org/).