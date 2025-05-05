# finm32000-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [FINM32000 Homework 1 Solved](https://www.ankitcodinghub.com/product/finm32000-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98411&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FINM32000 Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Consider a particular stock index that is defined to have value equal to the price of a fixed basket of non-dividend-paying stocks. Suppose that it follows the Black-Scholes dynamics with σ = 0.4, and that the time-0 index level is S0 = 100. Consider a three-month (=0.25 year) up-and-out European put, struck at 95, with a discretely-monitored knock-out barrier at 114, observed at times 0.02, 0.04, . . . , 0.24. That is, our option knocks out if and only if the index is at or above 114 at an observation time. Let the constant risk-free interest rate be r = 0.

The unit of time in this course will always be years, unless otherwise indicated.

(a) Write a Python function to price our option at time 0 using a trinomial tree. Some of the code is already provided for you.

Your code should choose the time step ∆t = T/N as suggested in class. We will want the barrier-monitoring times to be represented in the tree, preferably without introducing unequal time intervals anywhere, so we will want to choose N a multiple of 25. Your code should be able to accept any such N; a user who desires high accuracy can choose N large; a user who desires high speed can choose N small. For FINM 32000, please report a price using N chosen large enough that your output has converged, in your judgment (no proof needed), to within $0.01 of the true price. In this example, N = 100 will not be sufficient.

Your code should choose the space step ∆x such that the log of the barrier level is exactly halfway between consecutive log price levels of the tree. Subject to this constraint, choose ∆x

</div>
</div>
<div class="layoutArea">
<div class="column">
√

</div>
<div class="column">
3∆t value. In other words, the constraint is that there exists

</div>
</div>
<div class="layoutArea">
<div class="column">
close to the recommended σ

an integer j such that log(114) is halfway between the jth and (j + 1)th log-price levels:

</div>
</div>
<div class="layoutArea">
<div class="column">
log S0 + (j + 0.5)∆x = log(114).

How should the integer j be chosen? Choose it in such a way that the ∆x which satisfies the

</div>
</div>
<div class="layoutArea">
<div class="column">
constraint is approximately σ

</div>
<div class="column">
√

</div>
<div class="column">
3∆t.

</div>
</div>
<div class="layoutArea">
<div class="column">
Why do we have this “halfway between” requirement? If you try instead putting log(114) at a log-price level, you will find the accuracy to be much worse than the “halfway between” procedure, for this discretely monitored barrier option.

(b) Consider an up-and-in put with the same terms. Specifically, this option has the same strike, expiry, barrier, and monitoring dates, but it pays at expiry the put payoff only if the index was at or above the 114 knock-in barrier at some monitoring date; otherwise, it pays nothing. Using your part (a) result, find the time-0 price of the up-and-in put.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(c) Consider a continuously-monitored barrier option paying at time T = 0.25, the amount (95 − S0.25)+1􏰅 max St &lt; 114􏰆,

0≤t≤0.25

where the indicator variable 1(A) := 1A := 1 if event A occurs, 0 otherwise.

(c1) Is the time-0 price of the continuously-monitored barrier option greater than or smaller than the time-0 price of the discretely-monitored option in (a)? Justify briefly without doing any numerical calculations (one sentence is enough).

(c2) The continuously monitored barrier option can be replicated by a portfolio of T-expiry options, long 1 plain vanilla put struck at 95, and short α plain vanilla calls struck at 136.8.

The replication strategy is as follows. If S does not hit the barrier before time T , then simply collect the time-T payout of the 95 put, as desired. If S does hit the barrier, then at the time when S is at the barrier, the 1 unit of the vanilla put has value that exactly cancels the value of the −α units of the plain vanilla call; so at that time, we close out the portfolio positions, for a net payment of zero, as desired.

Solve analytically for the quantity α that makes this replication strategy valid, and find the time-0 value of the continuously-monitored barrier option. Do not use a tree.

Problem 1: Coding

Complete the coding of the function barrier trinom pricer in the provided file hw1.ipynb. The command barrier trinom pricer(hw1dynamics, hw1contract, hw1tree) must run properly, as it is currently written. Moreover, it should also still run properly, if you change the input parame- ters, such as hw1tree.N (which you will need to do, as N = 100 is insufficient for the desired level of accuracy), or other parameters, such as the volatility (therefore, the 0.4 volatility, and the other parameters should not be hard-coded into the function barrier trinom pricer.)

Do not modify the header of barrier trinom pricer. You may modify other lines in the file.

You do not need to make your code valid for contract parameters that would alter the contract’s logic. In particular, you may assume that H &gt; S0 &gt; K. Thus, you do not need to strive for maximum generality. But parameter perturbations that preserve the basic nature of the problem should run properly.

Problem 2 is at the end of this document

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Problem 1: Discussion

<ul>
<li>􏰇 &nbsp;Note that the introductory paragraph of Problem 1 specifies the option contract and the underlying dynamics. That paragraph says nothing about valuation method/algorithm.
The knock-out dates, described in that paragraph, are features of the contract. They are written into the terms of the option. Whatever methodology/algorithm that a modeler might choose to value the contract (analytic approximation, or tree with 500 steps, or tree with 5000 steps, or Monte Carlo) has no impact on the specification of the contract, which dictates that the barrier observation times are 0.02, 0.04, . . . , 0.24.
</li>
<li>􏰇 &nbsp;A useful diagnostic: test whether your code – with the barrier conditions removed – prices Europeans correctly, compared to Black-Scholes.</li>
<li>􏰇 &nbsp;When you introduce the barrier, one possible cause of error is code that fails to detect that you are at a monitoring date.
Beware of code that tests whether two floating point numbers are equal by naively using ==. Consider this example in Python:

<pre>     In [1]: 0.14 / 0.02 == 7
     Out[1]: False
</pre>
My computer thinks that .14/.02 and 7 are not equal.

That’s because it calculates .14/.02 and gets 7.000000000000001

Floating point arithmetic should not be assumed to be exact. If you need to test whether two floating point numbers x and y are equal, then instead of using ==, it would be better to test whether abs(x-y) is smaller than some tolerance.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Problem 2

<ol>
<li>(a) &nbsp;Interest rate is 0. A non-dividend-paying stock S has time-0 price S0 = 100. At time 0, you observe the dollar prices of at-the-money (K = 100) European calls on S at 0.5-year and 1-year expiries to be 11.25 and 12.00, respectively.
Find the time-0 Black-Scholes implied volatilities of these two options, by completing the coding of the IVofCall function.
</li>
<li>(b) &nbsp;Consider an at-the-money European call on S with expiry 0.75. Suppose that you try to price it by assuming that its implied volatility is equal to the midpoint (the arithmetic average) of the 0.5-expiry and the 1.0-expiry implied volatilities. Under that assumption, what would be the time-0 price of the 0.75-expiry call?</li>
<li>(c) &nbsp;The price computed in (b) would allow arbitrage involving the 0.75-expiry call and one of the other contracts. Describe the steps of this arbitrage.
You may assume either cash settlement or physical settlement of these options, but specify what your assumption is.

Cash settlement of an in-the-money option at time T means that you receive ST − K dollars if you are long the contract, K − ST dollars if you are short the contract. Physical settlement of an in-the-money option at time T means that you receive 1 share of stock and −K dollars if you are long the contract, or −1 share of stock and +K dollars if you are short the contract.
</li>
</ol>
(Conclusion: Expiry interpolation should not be done by linear interpolation of implied volatility. Instead it could be done by linear interpolation of. . . something else which we will discuss.)

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
