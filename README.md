# Week20_HomeWork
Smart contracts With solidity

## Background

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.
To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.


### Deliverables

> A Smart contract using solidity JointSavings

> A folder named Execution_Results that contains at least eight images. These images should confirm that the deposit and withdrawal transactions, which are designed to test the JointSavings functionality in the JavaScript VM, worked as expected.

### Steps

*Step-1*

Complete the coding and compiling the provided solidity file using Remix IDE.

<img width="363" alt="image" src="https://user-images.githubusercontent.com/56103714/162554334-a5518797-8a3c-4ff0-b234-670820acbbc2.png">


*Step-2*

Compile and deploy the contract using JavaScriptVM

<img width="363" alt="image" src="https://user-images.githubusercontent.com/56103714/162554345-f04e5145-f104-4a49-894c-9ab6eea59491.png">


*Step-3*

Create an interaction with the deployed smart contract  

<img width="360" alt="image" src="https://user-images.githubusercontent.com/56103714/162554357-fd84f11b-c015-4ebc-a899-8466866fe54c.png">

- Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.
- Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract:
-Transaction 1: Send 1 ether as wei.
-Transaction 2: Send 10 ether as wei.
-Transaction 3: Send 5 ether.

>Once you’ve successfully deposited funds into your contract, test the contract’s withdrawal functionality by withdrawing 5 ether into accountOne and 10 ether into accountTwo. After each transaction, use the contractBalance function to verify that the funds were withdrawn from your contract. Also, use the lastToWithdraw and lastWithdrawAmount functions to verify that the address and amount were correct.




