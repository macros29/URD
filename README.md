# futureURD

<b> 2020-11-09: version 0.1 </b>  
I made changes to the source code of [URD](https://github.com/farrellja/URD) taking advantage of the R [future](https://github.com/HenrikBengtsson/future) package, so that some of the functions can be performed with multiple processes. 

Futurized functions include:
  - [floodPseudotime](R/flood.R) 
  - [simulateRandomWalk](R/diffusion.R)

Other changes:
  - [floodPseudotimeCalc](R/flood.R):
    No longer requires object and conduct calculations on sparseMatrix directly which significantly reduced memory footprint.
	
