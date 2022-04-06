# modelling-entry-queue-post-merge
The Beacon Chain exists separately to the Ethereum Mainnet doling out rewards to the validators that correctly perform their duties. The Merge, the most anticipated event of 2022 in crypto world that will connect the Beacon Chain and the Ethereum Mainnet, is expected to bring a significant increase in staking APR causing an increasing amount of ETH2 deposits and, as a result, the entry queue.

Lido, being the leading Ethereum staking pool with more than 3M staked ether, uses a so-called “socialized model” for paying rewards to its users. It implies that rewards earned by Lido’s validators are being divided among existing and new users in proportion to amount staked although queueing validators do not earn any rewards until being activated.
Currently, Lido’s staking APR is about 4% and the Merge will raise it up to 8.5%. We conducted this research to figure out to what extent the decrease in staking APR due to the expected entry queue may affect our existing users. 

Based on historical data and multiple simulations with the network's parameters, we developed standard (the most probable) and “harsh” (the most extreme) scenarios of the Beacon Chain growth. 

In the standard scenario (3M ether staked in 6 weeks, Lido share 50%), there will be a slight decrease short-term in Lido’s APR but over a one-year perspective the APR loss would not exceed 0.07 percent point (or by 1%). In the “harsh” scenario that seems quite unlikely (5M ether staked in 8 weeks, Lido share 80%), the APR would not go below 0.42 percent point (or by 6.2%).

Thus, we do not recommend changing the “socialized model” and if the “harsh” scenario came true, Lido would introduce the upper limit for the protocol growth aimed to protect the existing Lido’s users from the significant APR loss.
