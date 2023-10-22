---
layout: posts
title:  "Tax Farming: should we bring it back?"
toc: true
---
<div style="text-align: Justify">
### Introduction
To the unininitiated "tax farming" might sound like an awful idea. Why grow more taxes for yourself? But ask yourself: if taxes take from the worker the hard-earned fruits of his labour, what happens when those fruit are taxes?

Fortunately we needn't concern ourselves with this troubling thought any further. As it turns out, tax farming has little to do with fruit and agriculture. Instead, it is the name given to a once prevalent form of tax collection. Today we have the IRS, but tax collection hasn't always been this centralized or efficient(??). Instead, historically, rulers and governments often auctioned the right to levy a specific tax to private citizens! These citizens would, in theory, bid what they expected to be able to earn by obtaining this concession. They were then responsible for the collection and accounting processes. 

You might be wondering why on earth a ruler would choose to do this. Why not just hire some thugs, instruct them to sally forth in pursuit of taxes and unleash them on their hapless subjects? Well, our ancestors (or, if like me your family doesn't have its own coat of arms, more likely their overlords) had good economic reasons for delegating tax collection in this fashion. 

### The Problem of Monitoring (Contract Theory)
To understand these, it's worth taking a little detour via Contract Theory. Though Contract Theory may be second only to "tax farming" in the list of least interestingly named things on this post, it turns out it's actually pretty interesting. Consider a model in which a "Princple" (in our case the ruler) seeks to delegate a task to an "Agent" (in our case the tax collector/thug). Consider first a baseline in which the principle observes whether the "effort/honesty" put into the task by the agent is High (e=1) or Low (e=0). That is, our ruler can observe exactly how honestly and efficiently his tax agents are working. Higher effort yields a higher chance of a "successful" collection of taxes but is more costly to the agent. Lower effort/honesty leads to a higher chance of a "failed" collection of taxes (perhaps the thug is bribed, or gets lost in the woods) but is cheaper for the agent to implement. The ruler does observe whether the tax harvest is successful or a failure and can compensate the worker accordingly. More specifically the expected profit is given by:

$$ E[\pi|e=1] = P(S|e=1)\pi(S) + P(F|e=1)\pi(F) > \\
P(S|e=0)\pi(F)+P(F|e=0)\pi(F) = E[\pi|e=0] $$

and the agent's utility is given by:

$$ \bar{U}(w,e) = u(E[w]) - u(10)\cdot e $$

Finally, assume the agent has a "reservation wage" (think of this as an outside option for the tax collector/thug, like joining the Ballet) of \$0. What wage does the Principle (ruler) have to offer to induce high effort from the agent? Well, if he can observe effort he wants to pay as little as possible while getting the agent to agree to work for him and put it a high-level of effort:

$$ u(w') - u(10) = 0\\
\Rightarrow w' = u^{-1}u(10) = 10
$$

Now what if the Principle cannot observe effort? Well, the Principle can observe outcomes, and so might design a wage that is contingent on the outcome of the tax harvest! A "success" will be rewarded with a higher wage than a "failure". The Principal thus solves:

$$ \max_{w_S, w_F} E[\pi|e=1] - (P(S|e=1)w_H + P(F|e=1)w_F)\\
\text{s.t:} u(P(S|e=1)w_H + P(F|e=1)w_F) - u(10) \geq u $$

</div>

<object data="/assets/pdfs/TaxFarmingEssay.pdf" width="1000" height="1000" type='application/pdf'/></object>

