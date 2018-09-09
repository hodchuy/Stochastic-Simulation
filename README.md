# Stochastic-Simulation
The workbook aims to analyze Facebook stock movement in 2018 and try to use Montecarlo to simulate the stock movement in 360 days
The simulation use the Geometric Brownian Motion (GBM), meaning that the stock price follows a random walk and is consistent with (at the very least) the weak form of the efficient market hypothesis (EMH) – past price information can reflect future price.

- <img src="https://latex.codecogs.com/gif.latex?O_t=\text { Onset event at time bin } t " /> 

\begin{align}
\delta{S} & =  S (\mu \delta{t} + \sigma \epsilon \sqrt(\delta{t})
\end{align}

##### where: 
* "S" is the stock price,
* \begin{align} \mu \end{align} is the expected return, 
* \begin{align} \sigma \end{align} is the standard deviation of returns, 
* "t" is time
* \begin{align} \epsilon \end{align} is the random variable.

"The equation composes of two part: the drift and the shock.
For each time period, our model assumes the price will "drift" up by the expected return. But the drift will be shocked (added or subtracted) by a random shock. The random shock will be the standard deviation "s" multiplied by a random number "e." This is simply a way of scaling the standard deviation." (Investopedia - https://www.investopedia.com/articles/07/montecarlo.asp)
