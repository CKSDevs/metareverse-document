# Vintk Pool FAQ & Troubleshooting

## Troubleshooting

### **I can't find the Vintk Pool I was staking in!**

You should be able to find the Vintk Pool under the “Finished” tab on the Vintk Pools page.

By selecting “Staked Only”, it will make it easier to find your assets.

### **Why can’t I unstake my tokens from a** Vintk **Pool?**

If you are unable to unstake from the Stake $MTR, Earn $MTR pools, please check to make sure that you haven’t sold the Vintk tokens in your wallet. This token acts as a \`proof of ownership\` over your $MTR in the Manual $MTR pool.

### **Why did my earned tokens go to zero after staking/unstaking?**

Don’t worry! They’re in your wallet already.

Whenever you stake or unstake from a Vintk Pool or farm, your earned tokens get harvested and sent to your wallet at the same time.

## **General Questions**

### How is APR for Vintk Pools calculated?

> Vintk Pool APR = Annualized rewards (USD) / User funds staked in Vintk Pool (USD) \* 100

As a basic example, let's take a 60-day pool with 300,000 USD worth of rewards, and 3,000,000 USD worth of $MTR staked in it.

The APR fluctuates as more $MTR is staked by users, and as the price of $MTR, and the reward token, vary.

|                                                       | **Calculation**                  | Amount            |
| ----------------------------------------------------- | -------------------------------- | ----------------- |
| Total rewards to distribute (USD value)               |                                  | 300,000 USD       |
| Distribution period                                   |                                  | 60 days           |
| Daily distribution                                    | 300,000 / 60 =                   | 5,000 USD daily   |
| **Annualised rewards (USD value)**                    | 5,000 \* 365 =                   | **1,825,000 USD** |
| **Value of $MTR staked by users in pool (USD value)** |                                  | **3,000,000 USD** |
| **APR**                                               | (1,825,000 / 3,000,000) \* 100 = | **60.833% APR**   |

### **What does the “End” number on my Vintk Pool refer to?**

This shows the amount of blocks left until the rewards for that pool stop being distributed. Once the pool has reached that block, you should unstake your tokens, because you won’t be receiving any rewards after that.

### **Where do the rewards from Vintk Pools come from?**

There are three main types of Vintk Pools.

1. Stake $MTR, earn $MTR
2. Stake $MTR, earn other tokens.
3. Stake other tokens, earn $MTR

The rewards for the "Stake $MTR, earn $MTR " Vintk Pools come from the [CAKE emissions](https://docs.pancakeswap.finance/tokenomics/cake/cake-tokenomics). Each block, a number of $MTR tokens are allocated as rewards for these pools.

The rewards for the "Stake $MTR, earn other tokens" type are provided by the project teams who sponsor a Vintk Pool.

For the "Stake other tokens, earn $MTR" type, the MetaReverse AMM treasury buys back $MTR from the market to distribute as rewards. These pools are funded by MetaReverse, not by the projects themselves.

### What’s Vintk Token?

MetaReverse’s Vintk Token is deposited in your wallet when you interact with the **Manual** “Stake $MTR, Earn $MTR” Vintk Pool. It's not staked for

It’s basically an IOU that shows how much $MTR you’ve staked in the pool.

It’ll be returned automatically when you unstake your $MTR from that pool.

{% hint style="warning" %}
Don’t sell your Vintk tokens! You need to return your Vintk to unstake your $MTR from the Manual $MTR pool. The amount of VINTK you return must be the same as the amount of $MTR you unstake.
{% endhint %}
