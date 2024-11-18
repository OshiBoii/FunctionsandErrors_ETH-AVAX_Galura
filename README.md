<h1> FunctionsandErrors_ETH-AVAX_Galura </h1> 
A simple Solidity smart contract to demonstrate minting and burning tokens, while tracking balances for each address.

<h1> Description </h1>
This Solidity smart contract demonstrates the use of require(), assert(), and revert() statements for error handling, input validation, and maintaining internal consistency. <br> It is designed to showcase their functionalities through simple scenarios.
 
<h1> Features </h1>
<br> require(): Validates inputs and ensures conditions are met before execution.
<br> assert(): Checks internal consistency and invariants.
<br> revert(): Reverts transactions with a custom error message when conditions are not met.

<br><b> Executing Program </b>
<br> Compile the contract in Remix IDE.
<br> Deploy it using a local VM or Ethereum testnet.
<br> Test the following scenarios:
<br><t> 1. Update balance with valid and invalid inputs.
<br><t> 2. Withdraw amounts exceeding the balance.
<br><t> 3. Call nonOwnerTest() as a non-owner.

<h1> Help </h1>
For common issues:
<br> If the contract doesn’t deploy properly, check if your Solidity version is compatible (^0.8.18).
<br> Ensure you have enough testnet Ether for deploying and interacting with the contract.

<h1> Authors </h1>
Ywan Scazi Galura | 202110347@fit.edu.ph
