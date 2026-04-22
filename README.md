# Repository description
A collection of very simple (entry-level) problems on probability, distributions and investing, solved using the Monte Carlo approach to business simulations in the form of an exercise. 

# Tech stack and methodology
1) Environment: **Microsoft Excel**
2) Approach: **Monte Carlo**
3) Theory: Key statistical distributions (Uniform, Triangular, Normal and Exponential)

# What does this repository contain
1) [distributions](distributions) file folder - it contains simple tasks of different nature solved in Microsoft Excel environment. Each results set was adequately compared to key types of statistical distributions.
2) [investment&dilemma](investment&dilemma) file folder - it contains more complicated tasks than the previous ones on the topic of investing and managing small business. Using Monte Carlo approach to simulations in Microsoft Excel environment, investment and management recommendations were formulated.
3) [MC_simple_simulations.xlsx](MC_simple_simulations.xlsx) - Excel file with very simple Monte Carlo simulations on coin tosses and ball draw probability. More of an personal exercise than project itself.

# [Investment&Dilemma](investment&dilemma) task content
1) [MC_trip_dilemma.xlsx](MC_trip_dilemma.xlsx):

> Blue Lagoon travel agency fears that in the summer of 2026 the demand for tours will be lower than in previous years. The agency forecasts a decrease of 20% to 40%, but hopes that the decrease will not be higher than 30%. The agency buys tours from tour operators for 4000 PLN and sells them to individual customers for 5500 PLN. The agency can return the unsold tours, but will receive only 2000 PLN/trip.The agency is considering buying from 80 to 180 trips from the tour operator for the summer season. Demand in previous years was as follows:
> 
> 140 clients Probability=0.3
> 
> 160 clients Probability=0.2
> 
> 180 clients Probability=0.15
> 
> 200 clients Probability=0.25
> 
> 220 clients Probability=0.1
>
For decline in demand value a triangular symmetric distribution was used  $x=a+\frac{b-a}{2}(U_1+U_2)$ 

2) [MC_investment_funds.xlsx](MC_investment_funds.xlsx):

> Kate decided to save money for a car and shechose different investment funds. Kate wants to invest 20,000 PLN in funds, putting 5000 PLN in each fund and keep money there for a year.
> 
> According to historical data:
>
> Fund A (secure fund): the past rate has varied according 
to a uniform distribution from 1.5% to 3%
>
> Fund B (moderate fund): the past rate has varied 
according to a triangular symmetric distribution from -4% 
to 8% (the most prob. Value = 2%)
>
> Fund C (aggressive fund): the rate so far has varied 
according to a normal distribution with a mean of 4% and 
a variation of 12%
>
> Fund D (the most aggressive fund) : the past rate has 
varied according to a normal distribution with a mean of 
5% and a variation of 6%
