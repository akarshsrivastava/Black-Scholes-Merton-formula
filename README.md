# Black-Scholes-Merton formula

## What Is the Black Scholes Model?
The Black Scholes model, also known as the Black-Scholes-Merton (BSM) model, is a mathematical model for pricing an options contract. In particular, the model estimates the variation over time of financial instruments. It assumes these instruments (such as stocks or futures) will have a lognormal distribution of prices. Using this assumption and factoring in other important variables, the equation derives the price of a call option.

The standard BSM model is only used to price European options and does not take into account that U.S. options could be exercised before the expiration date.

### The Black-Scholes model makes certain assumptions:

1. The option is European and can only be exercised at expiration.

2. No dividends are paid out during the life of the option.

3. Markets are efficient (i.e., market movements cannot be predicted).

4. There are no transaction costs in buying the option.

5. The risk-free rate and volatility of the underlying are known and constant.

6. The returns on the underlying asset are normally distributed.

### In mathematical notation:

#### 𝐂=𝑆𝑁(𝑑1)−𝐾𝑒−𝑟𝑡𝑁(𝑑2)

#### 𝑑1 = (ln(𝑆/𝐾)+(𝑟+𝑠𝑡𝑑𝑒𝑣^2/2)𝑡 ) / 𝑠.√𝑡

#### 𝑑2 = 𝑑1 − s⋅√𝑡 = (ln(𝑆/𝐾) + (𝑟−𝑠𝑡𝑑𝑒𝑣^2/2)𝑡) / 𝑠⋅√𝑡

where:

C=Call option price

S=Current stock (or other underlying) price

K=Strike price

r=Risk-free interest rate

t=Time to maturity

N=A normal distribution

s = asset volatility

### About the project

We will work to calculate call option premium for Microsoft (MSFT), with risk free rate, r, equal to 2.5% (0.025); the strike price, K, equal to 110.0; and the time horizon, T, equal to 1 year, respectively.

1. Download the data for Microsoft (‘MSFT’) from Yahoo Finance for the period ‘2000-1-1’ until today.

2. Understadning Standard Normal Distribution cummulative distribution function (cdf)

3. Calculating d1 and d2

4. Defining Black-Scholes-Merton formula using d1 and d2

5. Calculating Call option premium for Microsoft (MSFT) 
