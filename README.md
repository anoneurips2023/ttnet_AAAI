# TTnet submission NeurIPS 2023


This repository is the implementation Reproducibility part for submitted paper.

Among all the families of possible DCNN models, some are easier to manipulate than others. A perfect example is BNNs, which by binarizing the architecture, manage to find a friendly DCNN architecture that makes a lot of open problems easier. In our paper, we propose to follow the same strategy. We address the three open challenges presented above by introducing the first DCNN family that is specifically designed to be 


(i) amenable to fast complete/sound verification using any SAT solver

(ii) easily differentiable with standard machine learning framework and capable of compact logic gate CNN representation

(iii) scalable to large datasets.




Here is a visualisation of 1 block of 2D-CNN: the first layer has 3 filters with real-valued weigths and intermediate values, and the second layer has one filter with with real-valued weigths and  binary values.

![screen-gif](./gif/animatedGIF.gif)


## Tabular

Code & results are given at [https://github.com/anoicml2023/tab_res](https://github.com/anoicml2023/tab_res)

## Formal Verification

Code & results are given at [https://github.com/anoicml2023/Formal_verif](https://github.com/anoicml2023/Formal_verif)

## Logic Gate Boolean Circuit

Code & results are given at [https://github.com/anoicml2023/bool_gate_circuit](https://github.com/anoicml2023/bool_gate_circuit)

## Scalability

Code & results are given at [https://github.com/anoicml2023/scale_imagenet](https://github.com/anoicml2023/scale_imagenet)

Last Update: 16/05/2023
