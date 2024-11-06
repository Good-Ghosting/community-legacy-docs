# Risks

At HaloFi, we offer different type of decentralized savings pools. These pools may utilize different yield-generating strategies, carrying different type of [risks](../audits.md#risk-disclaimers).

## **Definition of Risk categories**

In our user interface, we display a risk category for each savings pool: ranging from low to high. Please keep in mind that we are simplifying a lot of different risk parameters into one simplified category. No simplification is ever perfect. \
\
We mainly categorized the savings pools depending on their perceived level of risk regarding impermanent loss and/or a loss in fiat value for our users.

### <mark style="background-color:green;">Low risk</mark>

_Low risk for impermanent loss and/or a loss in fiat value._

Typically, these pools require deposits in stablecoins (launched more than one year ago) and use a yield-generating strategy on an audited protocol. Note that the deposited stablecoin may be censorable or upgradeable (e.g. USDT, USDC, cUSD , cEUR or EURS). **There is no risk for impermanent loss, and a low risk for a loss in fiat value.**\
\
Examples:\
\- Savings pools with DAI or USDC or USDT deposits using an Aave v2 strategy\
\- Savings pools with DAI or USDC or USDT or EURS deposits using an Aave v3 strategy\
\- Savings pools with cUSD or cEUR deposits using a Moola v2 strategy



### <mark style="background-color:orange;">Medium risk</mark>

_Medium risk for impermanent loss and/or a loss in fiat value._

Typically, these pools require deposits in stablecoins and use a yield-generating strategy on an audited protocol. The underlying yield protocol may be newer (i.e. launched less than one year ago). The deposited stablecoin currency may be launched less than one year ago as well (e.g. cREAL, agEUR or jEUR) and/or censorable or upgradeable. \
Additionally, the strategy may use a StableSwap AMM pool which is subject to slippage, price impact and has a medium risk of [impermanent loss](technical-documentation/slippage-and-impermanent-loss.md). **There is a real risk that the fiat value at the time of withdrawal is (slightly) smaller, than the combined fiat value at the time of deposit(s).**

Examples:\
\- Savings pools with DAI or USDT or USDC deposits that use a Curve Finance [Aave pool strategy](technical-documentation/yield-strategies.md#curve-aave-stable)\
\- Savings pools with cUSD or cUSDC or pUSDC deposits that use a Mobius [Optics pool](https://www.mobius.money/#/pool) strategy\
\- Savings pools with agEUR or jEUR deposits that use an Aave v3 strategy\
\- Savings pools with cREAL deposits that use a Moola v2 strategy



### <mark style="background-color:red;">High risk</mark>

_High risk for impermanent loss and/or a loss in fiat value._

Typically, these pools require deposits in **volatile** **assets** (with a high risk for loss in fiat value) or have (indirect) exposure to volatile assets, and use a yield-generating strategy on an audited protocol. The underlying protocol might be newer and/or the deposited assets might be censorable or upgradeable and/or only recently launched.  Additionally, the strategy may use a non-stablecoin AMM pool (such as [Curve v2](https://resources.curve.fi/base-features/understanding-crypto-pools)) which is subject to slippage, price impact and has a high risk of [impermanent loss](technical-documentation/slippage-and-impermanent-loss.md). This category also includes any pool where a user deposits a volatile asset (such as ETH, MATIC or CELO), irrespective of the used strategy.\
**There is a high risk that the fiat value at the time of withdrawal is (much) smaller, than the combined fiat value at the time of deposit(s).**

\
Examples:\
\- Savings pools with DAI or USDC or USDT deposits using a Curve Finance [atricrypto strategy](technical-documentation/yield-strategies.md#curve) _(having exposure to volatile assets)_\
\- Any savings pools with volatile assets (e.g. ETH, CELO, GHST, WMATIC) using any of the available strategies (e.g. Aave v2, Aave v3, Curve or Mobius)\


## Factors taken into account

\
We aim to take into account:

* Complexity of the yield-generating strategy
* The chance of impermanent loss versus the underlying (deposited) asset
* The chance of loss versus fiat value (due to the exposure to volatile assets or a loss of peg)
* The safety of the underlying assets (e.g. immutable versus censorable tokens; newer vs battle-tested tokens)
* Whether the underlying protocol is battle-tested
* Whether the underlying platform had security issues / exploits before
* Whether the underlying platform is audited
* External risk ratings such as [DeFi Safety Reviews](https://www.defisafety.com/pqrs) and [Beefy Safety Score](https://docs.beefy.com/safu-protocol/beefy-safety-score#category-asset-risks)
