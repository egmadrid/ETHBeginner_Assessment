# ETHBeginner_Assessment

This Solidity program will allow a user to mint and burn tokens to either increase or decrease the total supply and the address' balance. The purpose of this program is to serve as a project assessment for the ETH PROOF: Beginner EVM Course.

## Description

### Assessment Requirements:
1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the “sender” address by that amount
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the “sender”.
5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on "Create new file" in the left-hand sidebar. Save the file with a .sol extension (e.g., ETH_AssessmentProject.sol). Copy and paste the contents of the .sol file in the reposiory into the IDE.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.26" (or another compatible version), and then click on the "Compile ETHBeginner_AssessmentProject.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

### Using Program

Once the contract is deployed, you can interact with it by calling the various functions. Click on the "MYTOKEN" contract in the left-hand sidebar under "Deployed Contracts", and then click on the different functions to see or change their values. 

To mint tokens, input an address and a value then click on the "transact" button. To burn tokens, do the same as with minting but make sure the value is lower than or equal to the balance of the address.

To check the balances, simply click the dropdown icon next to the balances function, enter an the address, and click "call".

## Authors

Erika Gabrielle Madrid <br>
201920013@fit.edu.ph

## License

This project is licensed under the MIT License.
