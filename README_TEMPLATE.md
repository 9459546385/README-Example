# Project Title
creating a Token using solidity
Simple overview of use/purpose.

## Description
In a contract named MyToken,there will be public variables that store the details about our coin (Token Name, Token Abbrv., Total Supply).
* Our contract will have a mapping of addresses to balances (address => uint).
* We will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
* Our contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
* Lastly, our burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Getting Started
language used 
### Installing
solidity 
### IDE used 
* How/where to download your program
* Any modifications needed to be made to files/folders
Remix IDE
### Executing program

* How to run the program
* Step-by-step bullets
```* Just simply run the following code on Remix IDE.
* Then after compilation is done, deploy the smart contract. Simply put the values of mint and burn functions (i.e. address and values)
* Transact the functions and check balance if the code is being properly deployed.
