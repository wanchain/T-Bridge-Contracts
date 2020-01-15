# T-Bridge-Contracts
The contracts for Wanchain 4.0 T-Bridge framework

# Introduction

With T-Bridge framework, Cross-Chain Transactions (CCT) contracts and sample business contracts have been provided for the CCT transactions.

<img width='400px' src='./images/T-Bridge-Contracts.jpg' />

For the sample scenario, Wanchain blockchain and HyperLedger BESU blockchain have been connected. Here HyperLedger BESU plays the role of private and business blockchain. Wanchain plays the role of public and router blockchain.

For the sample scenaio, user owns the WRC20 token. Two cases are supported:

1. User shall be able to use the exchange service to exchange WRC20 token to B token in BESU, and pay the exchanged B token to others. 
2. User shall be able to use the exchange service to exchange WRC20 token to B token in BESU, and buy the goods published in BESU. 
 
For new CCT scenarios, additional business contracts could be developed accordingly.

# Deployment

For Wanchain mainnet, relevant contracts have been deployed:

- CCTRoot: 0x5f1aa1e999c2c5e31ed53779bf1d10fa3257516f
- CCTTrustTest: 0x6ef5eb9dd724c6fe24167b4c6c7c4bb64f6a0a0f
- CCTChannel: 0x8bcbbaf979324b2ea6fa14b5d15599789c81dac7
- CCTDispatcher: 0xf65e3f151b5f76055571b46cbab3d42247df8402
- AggregationWan: 0xc4b0f47ec8492ecc13041ae50aeb11d3c8308196
- ExchangeProxy: 0xc6ae4b098fde7aed3b7870fd20d14b5ec7678c6e
- GoodsProxy: 0xc1bface4728c443e48dedd0f39f3ec19a32fc696
- Wrch: 0x005b96e8472d2d7801dea430dd270f115277bdc2
- DemoERC20: 0x223bf6e0448d61ed88da4143a0adf3d19e60230b

