# CatapultX-Dashboard-Project
## Click the link to enter my dashboard
https://public.tableau.com/app/profile/songchangjiang/viz/CatapultXDashboardProject1/OverallPerformance2

## Project Description

This is the CatapultX (CX) project. The overall
goal of this project is to ascertain bidding strategies that lead to increased overall revenues. Here
is how the system is currently structured. CatapultX works with publishers of whom reserve
spots on their sites for advertisements. The publishers ask CatapultX to place bids on their
behalfs across multiple "feeds", which can be thought of as a market for advertisements. The
publishers and CatapultX will place a series of bids for specific advertisements that advertisers
place on the market. Not all of the bids will be recognized, and the ones that are recognized are
not always won. If a publisher/CatapultX wins a bid, the publisher then receives revenue from
the advertiser at the agreed upon bid price. Here is where CatapultX and publishers often face
issues.
On the one hand, if the publishers/CatapultX place bids that are too low, they could be
risking to leave revenue on the table. While they increase the probability of winning their bid,
they do so at the risk of a lower revenue per thousand views. On the other hand, they could set
the bid higher, and of course make more money per 1000 views. The issue here is that too high
of a bid may lead to a loss of probability of winning the bid, and in this case they loose out on
all possible revenue.
Over the prior 6 months, CatapultX has been gathering bidding data so that they can better
understand how best to bid. The longer term goal for CatapultX is to eventually implement an
optimization algorithm that can automatically suggest bid floors so as to maximize the average
revenue within a period of time. However, before taking on this more ambitious goal, CatapultX
needs help in exploring the data they already have. This is where I come in! My job is to take
the data and addresses the following objectives:
1. Generally speaking, is there is connection between the average bid price and the probability
of winning the bid?
2. Does this probability differ based on different time frames (time of day, month, etc)?
3. What other dynamics in the data impact the probability of winning?
