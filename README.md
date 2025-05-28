# Foundry Fund Me

A smart contract project built using [Foundry](https://book.getfoundry.sh/) that demonstrates funding and withdrawal functionality. This project is part of my journey to becoming a smart contract auditor.

## 🚀 Project Overview

This project allows users to fund a contract and the contract owner to withdraw the funds. It integrates with Chainlink price feeds to enforce a minimum USD contribution threshold.

## 🧱 Built With

- [Solidity](https://soliditylang.org/)
- [Foundry](https://book.getfoundry.sh/) (Forge & Cast)
- [Chainlink](https://chain.link/)
- [Hardhat (for reference)](https://hardhat.org/) *(if applicable)*
- [GitHub](https://github.com/)

## 📂 Directory Structure

foundry-fund-me/
├── lib/ # External dependencies
├── script/ # Deployment scripts
├── src/ # Smart contracts
│ └── FundMe.sol
├── test/ # Foundry tests
│ ├── FundMeTest.t.sol
│ └── InteractionsTest.t.sol
├── .gitignore
├── foundry.toml
└── README.md # Project documentation

## 🧪 How to Test

To run the tests locally:

```bash
forge test
```

## 🛠️ How to Deploy

Set your environment variables:

PRIVATE_KEY

RPC_URL

Deploy with Forge script:

forge script script/DeployFundMe.s.sol --rpc-url $RPC_URL --private-key $PRIVATE_KEY --broadcast

## 🔒 Security & Audit Notes

This project is a practice ground for learning:

Proper test coverage

Handling real ETH funding and withdrawal scenarios

Using mocks for Chainlink integration in local testing

## 🙋‍♂️ Author

Victor Mkpo

[GitHub](https://github.com/vmkpo)

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

## Course link for this Project.


[UPDRAFT.CYFRIN](https://updraft.cyfrin.io/courses/foundry/foundry-fund-me) 






