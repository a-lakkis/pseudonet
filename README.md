# pseudonet

Pseudonet is an R package that provides a supervised approach for pseudo-time reconstruction to model a non-branching temporal cell process between two nodes. PseudoNet is a targeted pseudo-time reconstruction method in which the user can incorporate prior knowledge about the underlying process by  defining cells that are in the start and end nodes. A feedforward neural network is trained with these specified cells to predict the probability that a cell is in the end node of the temporal process based on its gene expression, and the predicted probability is used as a proxy for pseudo-time.

# Installation

Recomended installation procedure is as follows.

1. Install [R](https://www.r-project.org/)  on your computer if you do not already have it. (Note: some users may find it very useful to also download [RStudio](https://www.rstudio.com/products/rstudio/download/) but this is not necessary).
2. Download the package above 
```
PseudoNet_0_9_0.tar.gz

```
3. Run this line of code in R
```
install.packages('pseudonet_0.9.0.tar.gz', repos = NULL, type='source')

```

