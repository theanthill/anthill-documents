# Stabilisation Mechanism

## The Anthill Protocol

* _**When ANT trades below the $1 target price**_

When ANT price is below the target price of $1, token holders can purchase Midas Dollar Bonds \(ANTB\) by burning ANT to reduce the circulating supply with a 1:1 ratio, and Bonds will be burnt when users redeem ANT with a premium bonus.

In case of redemption, an amount of ANT will be minted according to the TWAP at the beginning of the epoch \(for example, if the ANT price is $1.1 then one Bond burnt will get back 1.1 ANT\). Important to note is that Bonds have no expiry after purchase.

* _**When ANT trades above the $1 target price**_

When ANT price is above the 1$ peg, the token supply will have to expand to push it back down to 1$ and the contract will allow the redemption of the ANTB.

When the price of ANT continues trading above the $1 target price after bond redemption, the contract mints an appropriate amount of new ANT. This will be distributed to the Boardroom Stakers.

This three token system creates incentives through seigniorage, always pushing ANT towards its peg. ANTS is used to redistribute the seigniorage from inflating the asset, while ANTB is used to establish a price floor while ANT is in its deflationary state.

* _**Epoch Expansion**_

Capped at +50% of current expansion cap if there are bonds to be redeemed and follows the expansion cap if treasury is sufficiently full to meet bond redemption \(See table below for detailed information\)

Total ANT Supply Expansion / Bonds Issued per Epoch

* Under 500k      4.00% Cap 
* 500k+                3.50% Cap 
* 1m+                   3.00% Cap 
* 2m+                   2.50% Cap 
* 5m+                   2.00% Cap 
* 10m+                 1.50% Cap 
* 20m+                 1.25% Cap 
* 50m+                 1.00% Cap 
* 100m+               0.75% Cap 
* 200m+               0.50% Cap 
* 1B+                     0.25% Cap

**Bootstrap period:** 1st week \(21 epochs\) goes with full expansion 4% each epoch

## Unique Algorithm <a id="unique-algorithm"></a>

* \(Boardroom\) Epoch duration: 8 hours during expansion and 6 hours during contraction — the protocol reacts faster to stabilize ANT price to peg as compared to other protocols with longer epoch durations
* Epoch Expansion: Capped at 6% if there are bonds to be redeemed, 4% if treasury is sufficiently full to meet bond redemption
* ANTB tokens do not expire and this greatly reduces the risk for bond buyers
* Price feed oracle for TWAP is based on the average of 2 liquidity pool pairs \(i.e. ANT/BUSD and ANT/BNB\) which makes it more difficult to manipulate
* The protocol keeps 75% of the expanded ANT supply for ANTS boardroom stakers for each epoch expansion, 25% toward Midas DAO Fund. During debt phase, 50% of minted ANT will be sent to the treasury for ANTS holders to participate in bond redemption.
* No discount for bond purchase, but premium bonus for bond redemptions if users were to wait for ANT to increase even more than the 1 $BUSD peg
* Riding on [theanthill.io](http://www.theanthill.io) various resources and ecosystem pillars, ANT will find its ever growing utilities right after launch, which is its great advantage over other algorithmic stablecoins.

## Midas DAO fund <a id="decentralised-dao-fund"></a>

This is a fund established to support MDO ecosystem:

* Rewards to all contributors & participants
* Marketing, events and partnerships to grow MDO.

