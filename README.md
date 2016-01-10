Deploying Dense Networks for Maximal Energy Efficiency
==================

This is a code package is related to the follow scientific article:

Emil Björnson, Luca Sanguinetti, Marios Kountouris, “[Deploying Dense Networks for Maximal Energy Efficiency: Small Cells Meet Massive MIMO](http://arxiv.org/pdf/1505.01181),” IEEE Journal on Selected Areas in Communications, To appear.

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the article. *We encourage you to also perform reproducible research!*


##Abstract of Article

How would a cellular network designed for maximal energy efficiency look like? To answer this fundamental question, tools from stochastic geometry are used in this paper to model future cellular networks and obtain a new lower bound on the average uplink spectral efficiency. This enables us to formulate a tractable uplink energy efficiency (EE) maximization problem and solve it analytically  with respect to the density of base stations (BSs), the transmit power levels, the number of BS antennas and users per cell, and the pilot reuse factor. The closed-form expressions obtained from this general EE maximization framework provide valuable insights on the interplay between the optimization variables, hardware characteristics, and propagation environment. Small cells are proved to give high EE, but the EE improvement saturates quickly with the BS density. Interestingly, the maximal EE is achieved by also equipping the BSs with multiple antennas and operate in a "massive MIMO" fashion, where the array gain from coherent detection mitigates interference and the multiplexing of many users reduces the energy cost per user.


##Content of Code Package

The article contains 6 simulation figures, numbered from 2 to 7. These are generated by the Matlab scripts simulationFigure2.m, simulationFigures3and4.m, simulationFigure5.m, and simulationFigures6and7.m. The package also contains the Matlab script generateMonteCarlo.m that pregenerates Monte-Carlo simulation results, which are used in simulationFigure2.m to generate Figure 2.

See each file for further documentation.


##Acknowledgements

E.~Bj\"ornson was supported by ELLIIT and an Ingvar Carlsson Award. L.~Sanguinetti was funded by the People Programme (Marie Curie Actions) FP7 PIEF-GA-2012-330731 Dense4Green and was also supported by the ERC Starting Grant 305123 MORE.

##License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
