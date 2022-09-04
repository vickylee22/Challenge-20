# Challenge-20

## Background
A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## Instructions
The steps for this Challenge are divided into the following sections:

  1. Create a Joint Savings Account Contract in Solidity

  2. Compile and Deploy Your Contract in the JavaScript VM

  3. Interact with Your Deployed Smart Contract
  
## Testing
Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the ```contractBalance``` function to verify that the funds were added to your contract:

  1. Transaction 1: Send 1 ether as wei.

  2. Transaction 2: Send 10 ether as wei.

  3. Transaction 3: Send 5 ether.

Once you’ve successfully deposited funds into your contract, test the contract’s ```withdrawal``` functionality by withdrawing 5 ether into ```accountOne``` and 10 ether into ```accountTwo```. After each transaction, use the ```contractBalance``` function to verify that the funds were withdrawn from your contract. Also, use the ```lastToWithdraw``` and ```lastWithdrawAmount``` functions to verify that the address and amount were correct.
