Our goal is to take Prokudin-Gorskii photographs of each RGB plate and generate a color image by aligning them. The easiest way to align the plates is to exhaustively search over a window of possible displacements (say [-15,15] pixels), score each one using some image matching metric, and take the displacement with the best score.

