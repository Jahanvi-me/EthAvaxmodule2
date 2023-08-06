# Simple Calculator DApp

This repository contains a Simple Calculator DApp built using Solidity for the smart contract and HTML/JavaScript for the frontend interface. The DApp allows users to perform basic arithmetic operations (addition, subtraction, multiplication, and division) by interacting with the smart contract deployed on the Ethereum blockchain using the MetaMask wallet.

## Prerequisites

- MetaMask extension installed on your web browser
- An Ethereum wallet with some test Ether 

## Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/simple-calculator-dapp.git
cd simple-calculator-dapp
```

3. Deploy the smart contract to an Ethereum test network using Truffle or Remix IDE. Update the `contractAddress` variable in the `index.html` file with the deployed contract's address.

## How to Use

1. Open the `index.html` file in a web browser.

2. Click on the "Connect to Metamask" button to connect your MetaMask wallet.

3. After connecting, your wallet address will be displayed.

4. Enter two numbers in the input fields and click on the corresponding operation buttons (Add, Subtract, Multiply, Divide) to perform the calculation.

5. The result of the calculation will be displayed below the buttons.

## Smart Contract

The smart contract `SimpleCalculator` is written in Solidity and provides the following functions:

- `add(uint256 a, uint256 b)`: Adds two numbers and returns the result.
- `subtract(uint256 a, uint256 b)`: Subtracts the second number from the first and returns the result. It checks for non-negativity before performing the operation.
- `multiply(uint256 a, uint256 b)`: Multiplies two numbers and returns the result.
- `divide(uint256 a, uint256 b)`: Divides the first number by the second and returns the result. It checks for division by zero before performing the operation.

## License

This project is licensed under the UNLICENSED license. You can use the code freely for educational and non-commercial purposes.
