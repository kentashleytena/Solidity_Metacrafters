# Hello world Contract
This Solidity program is a simple "Hello World" program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how it works.
# Discription
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a single function that returns the string "Hello World!". This program serves as a simple and straightforward introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.
# Getting started
# Insalling
To use this contract, you will need to have the following installed:

Node.js (version 14 or higher) npm (version 6 or higher) Truffle Suite (version 5 or higher) You can install Truffle Suite using npm by running the following command: npm install -g truffle

# Executing program

To execute the program, follow these steps:

Open a terminal or command prompt and navigate to the directory where the contract file is located. Compile the contract using the following command:

truffle compile

Deploy the contract to a local Ethereum network using the following command:

truffle migrate

Interact with the contract using the Truffle console:

truffle console
# Running the program

To run the program, follow these steps:

In the Truffle console, create a new instance of the contract:

let contract = await HelloWorld.deployed() Call the mint function to create new tokens

contract.mint("0x1234567890abcdef", 100) contract.mint("0x1234567890abcdef", 100)

Call the burn function to destroy tokens: contract.burn("0x1234567890abcdef", 50)

Check the balance of an address: contract.balances("0x1234567890abcdef")

# Help

If you encounter an error while compiling the contract, make sure that you have the correct version of Solidity installed. If you encounter an error while deploying the contract, make sure that you have a local Ethereum network set up and running.

# Authors

Kent Ashley Tena METACRAFTERS

# License

This project is licensed under the MARICAR LOVERIZA License - MIT License

Copyright (c) 2023 MetacrafterChris

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

