# Lottery-With-Solidity
Lottery project with Solidity Deployed on Testnet


Here What we are doing is we created a Manager of type "address" who will monitor the lottery.
Then we created a dynamic array "participants" which is "payable" because someone among these participants is going to get all the lottery money.
These participants will send a minimum described amount of ether to the contract in order to participate in the lottery and the lottery will only happen even if there are a minimum of 3 participants.
Then we will use keccak256 to generate a random hash which will help in getting a random winner for the lottery.
The total amount present in the contract will be transfered to the winner by the manager and the array will be reseted.
