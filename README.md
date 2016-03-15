### What is Algorithmic Trading?
**Algorithmic trading**, also called *algo trading* and *blackbox trading* usually refers to trading systems that are heavily reliant on complictaed mathematical formulas and high-speed computer programs to determine trading strategies, opening and closing positions etc. These strategies use electronic platforms to enter trading orders with an algorithm which executes pre-programmed trading instructions incorporating a variety of variables such as timing, price, and volume. Algorithmic trading is widely used by investment banks, pension funds, mutual funds, hedge funds etc.

 
### Strategies
Algorithmic trading may be used in any investment strategy or trading strategy, including market making, inter-market spreading, arbitrage. The investment decision and implementation may be augmented at any stage with algorithmic support or may operate completely automatically. There are hundreds, if not thousands, of possible strategies utilized across the globe depending on the focus of the firm. For the purpose of this assignment I will discuss just a few of the most easily understood and most common strategies to give the reader an idea of what is involved.

- **Pairs Trading:**
Pairs trading is a long-short, ideally market-neutral strategy which enables traders to profit from discrepancies in the value of close substitutes. In simpler terms, for example, consider two mining companies with very similar cash flows, net profit etc. Consider the siyuation where one company trades for a P/E of 8, while the other trades for a P/E of 14. In this scenario one would buy the (cheaper) first company and short the stock of the second (more expensive) company.

- **Arbitrage:**
Arbitrage is possible when one of three conditions is met:

1. The same asset does not trade at the same price on all markets (the "law of one price" is temporarily violated).

2. Two assets with identical cash flows do not trade at the same price.

3. An asset with a known price in the future does not today trade at its future price discounted at the risk-free interest rate.

##### Put-Call Parity 
Put-call parity is a principle that defines the relationship between the price of European put options and European call options of the same class, that is, with the same underlying asset, strike price and expiration date. Put-call parity states that simultaneously holding a short European put and long European call of the same class will deliver the same return as holding one forward contract on the same underlying asset, with the same expiration and a forward price equal to the option's strike price. If the prices of the put and call options diverge so that this relationship does not hold, an arbitrage opportunity exists, meaning that sophisticated traders can earn a theoretically risk-free profit. Such opportunities are uncommon and short-lived in liquid markets.

The equation expressing put-call parity is:

C + PV(x) = P + S

where:

<pre><code

<\code><\pre>

- **Mean Reversion:**
It is generally considered that a stock's high and low prices, generally caused by short-term movements as a result of earnings calls, news releases etc. are temporary, and that a stock's price tends to have an average price over time. This would be a moving average either increasing or decreasing. An example of a mean-reverting process is the Vasicek interest rate model which I actually discussed and modeled via stochastic differential equations for my final year project.

### Low-Latency Trading
Network-induced latency, a synonym for delay, measured in one-way delay or round-trip time, is normally defined as how much time it takes for data to travel from one point to another. Low latency trading refers to the algorithmic trading systems and network routes used by financial institutions connecting to stock exchanges and Electronic communication networks (ECNs) to rapidly execute financial transactions. Most HFT firms depend on low latency execution of their trading strategies.

### Controversy and Concerns
A lot of concern has arisen in recent years with the rise of high-frequency trading, a form of algorithmic trading whose key attributes are the use of highly sophisticated algorithms, specialized order types, co-location, very short-term investment horizons, and high cancellation rates for orders. People feel that the big investment firms and hedge funds that have the resources and capital to build and run such expensive and complex networks have an unfair advantage in the market. These people argue that a lot of the high-frequency trading that the investment firms are carrying out is illegal and that they are using the old, slow networks that individual traders use to their advantage to front orders and to use a scalping trading strategy to gain small profits many time per day from smaller individual traders.


