# Create a Token

This project involves creating a simple smart contract for a token on the Ethereum blockchain. The token contract will have functionalities to mint and burn tokens. It will keep track of the token name, abbreviation, total supply, and the balances of different addresses.

## Description

The MyToken smart contract is designed to manage a token named META with the abbreviation META. The contract includes public variables to store the token's details, a mapping to track balances of different addresses, and functions to mint and burn tokens. The mint function increases the total supply and the balance of a specified address, while the burn function decreases the total supply and the balance of a specified address, ensuring that the address has sufficient balance to burn the specified amount.

## Getting Started

### Installing
To get started with this project, you'll need to have the following installed:

* Node.js
* npm (Node Package Manager)
* Truffle or Hardhat (for Ethereum development)
* MetaMask (for interacting with the Ethereum network)
* How/Where to Download Your Program

Clone the repository from GitHub:
```
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
```
### Any Modifications Needed to Be Made to Files/Folders

Ensure that you have a '.env' file with your Ethereum network configuration if you're using a deployment tool like Truffle or Hardhat.

### Executing program

#### How to Run the Program
1. Compile the smart contract:
```
truffle compile
```
or

```
npx hardhat compile
```

2. Deploy the smart contract:

```
truffle migrate --network your_network
```

or

```
npx hardhat run scripts/deploy.js --network your_network
```

### Step-by-Step Bullets
1. Clone the repository.
2. Install the necessary dependencies.
3. Compile the smart contract.
4. Deploy the smart contract to your desired network.

```
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
npm install
truffle compile
truffle migrate --network your_network
```
## Help
### Any Advice for Common Problems or Issues
* Ensure your Ethereum client is running if you're deploying to a local network.
* Check your MetaMask configuration for the correct network.
* Verify your .env file for the correct network and private key setup.
### Command to Run if Program Contains Helper Info
If your program contains helper info, run:
```
npx hardhat help
```

## Authors

Nikhil Tripathi
@incrediblenikhil02
@Great_Alys



## License

This project is licensed under the MIT License - see the LICENSE.md file for details
