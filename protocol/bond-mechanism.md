# Bond Mechanism

### What are KBOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize KDOLLAR price around peg (1 KRONOS) by reducing circulating supply of KDOLLAR if the TWAP (time-weighted-average-price) goes below peg (1 KDOLLAR).

### When can I buy KBOND (Bonds)?

KBOND can be purchased only on contraction periods, when TWAP of KDOLLAR is below 1.

Every new epoch on contraction periods, KBONDs are issued in the amount of 3% of current KDOLLAR circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of circulating supply of KDOLLAR, no more bonds will be issued.

{% hint style="info" %}
KBOND TWAP (time-weighted average price) is based on KDOLLAR price TWAP from the previous epoch as it ends. This mean that KDOLLAR TWAP is real-time and KBOND TWAP is not.
{% endhint %}

### Where can I buy KBOND (Bonds)?

You can buy KBONDs if any are available, through the PIT on [KronosBoard](https://board.kronosdao.ai/pit), anyone can buy as many KBONDs as they want as long as they have enough KDOLLAR to pay for them.

There is a limit amount (3% of KDOLLAR current circulating supply) of available KBONDs per epoch while on contraction periods, and are sold as first come first serve.

### Why should I buy KBOND (Bonds)?

First and most important reason is Bonds help maintain the peg, but will not be the only measure use to keep the protocol on track.

KBONDs don't have a expiration date, so you can view them as a investment on the protocol, because long term you get benefits from holding bonds.

#### Incentives for holding KBOND

The idea is to reward KBOND buyers for helping the protocol, while also protecting the protocol from being manipulated from big players.&#x20;

So after you buy KBOND using KDOLLAR, you get 2 possible ways to get your KDOLLAR back:

1. Sell back your KBOND for KDOLLAR while peg is between 1 - 1.1 (1 KRONOS) with no redemption bonus. This to prevent instant dump after peg is recovered
2. Sell back your KBOND for KDOLLAR while peg is above 1.1 (1KRONOS) with a bonus redemption rate

The longer you hold, the more both the protocol and you benefit from Kbonds

{% hint style="success" %}
Example:

1. When KDOLLAR = 0.8, burn 1 KDOLLAR to get 1 KBOND (KBOND price = 0.8)
2. When KDOLLAR = 1.15, redeem 1 KBOND to get 1.105 KDOLLAR (KBOND price = 1.27)
{% endhint %}

So, which one is better?

If I buy KDOLLAR at 0.8, and hold it until 1.15 and then sell, I'm getting +0.35$ per KDOLLAR

But, if I buy KDOLLAR at 0.8, burn it for KBOND, and redeem it at 1.15, I'm getting 1.105 KDOLLAR \* 1.15 (KDOLLAR current price) = 1,271 (+0.47$) per KBOND redeemed.

But what if getting back to peg is taking too long ?

We are going to adjust our use cases, to have different behaviors on contraction and expansion periods to benefit KDOLLAR and KBOND holders when needed.

### When can I swap KBOND for a bonus?

KBOND TWAP (time-weighted average price) is based on KDOLLAR price TWAP from the previous epoch as it ends. This mean that KDOLLAR TWAP is real-time and KBOND TWAP is not. In other words, you can redeem KBOND for a bonus when the previous epoch's TWAP > 1.1.
