# How To Optimize Single Object Image Classification Model Accuracy using Tensorflow 2
*Last updated: 01/09/2021*

<!-- using https://www.codecogs.com/latex/eqneditor.php -->
Table : Comparative Analysis of Classification Accuracy 
| activation function | loss function | Optimizer | learning rate | learning rate dacay | epoch | total loss | learning time | final accuracy |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Relu | mean square error(MSE) | Gradient descent | 0.01 | every 50, \*=0.96 | 100 | 0.001 | 2h | 98% |
||
||

<br>

Table : Loss Functin and Optimizer Equation
| activation function | activation equation | loss function | loss equation | Optimizer | Optimizer notation |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Relu | <img src="https://latex.codecogs.com/gif.latex?f(x)=max(0,x)" title="f(x)=max(0,x)" /> | MSE | <img src="https://latex.codecogs.com/svg.latex?\frac{1}{n}\sum_{1}^{n}\left&space;(&space;y_{i}-t_{i}\right&space;)^2" title="\frac{1}{n}\sum_{1}^{n}\left ( y_{i}-t_{i}\right )^2" /> | Gradient descent | <img src="https://latex.codecogs.com/gif.latex?W:=W-\alpha&space;\frac{\partial}{\partial&space;W}cost(W)" title="W:=W-\alpha \frac{\partial}{\partial W}cost(W)" /> |

<!--
Relu = https://www.codecogs.com/eqnedit.php?latex=f(x)=max(0,x)
MSE = https://www.codecogs.com/eqnedit.php?latex=\frac{1}{n}\sum_{1}^{n}\left&space;(&space;y_{i}-t_{i}\right&space;)^2
Gradient descent = https://www.codecogs.com/eqnedit.php?latex=W:=W-\alpha&space;\frac{\partial}{\partial&space;W}cost(W)
-->
