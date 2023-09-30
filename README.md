# Stochastic Volatility Inspired Parametrization

This project implements the SVI and surface SVI parametrization schemes introduced in [1], showing how to convert parameters
from one scheme to another and how to calibrate the parameters to raw option data while ensuring the absence of arbitrage. 

The eSSVI parametrization which takes the SSVI a step further and makes the correlation parameter maturity dependent thereby 
increasing the calibration accuracy for short maturites is also implemented following a robust calibration alorithm introduced in [2].



## References
<a id="1">[1]</a> 
Gatheral, J., Jacquier, A. (2013). 
Arbitrage-free SVI volatility surfaces. 
arXiv e-prints, arXiv:1204.06464.

<a id="2">[2]</a> 
Corbetta, J., Cohort, P., Laachir, I., Martini, C. (2019). 
Robust calibration and arbitrage-free interpolation of SSVI slices. 
Decisions in Economics and Finance, 42, 665–677.
