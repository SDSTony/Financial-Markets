# Financial Markets Week1

This is a review on Week1 course of Financial Markets on Coursera. 

## Lesson1 - Welcome to the Course

Lectures for lesson1 are shown below

### Welcome Video

교수: Robert Shiller (Yale University)

finance is not about making money, it's about making things happen

Every human activity that's useful and important needs financing 

Want finance to be practical and useful



### Financial Markets Introduction

`Short description of the course`: Financial institutions are a pillar of civilized society, directing resources across space and time to their best uses, supporting and incentivizing people in their productive ventures, and managing the economic risks they take on. The workings of these institutions are important to comprehend if we are to predict their actions today and their evolution in the coming information age. 

This course is not about making money, it's about making things work. 

**If you make a lot of money in finance, you enjoyed it, -> give most of it away** (사회 환원?)



### Your Teaching Assistant, Arun!

Two ways of seeing Arun

1. chalk talks with Professor Shiller: detailed explanation on some concepts
2. TA timeout: highlight important concepts throughout the lecture



### Good and Evil

Finance can be used for good and evil -> you can be moral and ethical person

In poor countries, people are highly intrinsically interested in finance, it's a part of economic success. 

`Andrew Carnegie quote`: people who succeed are people with a natural, practical talent / business world selects them

When people succeed, which means make a lot of money in this context, their obligation is to give it away for the benefit of society. 

- give it away while still young
- if you amass money and get old, you may become self indulgent and it will eventually end up to the children
- this ruins children's life since they have no purpose in life

`Andrew Carnegie quote`: retire early and become philanthropists 

Two states in life

- before retire: actively gather wealth (run Microsoft)
- after retire: give it away (Gates foundation)

**This course is about how you can make a mark on your society, not a course about how to get rich**



## Lesson2

Lectures for lesson2 are shown below

### VaR and Stress Tests

VaR

- Variance: measure of it's variability
- Value at Risk: quantify risk of an investment or of a portfolio 
  - 1%, one-year value at risk of 10 million: there is a 1% chance that the portfolio will lose 10 million in one year
- Vector autoregression 



Stress test

- another measure for risk
- after the financial crisis it got popular
- method of assessing risks to firms or portfolio
- **look at details of the portfolio and ask what vulnerabilities there are for various kinds of financial crisis, not just look at its returns and how valuable they are** / not just look at historical revenue
- usually ordered by the government
- what would happen if the exchange rate changes
- what would happen if OO crisis comes
- scenario analysis
- always expect the worst, the home price fell under 13%, which was an expectation by another prof
- for companies, it might hurt their reputation if they reveal bad results from the stress tests, so they might hide or adjust it -> always questions institution reports and don't trust



### S&P 500

- used as a benchmark for return, average of 500 stocks
- law of large numbers: 큰 수의 법칙, as sample size grow, its mean gets closer to the average of the whole population
  - in stock, law of large numbers can't be observed, it should be a single line if it were to be observed (?)
  - in finance, indicates that a large entity which is growing rapidly cannot maintain that growth pace forever [reference](https://www.investopedia.com/terms/l/lawoflargenumbers.asp)
- LLN can't be seen in S&P 500, definite dependence across stocks

![image-20210123234451677](C:\Users\AhnSungJin\AppData\Roaming\Typora\typora-user-images\image-20210123234451677.png)

- `beta`: beta of a stock is a measure of how it relates to the stock market (above image)
  - if one, the stock tends to go up and down one for one according to the aggregated market
  - 기울기
- `market risk`: risk of the whole stock market

- `idiosyncratic risk`: Apple only risk  

- various of the return of a stock = beta

$$
Var_{stock-return} = beta^{2} \times Var_{market-return(market-risk)} + Var_{residuals-in-regression-model(idios-risk)}
$$

![image-20210124000729790](C:\Users\AhnSungJin\AppData\Roaming\Typora\typora-user-images\image-20210124000729790.png)

alpha = stock 수익률 에서 시장 수익률 뺀거 (시장초과수익률)

seekingalpha.com

[reference](https://www.investopedia.com/articles/investing/092115/alpha-and-beta-beginners.asp)



### Joe McNay Story

- 월마트, 인터넷 기업 투자해서 돈 많이 벌음 -> risk minimum, profit maximum



### Distribution and Outliers 

Normal distribution vs Cauchy distribution 

things can happen



### Chalk Talk - Covariance 

CAPM model 



## Lesson3

### Insurance Fundamentals 

- insurance: sharing risk, risk pooling

- `moral hazard`: dealt with partially deductions and co-insurance
  - if burning down house results more money from the insurance, than burn it

- `selection bias`: dealt with by group policies, by testing and referrals, and by mandatory government insurance
  - consumer knows more information about their state than insurance companies, so it raises selection bias on the side of insurance company
- insurance can be used to lure logical decisions on people (flood example)



### Insurance Milestones

- insurance developed due to the specific technical advances like the development of actuarial theory 
  - statistics on life tables



### Insurance is a Local Phenomenon

- insurance is often regulated at a local level 
- 큰 기업은 망하게 되면 정부가 도와주게 되는 동인을 제공한다

too big to fail -> documentary movie *Inside Job*

### Health Insurance

- need regulations to deal with moral hazards and selection bias



### Disasters

- katarina hurricane, haitian earthquake 
- create a system with right incentives
- do not build y our house on the flood plain
- there some things that can't be insured and government needs to do the job 
- Insurance premiums in Louisiana went up by 70% between 1997-2005, causing many people to cancel their insurance. -> 이 때 보험을 취소해야 할까? 아니면 정부가 보조 지원금을 줘야할까? 아니면 출혈을 감소하더라도 대출해서 계속 보험을 내야 할까? 
  - disaster는 개인이 계산할 수도 없고 예측할 수도 없다 
  - 꼭 살아야 하는데, insurance 들어야 하면 subsidy 제공하는것이 필요할 수 있다 



## Lesson4

### Eggs in One Basket

- managing risk thru diverse assets 
- risk is inherent to investing 
- we should care about the performance of the entire portfolio, not the individuals 
- mean and variance of portfolio matter 
- calculate each effect of the individual assets on the overall portfolio 
- need to check expected return of other assets and covariance 
- CAPM model 



### Salon - Risk

- hedge-funds are not allowed to promote themselves
- allowed to do risky things 
- black swan - Nassim Taleb
- labor market risk hedging 



### CAPM capital asset pricing model

- model for optimal portfolio
- does the past of any indication of the future? - sort of



### Chalk Talk: Beta

- in CAPM, systematic risk is more important than idios risk 
- systematic risk don't average out no matter how many diverse stocks you put in the portfolio
- gold has negative beta, ppl want to hold it during recessions 
- negative beta offset market shocks



### Chalk Talk: CAPM and Diversification 

- 



### Short Sales (공매도)

- I want to short the stock -> hold negative quantities of a stock by borrowing the shares and selling them

- do it when you think that the price is going to go down 
- 내가 100원에 빌리고 100원에 팔앗는데 stock 가격에 50원으로 떨어지면, 빌린 사람한테 50원만 갚으면 되니까 50원 수익 얻게됨
  - 그럼 빌릴 때 언제까지 갚을께 라고 계약 하나? - 
  - 왜냐면 빌려준 사람 입장에서는 갚에 높을 때 정산받고 싶어하지 않을까? - 



### Calculating the Optimal Portfolio

- people make mistakes
- what is rational?
- people get lazy, follow entertainment
- CAPM assumes that everyone follows it
  - 투자회사에서 주식 교육을 하는 거는 대의적인 목적도 있겠지만, 시장을 predictable하게 만들 수도?
- 

### Efficient Portfolio Frontier

![image-20210124083634773](C:\Users\AhnSungJin\AppData\Roaming\Typora\typora-user-images\image-20210124083634773.png)



### Chalk Talk - Gordon Growth Model

- Myron Gordon - gave a formula for the present value of a growing quantity 
- ![image-20210124084535887](C:\Users\AhnSungJin\AppData\Roaming\Typora\typora-user-images\image-20210124084535887.png)

r = rate of discount (이자율)

g = growth rate

at time 0, you should pay for PV calculated above as long as g is smaller than r

배당할인모형

![image-20210124085126015](C:\Users\AhnSungJin\AppData\Roaming\Typora\typora-user-images\image-20210124085126015.png)

[reference](https://www.investopedia.com/terms/g/gordongrowthmodel.asp)