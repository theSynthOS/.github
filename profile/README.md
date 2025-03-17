# Hi there 👋

# SynthOS - Verifiable DeFAI Agent Marketplace
## 👀What is SynthOS?
SynthOS is a verifiable DeFAI agent marketplace where users create no-code AI agents, and investors select policy-validated, automated yield strategies tailored to their risk appetite.

## 📌Product Description
### ‼️Problem Statement

SynthOS aims to solve key challenges in the DeFAI automation space:

- **Lack of verifiability**： 
AI agents operate as black boxes with no transparency.

- **Limited user control**：
No modular framework for setting execution rules.

- **High barriers to automation**：
Current solutions are complex and non-intuitive.

### 🎯Vision
A decentralized AI agent economy where users can create, customize, and monetize verifiable DeFi automation without security risks.

### 🚨Unique Value Proposition
A policy-based AVS framework powered by Autonome & Othentic. 

## ⚒️How it's Made?
SynthOS enables users to deploy AI agents with predefined execution rules while secure agent actions with Eigen Layer validators and utilize Scroll for low-latency, gas optimized transactions.

## The Stack
1. Frontend - Next.JS, TailwindCSS, React, Javascript, Typescript
2. UI Library - DaisyUI, Aceternity UI
3. Web3 Development - Solidity, Foundry, ThirdWeb


## Future Roadmap
![image](https://github.com/user-attachments/assets/08f1d183-d67a-4940-9df8-e50c1350d346)

# SynthOS Smart Contracts

### SynthOS is a Verifiable DeFAI Agent Marketplace that implements a cross-chain policy validation system between Base and Scroll networks. The system enables secure validation of agent transactions against predefined policies across different chains.

### System Architecture
![Diagram](https://github.com/user-attachments/assets/8c60b9c4-e1b1-468b-a8cb-e0a59a604d21)

## Overview

The Policy-based Transaction Validation AVS is a decentralized framework that enables the validation of blockchain transactions against predefined policies. It leverages the Othentic Stack to provide a secure and transparent validation mechanism.

The system consists of four main smart contracts:

1. **PolicyRegistry.sol**

   - Manages the registration and storage of policies
   - Defines rules and constraints for agent actions
   - Handles policy lifecycle (creation, activation, deactivation)

2. **AgentRegistry.sol**

   - Manages agent registration and metadata
   - Links agents to their associated policies
   - Tracks agent status and capabilities

3. **PolicyCoordinator.sol**

   - Core contract for transaction validation
   - Coordinates between agents and their policies
   - Validates transactions against time, function, and resource constraints
   - Receives cross-chain messages from Base network
   - Deployed on Scroll Sepolia

4. **CrosschainSender.sol**
   - Handles cross-chain communication from Base to Scroll
   - Integrates with Hyperlane for secure message passing
   - Acts as an AVS Logic hook for task validation
   - Deployed on Base Sepolia

### Cross-Chain Flow

![Image](https://github.com/user-attachments/assets/ccee5253-acdf-43c6-8cb6-f7efd1e12589)

### Key Features

- **Cross-Chain Validation**: Enables policy validation across Base and Scroll networks
- **Policy Management**: Flexible policy definition with time, function, and resource constraints
- **Agent Registry**: Secure registration and management of DeFi agents
- **Hyperlane Integration**: Secure cross-chain message passing
- **Task Validation**: Comprehensive validation system for agent actions

### Deployed Contracts

- **Scroll Sepolia**:

  - PolicyRegistry: [`0x3579D1B3606d7401A524F78ba8565374639348Fd`](https://sepolia.scrollscan.com/address/0x3579D1B3606d7401A524F78ba8565374639348Fd#code)
  - AgentRegistry: [`0xd97d57bae995259fe1Eb040a63A02F86a4398285`](https://sepolia.scrollscan.com/address/0xd97d57bae995259fe1Eb040a63A02F86a4398285#code)
  - TaskRegistry: [`0x5e38f31693CcAcFCA4D8b70882d8b696cDc24273`](https://sepolia.scrollscan.com/address/0x5e38f31693CcAcFCA4D8b70882d8b696cDc24273#code)
  - PolicyCoordinator: [`0xbAdfD548E1D369633Cf23a53C7c8dC37607001e9`](https://sepolia.scrollscan.com/address/0xbAdfD548E1D369633Cf23a53C7c8dC37607001e9#code)
  - Faucet: [`0x602396FFA43b7FfAdc80e01c5A11fc74F3BA59f5`](https://sepolia.scrollscan.com/address/0x602396FFA43b7FfAdc80e01c5A11fc74F3BA59f5#code)

- **Base Sepolia**:

  - CrosschainSender Contract (AVS Logic Hook): [`0xd97d57bae995259fe1Eb040a63A02F86a4398285`](https://base-sepolia.blockscout.com/address/0xd97d57bae995259fe1Eb040a63A02F86a4398285?tab=contract)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
