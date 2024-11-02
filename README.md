# Numerical-Methods-In-Finance

The selected seminars on the course ***Numerical Methods in Finance*** (2024) taught at the Lomonosv Moscow State University under the Vega Institute Foundation program. 

## Description

**Seminar 1.ipynb**

The problem of arbitrage-free interpolation of the implied volatility curve (or, respectively, option prices) is addressed. Despite the fact that arbitrage-free interpolation of 
option prices is quite natural, it implies notably strange and unexpected interpolation behavior of corresponding implied volatilities. Against, the interpolation of implied volatilities 
violates the arbitrage-free condition, but leads to an actually native interpolation of option prices. There is nothing left to do but combine both of these approaches.

**Seminar 2.ipynb**

Positive (semi-)definiteness of the correlation matrix is a vital condition for multi-dimensional Monte-Carlo simulations. However, the correlations estimations retrieved from the historical data 
may vioalate this condition. Hence, the problem of reducing a correlation matrix to a positive-definite matrix close to the original one arises. Secondly, multi-dimensional Monte-Carlo simulations 
involve sampling from a joint multidimensional distribution of underlying assets with given marginals. For that reason, gaussian copulae are used. 

## References

1. Jaeckel, Peter. Monte Carlo methods in finance. (2002).
   
2. Jäckel, Peter. Clamping Down on Arbitrage. *Wilmott* 2014: 54–69.

3. Delbourgo, Robert and J. A. Gregory. Shape Preserving Piecewise Rational Interpolation. *Siam Journal on Scientific and Statistical Computing* 6 (1985): 967-976.

4. Богачев, К. Практикум на ЭВМ. Методы решения линейных систем и нахождения собственных значений. (1998)


## Setup
The setup script creates a virtual environment with installed requirements.
See the manuals for detailed information regarding the workspace setup.

### Windows
Run `setup_windows.cmd` or run
```powershell
.\setup_windows.cmd
```

### macOS
Run:
```shell
chmod +x setup_macos.sh && ./setup_macos.sh
```


