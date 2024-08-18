---
layout: post
title: Why Stamp Duty Is The Real Villian Of They Sydney Housing Market
categories: [Data Science]
---

My quest to understand why housing is so screwed up in Sydney hasn't stopped, with the impact of stamp duty taking my interest. [Stamp duty](https://www.revenue.nsw.gov.au/taxes-duties-levies-royalties/transfer-duty/buying-property) for those unaware is a type of tax levied on the transfer of property including houses and cars. On the whole it is a good tax as it a tax on consumption so it is reasonably equitable, so let me preface this post by saying I do support stamp duty but I do think the system is truly broken and is stifiling the housing market in Sydney.

My journey into looking into stamp duty started when a colleague told me he is looking at knocking and rebuilding his house because moving is too expensive. This shocked me as him and his wife are good earners and they have equity in a house which has gone up in value since they bought. Why is moving out of their price range? It turns out that the cost of stamp duty for the sort of houses they are looking at is just too much of a cash outlay that they cannot afford to move. 

The really terrible thing is they are looking at building a low-quality kit house as they currently value space over everything else, so stamp duty in this case is actively lowering the quality of housing stock in Sydney.

# How Bad Is It?

I never really thought about the total value of stamp duty until then so I did some calculations and it is quite shocking just how much it costs to move between houses in Sydney. 

<figure>
    <img src="{{ site.baseurl }}/images/2024-08-18-Stamp-Duty.md/Stamp_duty.png" alt="Cost of stamp duty on a median property in Sydney."width="500"/>
    <figcaption>Cost of stamp duty on a median property in Sydney.</figcaption>
</figure>

Unsurprisingly, the graph of the cost of stamp duty goes up and to the right. 

But that is not too surprising as the cost of everything goes up and to the right due to inflation. Instead, lets look at how many weeks it takes the median worker to earn the stamp duty on the median property in Sydney (we know from [my previous analysis](https://surfacethoughts.com/Sydney-Property/) that the assumption that the median earner buys the median house is pretty good). 

<figure>
    <img src="{{ site.baseurl }}/images/2024-08-18-Stamp-Duty.md/Stamp_duty_weeks.png" alt="Weeks of work required for the median worker to earn stamp duty on a median property in Sydney." width="500"/>
    <figcaption>"Weeks of work required for the median worker to earn stamp duty on a median property in Sydney.</figcaption>
</figure>

Even accounting for increases in earning potential, the time it takes to earn stamp duty has risen over time. Now, it takes the median worker over 35 weeks to earn to the stamp duty on the median property. Even if we assume that house buyers are coupled up, it would take a couple of median workers over three months of their full time earnings to pay for stamp duty. 

# Why Is It A Problem?

The main issue with such a large cost asssociated with moving homes is it reduceds the velocity of the housing market. [Velocity](https://en.wikipedia.org/wiki/Velocity_of_money) in the economic sense is how quickly assets move through a market and an efficient market will have high velocity. In terms of housing this would mean that everyone would be in the right house for them. 

With such a high cost to moving, there will be a large chunk of the population in the "wrong" house for longer, meaning that their house is not available for the "correct" occupants. As you can see this problem will compound, again rising the cost of housing, making it worse. 

# Why Is It So Bad?

Well, obviously, increasing house prices are one of the major factors influencing the rising stamp duty costs, but there is a simple policy decision that has exacerbated it: stamp duty wasn't indexed until 2019.

As far as I can tell, the rates of stamp duty were the same between 1985-2019. This is ridiculous as stamp duty is designed to be progressive like income tax with multiple bands for properties of different prices. Like income tax you get charged a percentage of every dollar over a threshold:

| Property value        | Transfer duty rate                                       |
|-----------------------|----------------------------------------------------------|
| $0 to $14,000         | $1.25 for every $100 (the minimum is $10)                |
| $14,001 to $30,000    | $175 plus $1.50 for every $100 over $14,000              |
| $30,001 to $80,000    | $415 plus $1.75 for every $100 over $30,000              |
| $80,001 to $300,000   | $1,290 plus $3.50 for every $100 over $80,000            |
| $300,001 to $1 million| $8,990 plus $4.50 for every $100 over $300,000           |
| Over $1 million       | $40,490 plus $5.50 for every $100 over $1 million        |

[Source](https://www.revenue.nsw.gov.au/taxes-duties-levies-royalties/transfer-duty)

But you'll notice that the top range is $1,000,000. In 1985, only the most expensive properties were above a million but now just about every property is. So it went from only the uber rich buying prestige properties paying the heigher rate to just about everyone. 

In 2019, indexation was introduced which defnitely helps but it was seemingly introduced with the assumption that the rates in 2018 were logical. Now, in 2024 the rates are: 

| Property value           | Transfer duty rate                                       |
|--------------------------|----------------------------------------------------------|
| $0 to $17,000            | $1.25 for every $100 (minimum $20)                       |
| $17,000 to $36,000       | $212 plus $1.50 for every $100 over $17,000              |
| $36,000 to $97,000       | $497 plus $1.75 for every $100 over $36,000              |
| $97,000 to $364,000      | $1,564 plus $3.50 for every $100 over $97,000            |
| $364,000 to $1,212,000   | $10,909 plus $4.50 for every $100 over $364,000          |
| Over $1,212,000          | $49,069 plus $5.50 for every $100 over $1,212,000        |

[Source](https://www.revenue.nsw.gov.au/taxes-duties-levies-royalties/transfer-duty)

You would be very hard-pressed to find a free-standing house in Sydney that isn't in the top bracket of stamp duty. People far from the top tax bracket buying a three bedroom home in Western Sydney are forced to pay the same stamp duty rate as the uber rich buying prestige homes on the beaches. 


# What Can Be Done?

Obviously, this is not equitable so there must be something we can do? Well, there isn't much real political support as stamp duty is a nice cash cow for the NSW Government. There was a proposal from the previous NSW Liberal Government to introduce land tax levied each year as an alternative, [but that was axed](https://www.smh.com.au/politics/nsw/perrottet-s-flagship-land-tax-to-go-as-minns-introduces-stamp-duty-reform-20230521-p5da1j.html). 

I think the option to pay land tax yearly makes a lot of sense as it will allow people to move to properties they only plan to occupy for a few years. It will encourage downsizing and moving to the "correct" property of a given stage of life. Yes, it can cost more in the long rung (Labor's reasoning why it is bad) but I think that doesn't give people enough credit to make an informed decision. 

