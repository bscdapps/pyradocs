# What is PYRA?

PYRA is a dApp built on Binance Smart Chain. PYRA has its own unique cryptocurrency exchange which allows you to trade binance coin (BNB) for PYRA tokens. PYRA tokens are tokens with a clever twist: Every PYRA holder receives direct earnings in BNB every time that anyone else buys, sells or trades the token based on the amounts of tokens (in % out of total amount minted) held.

This means that as soon as you hold PYRA tokens, you are continuously accumulating "free" BNB distributed to you on every transaction based on the amount of PYRA tokens you hold on the exchange! This exchange and token is made better by the fact that the entire system is powered by an open-source smart contract deplyed on Binance Smart Chain ensuring transparency, security and trust.

## Understanding this Exchange

The core functionality of this exchange is entirely powered only by a deployed open-source Binance smart contract. Smart contracts are immutable and this means there is no one who has access to these funds but this autonomous program. You can see the full source code for the contract managing this exchange at any time on BSC Scan. 

This PYRA exchange is unlike any other you've seen and certain aspects may surprise you at first. This section tries to lay out the important things to understand:

- Smart contracts require a transaction to be sent for every action taken. This means that every action you take on the exchange requires a transaction to be sent through by the user on the Binance network. All actions including "Reinvest", "Withdraw", "Sell", "Transfer", etc require a "0" BNB transaction to be sent (with GAS which costs BNB, make sure you account for this!). This is why you see so many "0" BNB transactions here.
- The PYRA smart contract manages all the funds for this exchange. However, accessing secure smart contract data can be a bit slow at times under high load which is why the main exchange front-end site often may feel sluggish. You can always use backup sites to perform all the same functionality. You can also interact directly with the contract.
- When you are buying or selling on the exchange, you are buying or selling directly from the PYRA smart contract, not other users. The PYRA smart contract is solely responsible for issuing tokens and increasing supply as well as burning tokens and reducing supply. This happens automatically on all buys and sells to the exchange. In addition, the smart contract is solely responsible for determining the value of the PYRA token as well.


