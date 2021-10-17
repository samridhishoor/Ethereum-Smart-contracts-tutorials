# blockchain_1
Ethereum based smart contracts for beginner practice 
#First Smart Contract: Lottery

##The Lottery Smart Contract with 4 conditional variations in the source code.
 - Planning and Design

Lottery algorithm:
1. The lottery starts by accepting ETH transactions. Anyone having an Ethereum wallet can 
send a fixed amount of 0.1 ETH to the contract’s address.
2. The players send ETH directly to the contract address and their Ethereum address is 
registered. A user can send more transactions having more chances to win.
3. There is a manager, the account that deploys and controls the contract.
4. At some point, if there are at least 3 playesrs, he can pick a random winner from the 
players list. Only the manager is allowed to see the contract balance and to randomly 
select the winner.
5. The contract will transfer the entire balance to the winner’s address and the lottery is 
reset and ready for the next round.


Lottery Smart contract with variations: 

 #1

Consider the Lottery Smart Contract.

the contract is changed so that the manager of the lottery can not participate in the lottery.


 #2

Consider the Lottery Smart Contract .

the contract is changed so that the manager is automatically added to the lottery, without sending any ether.



 #3

Consider the Lottery Smart Contract.

the contract is changed  so that anyone can pick the winner and finish the lottery, if there are at least 10 players.



#4

Consider the Lottery Smart Contract.

the contract is changed so that the manager receives a fee of 10% of the lottery funds.




