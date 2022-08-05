# pseudonet

Pseudonet is an R package that provides a supervised approach for pseudo-time reconstruction to model a non-branching temporal cell process between two nodes. PseudoNet is a targeted pseudo-time reconstruction method in which the user can incorporate prior knowledge about the underlying process by  defining cells that are in the start and end nodes. A feedforward neural network is trained with these specified cells to predict the probability that a cell is in the end node of the temporal process based on its gene expression, and the predicted probability is used as a proxy for pseudo-time.

# Example


