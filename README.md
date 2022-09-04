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
  
![Deposit_1_Ether](https://user-images.githubusercontent.com/103230949/188336881-1de86f23-6e7e-4706-884a-cece20ce267a.png)

  2. Transaction 2: Send 10 ether as wei.
  
![Deposit_10_Ether](https://user-images.githubusercontent.com/103230949/188336886-c7eb1959-b694-4815-a7df-14b1a4081a1c.png)

  3. Transaction 3: Send 5 ether.
  
![Deposit_5_Ether](https://user-images.githubusercontent.com/103230949/188336890-a5c4d433-3753-420d-b0a6-e8f905912def.png)

Once you’ve successfully deposited funds into your contract, test the contract’s ```withdrawal``` functionality by withdrawing 5 ether into ```accountOne``` and 10 ether into ```accountTwo```. After each transaction, use the ```contractBalance``` function to verify that the funds were withdrawn from your contract. Also, use the ```lastToWithdraw``` and ```lastWithdrawAmount``` functions to verify that the address and amount were correct.

Withdraw 5 ether into ```accountOne```:

![Withdraw_5_Ether_Account1](https://user-images.githubusercontent.com/103230949/188336921-e918c72b-7cf9-407c-8ffc-1b3b8f1c074c.png)

Withdraw 10 ether into ```accountTwo```:

![Withdraw_10_Ether_Account2](https://user-images.githubusercontent.com/103230949/188336931-882d35b9-f868-4465-ac5c-ffdabd698db2.png)
