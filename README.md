<h1>Blockchain with Solidity! </h1>

![contract](https://image.shutterstock.com/z/stock-photo-two-hands-handshake-polygonal-low-poly-hud-illustration-smart-contract-agreement-blockchain-and-1161295627.jpg)

<h1> MultiWallet<h1>



<h2>Instruction: step by step</h2>

## Background

Your new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

Fortunately, you've been learning how to program smart contracts with Solidity! What you will be doing this assignment is creating a few `ProfitSplitter` contracts. These contracts will do several things:

* Pay your Associate-level employees quickly and easily.

* Distribute profits to different tiers of employees.

* Distribute company shares for employees in a "deferred equity incentive plan" automatically.

## Files

* [`AssociateProfitSplitter.sol`](Starter-Code/AssociateProfitSplitter.sol) -- Level 1 starter code.

* [`TieredProfitSplitter.sol`](Starter-Code/TieredProfitSplitter.sol) -- Level 2 starter code.

* [`DeferredEquityPlan.sol`](Starter-Code/DeferredEquityPlan.sol) -- Level 3 starter code.


## Initial Instructions

This assignment has 3 levels of difficulty, with each contract increasing in complexity and capability. Start with Level 1, then move forward as you complete the challenges. You can build all three with the skills you already have!

* **Level One** is an `AssociateProfitSplitter` contract. This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

* **Level Two** is a `TieredProfitSplitter` that will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* **Level Three** is a `DeferredEquityPlan` that models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.

### Starting your project

Navigate to the [Remix IDE](https://remix.ethereum.org) and create a new contract called `AssociateProfitSplitter.sol` using the starter code for level one above.

While developing and testing your contract, use the [Ganache](https://www.trufflesuite.com/ganache) development chain, and point MetaMask to `localhost:8545`, or replace the port with what you have set in your workspace.



#### setup, compile, deploy

#### Test the contract

In the `Deploy` tab in Remix, deploy the contract to your local Ganache chain by connecting to `Injected Web3` and ensuring MetaMask is pointed to `localhost:8545`.

You will need to fill in the constructor parameters with your designated `employee` addresses.

Test the `deposit` function by sending various values. Keep an eye on the `employee` balances as you send different amounts of Ether to the contract and ensure the logic is executing properly.

![Remix Testing](Images/remix-test.png)



### Deploy the contracts to a live Testnet

Once you feel comfortable with your contracts, point MetaMask to the Kovan or Ropsten network. Ensure you have test Ether on this network!

After switching MetaMask to Kovan, deploy the contracts as before and copy/keep a note of their deployed addresses. The transactions will also be in your MetaMask history, and on the blockchain permanently to explore later.

![Remix Deploy](Images/remix-deploy.png)





### Level One: The `AssociateProfitSplitter` Contract




<p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/screenshots/btc-confirmation%20-trx.PNG)

<p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/screenshots/btc-confirmation%20-trx.PNG)

<p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/screenshots/btc-confirmation%20-trx.PNG)



#### NOTE: If one get an error running `./derive`, as it can happen on windows machine then use: `php ./hd-wallet-derive/hd-wallet-derive.php`.


### Level Two: The `TieredProfitSplitter` Contract

In this contract, rather than splitting the profits between Associate-level employees, you will calculate rudimentary percentages for different tiers of employees (CEO, CTO, and Bob).


<p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/screenshots/btc-confirmation%20-trx.PNG)
<p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/screenshots/btc-confirmation%20-trx.PNG)

<p> Confirmation of Executed Transaction </p>

![](https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/screenshots/btc-confirmation%20-trx.PNG)


   




## More details on the:
   
   - codes:  'https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/master/wallet.py'




<footer>
    
Copyright 2020 Columbia Engineering - FinTech Bootcamp NVasic
    
    
</footer>




