# Audits

We do take security [seriously](https://medium.com/goodghosting/goodghosting-smart-contract-audits-cc271fb9c268) and have spared no resources in order to ensure that the protocol matches the highest security standards. The smart contracts have been designed to be safe and secure from the very start, and underwent multiple [professional audits](broken-reference). However, there is no insurance provided in case an unknown bug or exploit is found.

### **External audit reports**

{% tabs %}
{% tab title="v2" %}
**GoodGhosting v2**

<table data-header-hidden><thead><tr><th>Auditor</th><th width="380">Description</th><th>Audit Type</th><th>Date</th></tr></thead><tbody><tr><td>Auditor</td><td>Description</td><td>Audit Type</td><td>Date</td></tr><tr><td><a href="https://github.com/Good-Ghosting/goodghosting-protocol-v2/blob/master/docs/audits/dedaub-goodghosting-v2-audit-june%20&#x27;22.pdf">Dedaub</a></td><td>v.2.0.0 Core Contracts and five yield-strategies (Aave v2; Aave v3; Curve; Mobius; No yield)</td><td>Smart Contracts</td><td>Jun, 2022</td></tr></tbody></table>
{% endtab %}

{% tab title="v1" %}
**GoodGhosting v1**

<table data-header-hidden><thead><tr><th>Auditor</th><th width="236">Description</th><th>Audit Type</th><th>Date</th></tr></thead><tbody><tr><td>Auditor</td><td>Description</td><td>Audit Type</td><td>Date</td></tr><tr><td><a href="https://certificate.quantstamp.com/full/good-ghosting-core-files-audit">Quantstamp</a></td><td>v.1.0.1 Core Contracts</td><td>Smart Contracts</td><td>Aug, 2021</td></tr><tr><td><a href="https://github.com/Good-Ghosting/goodghosting-smart-contracts/blob/master/docs/audits/dedaub-good-ghosting-core-files-audit.pdf">Dedaub</a></td><td>v.1.0.1 Core Contracts</td><td>Smart Contracts</td><td>Jul, 2021</td></tr><tr><td><a href="https://github.com/Good-Ghosting/goodghosting-protocol-v0/blob/master/docs/audits/ackee-good-ghosting-core-files-audit.pdf">Ackee Blockchain</a></td><td>v.1.0.1 Core Contracts</td><td>Smart Contracts</td><td>Nov, 2021</td></tr><tr><td><a href="https://github.com/Good-Ghosting/goodghosting-protocol-v1/blob/master/docs/audits/ackee-good-ghosting-curve-audit.pdf">Ackee Blockchain</a></td><td>v1.0.2 Curve Strategy </td><td>Smart Contracts</td><td>Jan, 2022</td></tr></tbody></table>
{% endtab %}
{% endtabs %}



### Risk disclaimers

Depositing funds into HaloFi does not come without risks. Before making a deposit, it is best to research and understand the risks involved.&#x20;

{% hint style="warning" %}
#### Please only risk funds you can afford to lose!
{% endhint %}

As with all [decentralized finance (DeFi)](https://ethereum.org/en/defi/) products, there are inherent dangers, including those related to smart contract vulnerabilities. The risks include, but are not limited to:

* Smart contract issues and/or exploits with the HaloFi savings pool \[[Ref](https://github.com/Good-Ghosting/goodghosting-smart-contracts)]
* Smart contract issues and/or exploits with the Aave v2 lending protocol  \[[Ref](https://docs.aave.com/developers/v/2.0/security-and-audits)]
* Smart contract issues and/or exploits with the Aave v3 lending protocol \[[Ref](https://docs.aave.com/developers/security-and-audits)]
* Smart contract issues and/or exploits with the Moola v2 lending protocol \[[Ref](https://docs.moola.market/)]
* Smart contract issues and/or exploits with the Mobius Money protocol \[[Ref](https://www.mobius.money/#/risk)]
* Smart contract issues and/or exploits with the Curve Finance protocol \[[Ref](https://curve.fi/risks)]
* Systemic issues and/or exploits with the blockchain used \
  E.g. Polygon PoS chain \[[Ref](https://docs.matic.network/docs/home/new-to-matic)] or Celo \[[Ref](https://celo.org/audits)]
* Systemic issues and/or exploits with the stablecoins used\
  E.g. DAI from MakerDAO \[[Ref](https://docs.makerdao.com/mcd-security/security.makerdao.com)] or cUSD/cEUR/cREAL from Celo \[[Ref1](https://medium.com/celoorg/diving-into-the-celo-price-stability-protocol-d7afd210609e), [Ref2](https://forum.celo.org/t/celo-reserve-liquidation-mechanism/2552), [Ref3](https://docs.celo.org/celo-codebase/protocol/stability)]
* Loss of fiat value due to price fluctuations of deposited volatile digital assets \[[Ref](https://www.coinbase.com/learn/crypto-basics/what-is-volatility)]&#x20;
* Slippage, Price Impact and Impermanent loss when using automated market makers (AMMs) like Curve and Mobius \[[Ref](https://research.paradigm.xyz/amm-price-impact)]



**Read our detailed explanations on**

{% content-ref url="halofi-challenges/technical-documentation/slippage-and-impermanent-loss.md" %}
[slippage-and-impermanent-loss.md](halofi-challenges/technical-documentation/slippage-and-impermanent-loss.md)
{% endcontent-ref %}

{% content-ref url="halofi-challenges/risks.md" %}
[risks.md](halofi-challenges/risks.md)
{% endcontent-ref %}

### Further reading

To fully graps how HaloFi works, we strongly recommend to read the technical details described in the [Game Mechanics](halofi-challenges/technical-documentation/savings-challenge-mechanics.md) & [Technical page](halofi-challenges/technical-documentation/). Especially, the risks inherent to the somewhat centralized power available to the [Admin functions](halofi-challenges/technical-documentation/savings-challenge-mechanics.md#admin-functions) of the HaloFi contracts.

_To learn more about the general risk in decentralized finance, we can recommend following publications:_

{% file src=".gitbook/assets/Meegan 2020 - Identifying Key Non-Financial Risks in DeFi on Ethereum Blockchain.pdf" %}

{% file src=".gitbook/assets/Jensen & Ross - 2021 - Managing Risk in DeFi - SSRN-id3745568.pdf" %}
