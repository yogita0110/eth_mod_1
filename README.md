# ErrorsAndFunctions

This smart contract demonstrates the use of `require()`, `assert()`, and `revert()` statements in Solidity by validating if a given number is even. It counts the number of even numbers provided to the contract functions.

## Description

The `ErrorsAndFunctions` contract is designed to showcase how to use error handling statements in Solidity. It includes three functions that check if a given number is even using `require()`, `assert()`, and `revert()`. If the number is even, it increments an `evenCount` state variable.

## Getting Started

### Installing

1. Clone the repository or copy the contract code.
2. Navigate to [Remix](https://remix.ethereum.org/) or any Solidity development environment.

### Executing program

1. Open [Remix](https://remix.ethereum.org/).
2. Create a new file and paste the contract code into it.
3. Compile the contract using the Solidity compiler (version 0.8.17 or above).
4. Deploy the contract using the "Deploy & Run Transactions" tab.
5. Interact with the contract functions:

```solidity
// Example commands in Remix

// Call the requireEvenNumber function with an even number
ErrorsAndFunctions.requireEvenNumber(2);

// Call the assertEvenNumber function with an even number
ErrorsAndFunctions.assertEvenNumber(4);

// Call the revertEvenNumber function with an even number
ErrorsAndFunctions.revertEvenNumber(6);
```

## Authors
Yogita Rani 
iamyogita1001@gmail.com

## Video Walkthrough
link

## License
This project is licensed under the MIT License 
