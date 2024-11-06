---
description: A list of our deployed savings pool smart contracts
---

# Contracts

You can find a list of all our deployed smart contracts on Dune Analytics

{% embed url="https://dune.com/Deepcryptodive/halofi" fullWidth="false" %}

{% hint style="success" %}
All our smart contract addresses can be found in our onchain registry on [Celo](https://explorer.celo.org/address/0x7a495c05d009D346C5Ec942ec49AC519dd7035D0/transactions), [Polygon](https://polygonscan.com/address/0x3367c7211c80840194496185a31868325Dc43150) and [Base](https://basescan.org/address/0x97c447def7cb858922f0cf83fa3695708191ca8e). There, all smart contract addresses of the HaloFi savings challenges and yield strategies are registered.
{% endhint %}

<details>

<summary>How does the onchain registries work?</summary>

New addresses are added to the registry via`addContract` by the HaloFi deployer. This function accepts an array of addresses, so multiple contracts can be added in the same call. Upon doing so, the following event is emitted: \
`LOG_NEW_POOL(address indexed caller, address indexed pool)`

Example: [https://polygonscan.com/tx/0xb037faddc4690f3ed2815f086c8953abbe942613286bcf7fbec17dcaef1ab2f3](https://polygonscan.com/tx/0xb037faddc4690f3ed2815f086c8953abbe942613286bcf7fbec17dcaef1ab2f3) \
Where  [0x21dd4a4c744058c524aa22d3294e5bcb652f36a8](https://polygonscan.com/address/0x21dd4a4c744058c524aa22d3294e5bcb652f36a8) and [0x555aa40417160febe64b1904294c7f9e0359b7b6](https://polygonscan.com/address/0x555aa40417160febe64b1904294c7f9e0359b7b6) where registered. Respectively, a HaloFi savings challenge (Pool.sol) and yield strategy contract (AaveStrategyV3.sol) were registered.

</details>

&#x20;

***

## Old contracts (2021 - 2022)

### v2 (**Pool.sol)**

<table><thead><tr><th width="471">Address</th><th width="104"> Network</th><th>Name</th></tr></thead><tbody><tr><td>0x87f0428e33cd2e2284e7ce7459acfa3cf16f378e</td><td>Polygon</td><td>ETH Merge Hodl Pool</td></tr><tr><td>0xd72bc584a6470923bc184917c9731849a309660c</td><td>Celo</td><td>Hodl Pioneer</td></tr><tr><td>0x01539f82A5820a927942154cbe12aE172A935423</td><td>Celo</td><td>EthicHub</td></tr><tr><td>0x2130068652DAbB5aE873FffaF731F076011a33ca</td><td>Celo</td><td>Save for Xmas</td></tr><tr><td>0x2eadc3afa195339a195d0a412a128e49021c66ae</td><td>Polygon</td><td>Evil Pool</td></tr><tr><td>0x833fa7eea85406a9c9016c80f04f9f541c2fea53</td><td>Celo</td><td>Push Pool</td></tr><tr><td>0x299317d2d55fb1277e9142e36a9f5a82f6faf729</td><td>Polygon</td><td>Cupid Pool</td></tr><tr><td>0x15c9cc44d9d0130f405345e7143b29bcdf9b6306</td><td>Celo</td><td>Celoversary</td></tr><tr><td>0xd8ca269c2a929fee284f822b591b591c40ce5d85</td><td>Polygon</td><td>Save2Save Spirals - ReFi DAO</td></tr><tr><td>0x8d7a9b528cf9f31c439742ef2d49b6f0a524acb7</td><td>Polygon</td><td>Save2Save Spirals - Toucan</td></tr></tbody></table>



###

### v1 (**GoodGhostingPolygon.sol  & GoodGhosting.sol)**

<table><thead><tr><th width="474">Address</th><th width="102">Network</th><th>Name</th></tr></thead><tbody><tr><td>0x360BBC11322C77Dadc1DDCdb26224271C96CFD47</td><td>Polygon</td><td>Beta Launch</td></tr><tr><td>0xB81E1db4771C28250C98b3099Ec9962e269b4022</td><td>Polygon</td><td>MGD</td></tr><tr><td>0x9B5B6B4E889faca1e4Fc836a12102d6ffe8B5f52</td><td>Polygon</td><td>EthCC Pool</td></tr><tr><td>0x0F59f76f021BAfA4bc3E264E75199aFE5D839335</td><td>Polygon</td><td>Summer Savers</td></tr><tr><td>0x4aC6C237160275144B63814227eC71797257e25a</td><td>Polygon</td><td>Mask</td></tr><tr><td>0xDe59e1fD6A33091c0f34c675ACc455d85620C7d6</td><td>Polygon</td><td>200 DAI monthly</td></tr><tr><td>0x379eAC144939570B3F9289580Ef7C8a1F7f76259</td><td>Polygon</td><td>50 DAI monthly</td></tr><tr><td>0xCC4655Afe3A6Ce03faE33625F5Dfb9592F8F1825</td><td>Polygon</td><td>Bankless</td></tr><tr><td>0x8d241842cCd0ABcF8E0700C0637019692Bf52458</td><td>Polygon</td><td>Quest Pool</td></tr><tr><td>0x6768A8A3dCD689aea3de2A3A51a7626040e8415b</td><td>Polygon</td><td>Cometh</td></tr><tr><td>0x83b47F72D880993CaCC7d612F80B75220ad9C217</td><td>Polygon</td><td>ETH Lisbon</td></tr><tr><td>0x388C3Df56A924594230e9Ca689CaBe29055b87CC</td><td>Polygon</td><td>Crypto Colosseum</td></tr><tr><td>0xB12695e555Ce0d0ed2B8d3db90A027e234697D98</td><td>Polygon</td><td>Advent</td></tr><tr><td>0xAc2dEf60D45B8bBA10cc08d32908364747eE5Af2</td><td>Polygon</td><td>Future</td></tr><tr><td>0x242418F5eC3c218fa339eDE8C31eA22a928FbD55</td><td>Polygon</td><td>Unstoppable</td></tr><tr><td>0x4dc2E489E2bC5A4fBF2bfDC3f204e53a0BAe5D45</td><td>Polygon</td><td>Aavegotchi</td></tr><tr><td>0x90CD21957b03b4014E0db2159Cd75CaD1C9d5486</td><td>Polygon</td><td>Matic March</td></tr><tr><td>0x90A47003f208b09bA8C74eA05C34CbF6fc73b4d8</td><td>Polygon</td><td>Spring Pool</td></tr><tr><td>0xd613Ede2ed8A05Ae00f51B2046a1281671643eb3</td><td>Polygon</td><td>Stable Spring</td></tr><tr><td>0x34962DF66e390b9aAE6F353D1437931D6e874d2b</td><td>Polygon</td><td>SOS Pool</td></tr><tr><td>0xb0a8fFfd2bD0174d8Fd2d76F8f9072706576bFA1</td><td>Polygon</td><td>ETHAmsterdam</td></tr><tr><td>0xb5D5B0967a746419e84F8a900Eef97fe40dEa614</td><td>Polygon</td><td>Savings Showdown Pools: Round 1 - WETH</td></tr><tr><td>0x4D45240FfDA4E3DaA41F5564De99ecd2460F1F67</td><td>Polygon</td><td>Savings Showdown Pools: Round 1 - WMATIC</td></tr><tr><td>0xaf96213BBb61675ea2f4b27B602a40b110FD9127</td><td>Polygon</td><td>Fight Pool</td></tr><tr><td>0x224Cc7e2E84947F491dBE03c24334021b8671FD4</td><td>Polygon</td><td>1st Anniversary Polygon Pool</td></tr><tr><td>0xc1FC9FF2ea44AaAa46A9520C0c9b83BAEc7b846c</td><td>Polygon</td><td>Rio</td></tr><tr><td>0xCf9D9cC4F2439488fB8065ab2735d7C62078a15a</td><td>Polygon</td><td>Koh Tao</td></tr><tr><td>0x620a261d2c071fc2a92414d1696e9b3ab6b146e3</td><td>Polygon</td><td>Curve Pioneer - Stable</td></tr><tr><td>0x551be65c18102d68eed9990c6e7f3ad0c0e33802</td><td>Polygon</td><td>Curve Pioneer - Volatile</td></tr><tr><td>0xEee4Bc9B45dC43B3e6867901c915B55Ee1b05002</td><td>Polygon</td><td>The Longer Save</td></tr><tr><td>0xb759d54196898e8e6f9abdbabd3679cbc8bd7ee8</td><td>Polygon</td><td>Pumpkin Spice Savers - Grande</td></tr><tr><td>0xe07601a37426b780ac6382a6b98a1da4562337e4</td><td>Polygon</td><td>Pumpkin Spice Savers - Small</td></tr><tr><td>0xd924bc5fec62ea69175bd35f4c53e0b6825b8981</td><td>Polygon</td><td>CANCELLED - Pumpkin Spice Savers - Small</td></tr><tr><td>0xb25bbdf4e73f5bcaa93f28849d0d8cb285088b4a</td><td>Polygon</td><td>CANCELLED - Pumpkin Spice Savers - Grande</td></tr><tr><td>0xffD343a7F20093E9bcefe45Af552C1718059329E</td><td>Celo</td><td>Celo Launch</td></tr><tr><td>0x88779b5e8ABf203577A1c6d8F51abA7090AC75Bc</td><td>Celo</td><td>Celo 10</td></tr><tr><td>0x32Bd3ce981A575569d4bf1179f6B70D14Cf8E881</td><td>Celo</td><td>Celo Community</td></tr><tr><td>0x6DB09107Ba2aeb750691d67329A866EF7573Dd5E</td><td>Celo</td><td>Celoween</td></tr><tr><td>0x90f13aBbe52A1055B7eE3A69654C2a924CFB6a7d</td><td>Celo</td><td>Snow Pool</td></tr><tr><td>0x063502593e72726eBAD778e9E9648fb69e8E5f38</td><td>Celo</td><td>Celo Punks</td></tr><tr><td>0xbdAbD380D0f16a3F0bB03c5E186C834B90002924</td><td>Celo</td><td>Celo NFTs</td></tr><tr><td>0x173fdeEaC60418750c11d6B9Cc0c1c0E33111cec</td><td>Celo</td><td>Kenyan Digital Microworkers</td></tr><tr><td>0xe2Db3Ff23adF232b0dB2c652d50B413f6511BAcd</td><td>Celo</td><td>Celo-brate 100 cUSD</td></tr><tr><td>0x1D1371508dbD1C5C361780e397835B15DaCb4261</td><td>Celo</td><td>Celo-brate 10 CELO monthly</td></tr><tr><td>0x41C8Cf533719cDb67244Ce12d1453923762fe8CF</td><td>Celo</td><td>Ari-Ready?</td></tr><tr><td>0xA708610588DF1c5497D7efB58D2ed69F63a69196</td><td>Celo</td><td>LongHash</td></tr><tr><td>0x7Cdf5A7333f5590C86df0e2C651C3468B4235743</td><td>Celo</td><td>cREAL Samba</td></tr><tr><td>0x0111FF3F707e0cAba64123C490CdB559d826D04B</td><td>Celo</td><td>cUSD Samba</td></tr><tr><td>0xAb98026b821d46c135f0565Caac23bb323AeA0A5</td><td>Celo</td><td>Women's Day CELO</td></tr><tr><td>0xfCcEd47A38CdE380495e47f216c8A3072e97b9E8</td><td>Celo</td><td>Women's Day cUSD</td></tr><tr><td>0x1555B57448764CA2865644b2Af2dc649b293a514</td><td>Celo</td><td>Celo Mobile</td></tr><tr><td>0x2d18A07440A5061b4cD0375A7a57d9A382a0917A</td><td>Celo</td><td>Flywallet Pilot</td></tr><tr><td>0xD144f0848A3b1C08ABBF33c976Ed9fd2E822729c</td><td>Celo</td><td>The Second Wave</td></tr><tr><td>0x2609Ccce86a5C8761be7344306fa8857946D1B95</td><td>Celo</td><td>KnoxDAO</td></tr><tr><td>0xf54658d51a33525bE5CA67C45F81B34F56055cC1</td><td>Celo</td><td>1st Anniversary Celo Pool</td></tr><tr><td>0xF95799b722EA41e13641AE2fCbd27B3d96Ac54fd</td><td>Celo</td><td>Ibiza</td></tr><tr><td>0x8C76BC8b993b671A14Ef598705DdAee244c3A633</td><td>Celo</td><td>Hawaii</td></tr><tr><td>0xe5e5a97986e98a1f4137f982cbc311e32b13d4f3</td><td>Celo</td><td>Miami</td></tr><tr><td>0x6361d05e27a09630eae9e2515b8ee3705eb0f87e</td><td>Celo</td><td>Save2Save: impactMarket</td></tr><tr><td>0xd7a7f93e2005fdb4ff8149dedae0e30a984c9a19</td><td>Celo</td><td>Save2Save: Plastiks</td></tr></tbody></table>