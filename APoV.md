## APoV

### Active Proof of Verification

One challenge faced by distributed AI systems/marketplaces is reptutation management and rating.

One possibility is that the consumer of the service is able to provide a rating based on how accurate the data they were provided was; this can be useful, however for it to be useful feedback needs to be required regularly, which can add extra friction to the user adoption process.

One potential to this is APoV, or Active Proof of Verification.

#### The Validators

Validators in this blockchain perform a role that could be described as ‘Active Proof of Stake’.

Validators provide feedback on predictions or analysis components from the AI Nodes to ensure that they are accurate (the process is similar to manually validating the training of a dataset). I have included a few example images below.

![fig1](/keybase/private/peterxyz/AI Project/fig1.png)



![fig2](/keybase/private/peterxyz/AI Project/fig2.png)

The validator could be a dapp or a wallet like app that people can use on their smart phone.

The aggregate score would be the trust rating for that particular AI Node with a minimum number of ratings required to be used available on the marketplace, and an algorithm that considers if a well performing Node suddenly starts getting consistent poor ratings (in the case of a Node being hijacked) and decays the total score appropriately.

The validators are incentivised to act honestly as the rewards they receive are ‘locked-up’ for a period of time, and if their validations are consistently vastly different from the mode (in the case of Yes/No) or the mean (in the case of 5 star ratings) their rewards are lost.

The incentives for the validators would be a consistent percentage of the reward for each cycle (could be a block, or *n* blocks). By keeping the incentives a consistent percentage of rewards, you ensure that when there are few validators there is a large incentive for new validators to join, and as the network grows more popular the number of validators should naturally rise as greater network usage should lead to a greater token price, allowing a smaller validator incentive to still be worthwhile.



