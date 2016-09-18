# [Recursive Weighted Myriad Based Filters and Their Optimizations](http://ieeexplore.ieee.org/document/7457715/)

[Juan Marcos Ramirez](juanra@ula.ve) and [Jose Luis Paredes](https://www.eecis.udel.edu/~paredesj/)

IEEE Transactions on Signal Processing

## Abstract
This paper proposes two new recursive filtering structures based on the nonlinear myriad operator. First, we develop the general class of *recursive weighted myriad* (RWMy) filters as a robust filtering structure against impulsive noise that includes, as particular cases, a normalized version of the linear infinite impulse response (IIR) filter, the recursive mode-type filter, and the non-recursive weighted myriad filter. Secondly, considering the fact that the additive noise that contaminates the previous filter's outputs is no longer impulsive, we introduce a novel class of *recursive hybrid myriad* (RHMy) filters whose structure gathers the advantages of both the weighted myriad and the weighted mean in a single cost function to be minimized. Some properties of the RHMy filter are derived and a fast algorithm to compute the RHMy filter output is proposed. Furthermore, adaptive algorithms for designing the proposed recursive structures, under the equation error formulation framework, are developed. Finally, extensive numerical simulations are shown to evaluate both the iterative update of the adaptive algorithms and the performance of the proposed recursive filters against impulsive noise.

## Suplementary Material

### How to run the code

Download and uncompress the RecursiveMyriadBased folder. 

Under a Matlab environment run the following routines

	* FigTrainingBehavior.m generates Figure 4
	* FigComputationalCost.m generates Figure 4(f)
	* FigCleanChirpFiltering.m generates Figure 5
	* FigNoisyChirpFiltering.m generates Figure 6
	* TableNoisyChirp.m generates Table I
	* TableImageDenoising.m generates Table II
	* FigPLCSignals.m generates Figure 8
	* FigPLCMetrics.m generates Figure 9

## License and Referencing

This code package is licensed under the GPLv3 license. If you in any way use this code for research that results in publications, please cite our original article listed above.

## Reference
J.M. Ramírez and J.L. Paredes "Recursive Weighted Myriad Based Filters and their Optimizations" *IEEE Transactions on Signal Processing*, vol. 64, No. 15, pp. 4027 - 4039, 2016.


## Author

Juan Marcos Ramirez Rondon. Universidad de Los Andes. Merida, 5101, Venezuela. email: juanra@ula.ve or juanmarcos26@gmail.com

## Date

September 14, 2016
