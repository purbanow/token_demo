# Token demo

The purpose of this repo is to demonstrate simple token deployment on Ropsten network using Remix - Solidity IDE 
and MetaMask + Ledger Nano S interaction with contract. 
The token code is based on tutorial from [Ethereum website](https://www.ethereum.org/token)


### Contract deployment:

1. Install and setup [MetaMask](https://metamask.io/).
![Alt text](img/metamask_1.png?raw=true)
2. Get some ether using this [website](https://faucet.ropsten.be/) 
3. Copy code and paste to Remix, select 0.5.4 Solidity version and click compile.
![Alt text](img/remix_1.png?raw=true)
4. Fill all inputs as in the below image and click deploy.
![Alt text](img/remix_2.png?raw=true)
5. Done, the contract is on Ropsten network.
![Alt text](img/remix_3.png?raw=true)


### Contract Interaction using MetaMask

1. Call setPrices function with 100000,100000
2. Change MetaMask account.
3. Call buy function with 100000000 wei as value.
4. Call balanceOf function with address value

### Contract Interaction using Ledger Nano S

1. Go to [myetherwallet](https://vintage.myetherwallet.com/#contracts) 
2. Pass contract address
3. Pass ABI interface
4. Click Access and choose buy function 
5. Connect Ledger Nano S
6. Generate transaction
7. Sing transaction using Ledger
8. Send transaction 
9. Call balanceOF function   

Explore other functions ... 
