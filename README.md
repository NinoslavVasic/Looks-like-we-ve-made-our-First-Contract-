<h1>Blockchain - Smart Contracts with Solidity! </h1>

![contract](https://image.shutterstock.com/z/stock-photo-two-hands-handshake-polygonal-low-poly-hud-illustration-smart-contract-agreement-blockchain-and-1161295627.jpg)

<h1> "Looks like we've made our First Contract!"<h1>



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

This assignment has 3 levels of difficulty, with each contract increasing in complexity and capability. 

* **Level One** is an `AssociateProfitSplitter` contract. This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

* **Level Two** is a `TieredProfitSplitter` that will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

* **Level Three** is a `DeferredEquityPlan` that models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.

### Starting project

Navigate to the [Remix IDE](https://remix.ethereum.org) and create a new contracts  using the starter code for respected level above.

While developing and testing contracts, use the [Ganache](https://www.trufflesuite.com/ganache) development chain, and point MetaMask to `localhost:8545`, or replace the port with what you have set in your workspace.



#### SetUp, Compile, Deploy
As Solidity is OOP (Object Oriented Programming) language all contracts must be compiled and deployed first.

#### NOTE: Make sure to use correct compiling version in Remix (^0.5.0 or above) and always use prefunded address from Metamask. Contracts deployment has to be done with 0 wei and Injected Web3 which will automatically connect your 'lead' MetaMask address. As this exercise require using multiple ETH wallet address always check if your 'lead' in order to succesfully execute transactions.

#### Test the contracts

In the `Deploy` tab in Remix, deploy the contracts to your local Ganache chain by connecting to `Injected Web3` and ensuring MetaMask is pointed to `localhost:8545`.

You will need to fill in the constructor parameters with your designated `employee` addresses.

Test the `deposit` function by sending various values. Keep an eye on the `employee` balances as you send different amounts of Ether to the contract and ensure the logic is executing properly.

![Remix Testing](Images/remix-test.png)



### Deploy the contracts to a live Testnet

Contracts in this exercise are pointed on MetaMask to the Kovan network. 

After switching MetaMask to Kovan, deploy the contracts as before and copy/keep a note of their deployed addresses. The transactions will also be in your MetaMask history, and on the blockchain permanently to explore later.

![Remix Deploy](Images/remix-deploy.png)





### Level One: The `AssociateProfitSplitter` Contract




<p> Contract Deployment </p>

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/01-Associate_Profit_Splitter_deployment.PNG)

<p> Confirmation of Deployed Contract </p>

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/02-ass_contract_confirmed.PNG)

<p> Profit Splitter Confirmation </p> 

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/Inked03-ass_profit_split_employess_confirmation_LI.jpg)




### Level Two: The `TieredProfitSplitter` Contract

In this contract, rather than splitting the profits between Associate-level employees, it is calculated by rudimentary percentages for different tiers of employees (CEO, CTO, and Bob).


<p> Contract Deployment </p>

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/04-tiered_profit_splitter_deployment.PNG)

<p> tiered Profit Deposited </p>

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/05-tiered_deposit.PNG)

<p> Tiered Deposit Confirmation </p> 

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/Inked06-tiered_confirmation_LI.jpg)

   
### Level Three: The `DeferredEquityPlan` Contract

In this contract, we  are managing an employee's "deferred equity incentive plan" in which 1000 shares will be distributed over 4 years to the employee. We won't need to work with Ether in this contract, but we will be storing and setting amounts that represent the number of distributed shares the employee owns and enforcing the vetting periods automatically.

<p> `DeferredEquityPlan` Contract Deployment </p>

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/07-deffered_deployment.PNG)

<p> `DeferredEquityPlan` Contract Deployment Confirmation </p>

![](https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/screenshots/08-deffered_deployed_acc.PNG)








## More details on the:
   
   - codes: 
   'https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/Associate_Profit_Splitter.sol',
   'https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/Tiered_Profit_Splitter.sol',
   'https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/Deffered_Equity_Plan.sol',
  
  - fakenow code file: 'https://github.com/NinoslavVasic/Looks-like-we-ve-made-our-First-Contract-/blob/master/fakenow_deffered_equity_plan.sol'
   




<footer>
    
Copyright 2020 Columbia Engineering - FinTech Bootcamp NVasic
    
    
</footer>




