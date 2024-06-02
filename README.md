# Building Your First DApp Challenge 
This repository includes building a DApp developed for an assessment challenge. DApp will allow a particular organization to create a vesting schedule for their tokens. 


## Description

An assessment challenge led to the development of a DApp, which is available in this repository. All of the following conditions are met by the contract:

An organization is able to register themselves and their token (basically spinning off a contract for one ERC20 token).
Organisation is able to mention the type of stakeholder and their vesting period (timelock).
Org is able to whitelist addresses for certain stakeholders (founders, investors etc.).
Whitelisted addresses are able to claim their tokens after the vesting period.
## Getting Started

### Installing
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Tokens.sol). Copy and paste the following code into the file:

### Executing program

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile Tokens.sol" button.
![image](https://github.com/Abr-204/Building-First-DApp-Challenge)

We have created solidity contracts for registering orgs and adding stakeholders for each. Next step is to create a front end page for users to connect their wallet and register their org and add stakeholders and vesting details.Then,create a page for users to be able to withdraw if they are whitelisted otherwise only org admin should be able to withdraw.
## Help
if there is any issue while compiling the code then make sure the compiler version which you have written in the code must be the same when you selecting the compiler.

## Authors

Abhay Rana
[@Abhay](https://www.linkedin.com/in/abhay-rana-0a25a6227/)

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details
