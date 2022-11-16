# crypdoku
A Sudoku example written in noir

This is a [noir](https://github.com/noir-lang/noir) program which can prove in **zero-knowledge** the solution to a given sudoku puzzle in less than 3000 ACIR gates (read constraints, although the real number of constraints will be bigger with R1CS proving systems, mainly because they do not support ACIR range gate, as well as with plonk-ish proving systems due to the width reduction step).
