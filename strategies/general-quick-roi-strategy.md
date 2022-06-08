# Platform

### Boardroom(Masonry)

* Epoch duration: 6 hours
* Deposits / Withdrawal of KSHARE into/from Masonry will lock KSHARE for 6 epochs and KDOLLAR rewards for 3 epochs.&#x20;
* KDOLLAR rewards claim will lock staked KSHARE for 6 epochs and the next KDOLLAR rewards can only be claimed 3 epochs later
*   Distribution of KDOLLAR during Expansion

    **80%** as Reward for Boardroom KSHARE Stakers

    **10%** goes to DAO fund

    **10%** goes to DEV fund
* Epoch Expansion: Current expansion cap base on KDOLLAR supply, if there are bonds to be redeemed, 65% of minted KDOLLAR goes to treasury until its sufficiently full to meet bond redemption. If there is no debt it will follow max capped expansion rate

### Boardroom UI Available information

Next **Seigniorage** indicates a countdown timer to the next epoch. (Each epoch duration lasts for 6 hours)      &#x20;

**APR** refers to the simple returns in USD value relative to the amount of KSHARE staked (USD value).\
_Note: **** APR fluctuates from time to time and is dependent on certain factors such as:_

* Price of KDOLLAR
* Price of KSHARE
* Amount of KSHARE staked in Boardroom(Locked Value)

### Boardroom on Contraction Periods

Boardroom will **not** mint any KDOLLAR (_NO REWARDS ON BOARDROOM_) while TWAP<1.01

### Boardroom on Debt Phase

Debt Phase take place on the expansion epochs that start after a contraction period where there are still Kbonds to be redeemed.

65% of Expansion during Debt Phase is allocated to the Treasury Fund to prepare for the KBOND Redemption. This amount is still reserved  whether or not KBOND holders are redeeming bonds or not.

Once KDOLLAR in treasury is sufficiently full to meet all circulating bond redemption, expansion rates will resume to normal.

KBOND emitted per epoch during contraction periods can be found on Regulations.

## Farm (Shares)

Stake your LP to earn KSHARE tokens

Shares Pools (Shares Reward) available for 12 months:

* KDOLLAR-KRONOS LP: 35500 Shares
* KSHARE-KRONOS LP: 24000 Shares

## Bonds(Pit)

**K**BOND (bond tokens) are available for purchase when KDOLLAR falls below the 1 KRONOS peg. If KDOLLAR's TWAP is between 1.00 and 1.01, neither KBOND nor  KDOLLAR will be issued.

e.g. if KDOLLAR's TWAP < 1, exchange KDOLLAR for KBOND will be in a 1:1 ratio.

KDOLLAR (bond tokens) are available for redemption when KDOLLAR goes above the 1 KRONOS peg.

To encourage redemption of KBOND for KDOLLAR when KDOLLAR TWAP > 1.1 and incentivize users to redeem at a higher price, KBOND redemption will be more profitable with a higher KDOLLAR TWAP value, of which KBOND to KDOLLAR ratio will be 1:R, where R can be calculated in the formula as shown below:

&#x20;                              R=1+\[(KDOLLAR(​twapprice)−1)∗coeff)]

Where coeff = 0.7
