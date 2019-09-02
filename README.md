# PolkaDeFi

 ## Project Description

 PolkaDeFi is an open decentralized financial platform (Layer 0), supported by cross-chain assets, stable coin POD (Layer 1) is generated by excess mortgage. To provide users with financial services including payment scenarios, lending, financial management, insurance and so on (Layer 2). Based on the infrastructure provided by PolkaDeFi, can develop many flexible financial businesses (Layer 1 & 2 & 3).

 ### 1. Why Polkadot needs the service of DeFi ?

 In the PoS network, pledged tokens provide network security , and only the pledged tokens have the right to earnings and voting.

 The token in the pledge state cannot be circulated, and it usually needs an unlocking period to prevent the evil node from redeeming the pledged assets immediately .The token in the non-pledged state can circulate freely , but cannot enjoy the additional revenue , which in a disguised way pays for the network security cost.

 The PoS blockchain is designed to encourage holders to pledge tokens to offset the dilution of value in the dilution of value in process of inflation , there is no liquidity and the holder cannot use their own assets.

 The consensus of Polkadot is NPoS（nominated proof-of-stake）, that means most of the holding DOT users can participate in Polkadot ecosystem.  

 In the staking process, the entire system needs to secure the network by locking the DOT pledged by validators and nominators . 

 In addition , in the future ,more than 50% of the total amount of DOT users will get involved in the staking module . When users want to unbind staking ,they need three months to get rid of the shackles , which greatly restricts their assets liquidity .

 If users have the demand of funds to participate in finance (such as crowd-funding for high-quality projects , external debt or emergency consumption ) , they can not provide funds in time . So we deem DOT under the state of staking as an illiquid asset.

 DeFi would be a good solution to solve the problem of asset liquidity. For example , DeFi could provide decentralized mortgage lending service for users who has participated  in staking , thus, improving their asset liquidity without losing their mortgage assets.

 > What’s the best way to lend for a user with the low risk of price fluctuation ?  
 Because the blockchain has spawned a lot of cryptographic assets , and most of that are unstable. If we want to offer lending service and other DeFi service , the fluctuation of price are inevitable .So we think stable coin is the key to solve the problem of fluctuation. 

 Dai is a freely trade-able token which based on the Ethereum blockchain and stabilized the value of a coin around the value of a U.S. Dollar without any central control.

 The stable coin system of Dai has been running smoothly 2 years ,but it does not apply to Polkadot . Because Polkadot and Ethereum are two different blockchain networks , and the functions of DOT and ETH  are so different.

 Therefore, we try to develop POD stable coin system based on substrate framework according to the characteristics of Polkadot , and make stable coin POD as the main currency in circulation ,and finally construct the Parachain for PolkaDeFi ecosystem.

 ### 2. Improves the value of DOT in locked state.

 #### 2.1 Right to use and ownership of DOT

 DOT is the native token of the Polkadot network. The user mainly has two usage rights. One is used as a transaction fee, and the fee is generated along with the transaction.The second is for staking mining, slot auctions, voting on proposals. 

 When using these features, DOT is in a lock-up period, and between the right to use and ownership in the bound state. We think that the DOT does not have liquidity , although it is designed for network security and stability.

 But the value of these locked tokens cannot be directly used in financial business, so we separate the use rights and ownership of DOT.

 #### 2.2 L-DOT introduction

 The right to use the DOT is bound to the ownership of the locked state. If a reliable institution maps the ownership of the pledge state DOT into a redemption voucher, the use of the asset and the distribution of the proceeds are transparent.

 Actually the locked DOT is in use (staking, voting, slot auction, etc.), the redemption voucher is used for free circulation transactions. Just like the futures before the physical delivery, the transaction is the redemption voucher of the subject matter. This will release the liquidity of the pledge state DOT, so that its value can participate in more financial business.

 The user deposits the DOT into the collateral pool, and the DOTs is freely staking on the Polkadot network by PolkaDefi and maps the L-DOT to the user. L-DOT is a redemption voucher that is freely circulated and get the benefits of staking. L-DOT can be used in multiple DeFi services.

 Users can use L-DOT to redeem the associated Dot and the benefits of staking from the collateral pool at any time. The redemption process also requires a three-month unbundling period.

 Collateral pool will also provide immediate redemption services, which require users to pay a certain fees.

 #### 2.3 Collateral pool

 The collateral pool is the core module of PolkaDefi and the gateway to Polkadot. It agent controls the escrow account on Polkadot, the user locks the Dot to the collateral pool, and obtains the redemption voucher L-DOT.

 The locked DOTs is staking on the Polkadot network by a managed account controlled by the collateral pool. When a user redeems a collateral pool using L-dot, the escrow account unbinds the user-locked DOTs and the benefits of staking.

 ### 3. Introduce of POD

 #### 3.1 What's the POD

 POD is a stable coin generated by the collateral of L-DOT in the PolkaDeFi parachain, and  the value of a POD around the value of a U.S. Dollar. POD will be distributed in the future Polkadot cross-chain ecosystem to provide financial services.

 #### 3.2 How can users to get POD in the PolkaDeFi ?

 L-DOT is collateral for the PolkaDeFi and can be mortgaged by the user to generate stable coin POD.

 Once the POD is generated, the holder of the POD generates a corresponding amount of debt at the same time . For risk control ,all collaterals are over-collateralized , that means the value of the POD will be lower than the value of the collateral of L-DOT. 

 In the end, the debt will lock the L-DOT until the user repays the POD and pays interest and a stable fee before returning the L-DOT.

 #### 3.3 POD is the blood of PolkaDeFi

 ![3.3-image](https://github.com/jiangfuyao/PolkaDeFi-images/raw/master/3.3.png)

 ### 4. Use case of the POD

 ![4.1-image](https://github.com/jiangfuyao/PolkaDeFi-images/raw/master/4.1.png)

 ❶ Users lock their own DOT into PolkaDeFi.

 ❷ Locked DOT forms a Staking Pool.

 ❸ Freely selection or Automatic selection of optimal Validators.

 ❹ Staking in Polkadot.

 ❺ Users can get L-DOT after locking DOT.

 ![4.2-image](https://github.com/jiangfuyao/PolkaDeFi-images/raw/master/4.2.png)

 ❻ Users holding L-DOT can use L-DOT as a qualified collateral.

 ❼ Users deposit L-DOT to L-DOT collateral pool.

 ❽ Creating Collateral Debt Contracts.

 ❾ Provide stable coin POD for users.

 ![4.3-image](https://github.com/jiangfuyao/PolkaDeFi-images/raw/master/4.3.png)

 ❿ POD holders can participate in crowdfunding for future high-quality parachain, financial product  and payment scenario etc.

 ----
