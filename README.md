# Token Contract Assessment
The purpose of this project is to create a contract for a custom token with basic functionalities such as minting new tokens, burning tokens, and keeping track of token balances for different addresses. 

## Description
The contract has public variables that store the details about the user's token, including its name, abbreviation, and total supply. The mapping of addresses to balances allows for easy tracking of token ownership and the mint and burn functions enable the supply to be adjusted according to the needs of the system. The burn function includes conditionals to ensure that the balance of the account is sufficient for burning tokens. Overall, this project provides a basic framework for creating and managing a custom token on the blockchain.

## Getting Started
### Executing Program
* To execute this program, you may utilize Remix, which is an online Integrated Development Environment (IDE) for Solidity. To begin, navigate to the Remix website located at https://remix.ethereum.org/.

* After accessing the Remix website, you can initiate a new file by selecting the "+" symbol situated in the left-hand sidebar. Save the file with a .sol extension (such as HelloWorld.sol) and then proceed to copy and paste the code (myToken.sol) into the created file.

* To compile the code, go to the "Solidity Compiler" tab located on the left-hand sidebar. Ensure that the "Compiler" option is set to a compatible version, such as "0.8.4", and then select the "Compile myToken.sol" button.

* Once the code has been compiled, navigate to the "Deploy & Run Transactions" tab on the left-hand sidebar to deploy the contract. From the dropdown menu, select the "myToken" contract and press the "Deploy" button.

* After the contract is deployed, you can input values at the "mint" and "burn" function and click transact. you can also check the balances by inputting the address you want to track and by calling it. Lastly, you can view the values of the totalSupply, tokenName, and tokenAbbrv by simply clicking on it.

## Author
Patricia Go
guided by: Metacrafters mentor
