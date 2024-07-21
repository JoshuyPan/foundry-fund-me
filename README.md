# FundMe Smart Contract

  Contract verified -> https://sepolia.etherscan.io/address/0xb2d70070a729663eb45c3ecacfc12956a9508fcd#code

This repository contains the `FundMe` smart contract, which allows users to fund the contract with ETH. The contract leverages Chainlink's price feed to ensure that the funding meets a minimum USD value.

## Table of Contents

- [FundMe Smart Contract](#fundme-smart-contract)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Installation](#installation)

## Overview

The `FundMe` contract allows users to send ETH to the contract, which is stored and can be withdrawn by the contract owner. The contract ensures that each funding transaction meets a minimum USD value using Chainlink's price feed.

## Features

- Accepts ETH funding
- Enforces a minimum funding amount in USD
- Allows the contract owner to withdraw all funds
- Stores information about funders and their contributions
- Uses Chainlink's AggregatorV3Interface for price conversion

## Requirements

- Solidity ^0.8.18
- Chainlink contracts
- Foundry for compiling and testing

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/JoshuyPan/FundMe.git
   cd FundMe
   ```
  

   ->TODO: i have to finish this section<-