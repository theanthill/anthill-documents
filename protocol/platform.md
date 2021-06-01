# Platform

## Boardroom

* Epoch duration: 8 hours

## Banks

Bank Pools \(Farming details can be found [here](https://medium.com/midasprotocol/introducing-the-midas-dollar-ab99a5bcd526)\)

* ANT/BUSD
* ANT/BNB

ANTB \(bond tokens\) are always on sale. However, a purchase during epoch expansion will result in a net loss. Hence, the platform UI only allows for the purchase of ANTB when ANT falls below the target value peg.

To encourage the redemption of ANTB bonds for ANT when ANT's TWAP &gt; target value and incentivizes profit-seekers who are doing bonds. Bonds redemption will be more profitable with a higher ANT TWAP value, of which ANTB bonds to ANT ratio will be 1:R, where R can be calculated in the formula as shown below:

**R = 1.0 + min\[ 0.3,\( ANT\(TWAP Price\) − 1.0 \)∗coeff \) \]**

Where coeff = 0.65

**Example 1.** if ANT's TWAP = 1.05,

R = 1.0 + min\[0.3, \(1.05 - 1.0\)\*0.65\)\] = 1.0 + min\[0.3, 0.0325\] = 1.0 + 0.0325 = 1.0325

ANTB to ANT ratio in Example 1 would be 1:1.0325

**Example 2.** if ANT's TWAP = 1.10,

R = 1.0 + min\[0.3, \(1.1 - 1.0\)\*0.65\] = 1.0 + min\[0.3, 0.065\] = 1.0 + 0.065 = 1.065

ANTB to ANT ratio in Example 2 would be 1:1.065

As you can tell, ANTB holders can profit more when they participate in bonds redemption when ANT TWAP &gt;&gt; 1.z

