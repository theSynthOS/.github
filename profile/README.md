 Hi there 👋

# SynthOS - Verifiable DeFAI Agent Marketplace
## 👀What is SynthOS?
SynthOS is a decentralized marketplace for Verifiable DeFAI(Decentralized Finance AI) Agents, allowing users to deploy, manage, and interact with AI-driven DeFi automation while maintaining security through on chain attestation.

## 📌Product Description
### ‼️Problem Statement
SynthOS aims to solve key challenges in the DeFAI automation space:
Lack of verifiability – AI agents operate as black boxes with no transparency.
Limited user control – No modular framework for setting execution rules.
High barriers to automation – Current solutions are complex and non-intuitive.

### 🎯Vision
A decentralized AI agent economy where users can create, customize, and monetize verifiable DeFi automation without security risks.

### 🚨Unique Value Proposition



## ⚒️How it's Made?
SynthOS enables users to deploy AI agents with predefined execution rules while secure agent actions with Eigen Layer validators and utilize Scroll for low-latency, gas optimized transactions.

## The Stack
1. Frontend - Next.JS, TailwindCSS, React, Javascript, Typescript
2. UI Library - DaisyUI, Aceternity UI
3. Web3 Development - Solidity, Foundry, ThirdWeb

## 🎯 Sponsor Prizes


## Future Roadmap


# SynthOS Smart Contracts

### SynthOS is a Verifiable DeFAI Agent Marketplace that implements a cross-chain policy validation system between Base and Scroll networks. The system enables secure validation of agent transactions against predefined policies across different chains.

### System Architecture

The system consists of four main smart contracts:

1. **PolicyRegistry.sol**

   - Manages policy lifecycle (creation, activation, deactivation)
   - Defines rules and constraints for agent actions

2. **AgentRegistry.sol**

   - Registers agent and links them to policies
   - Tracks agent status and capabilities

3. **PolicyCoordinator.sol**
   
   - Validates transactions against time, function, and resource constraints.
   - Receives cross-chain messages from Base network
   - Deployed on Scroll Sepolia

5. **CrosschainSender.sol**
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

  - PolicyRegistry: [`0xa7b0446a0fa8e8c503774987931e071e3ddf271a`](https://sepolia.scrollscan.com/address/0xa7b0446a0fa8e8c503774987931e071e3ddf271a#code)
  - AgentRegistry: [`0x6ed02bf56beb79d47f734ee6bb4701b9789b4d5b`](https://sepolia.scrollscan.com/address/0x6ed02bf56beb79d47f734ee6bb4701b9789b4d5b#code)
  - TaskRegistry: [`0x5e38f31693CcAcFCA4D8b70882d8b696cDc24273`](https://sepolia.scrollscan.com/address/0x5e38f31693CcAcFCA4D8b70882d8b696cDc24273#code)
  - PolicyCoordinator: [`0x2e22bc79b58117015bf458045488e09aaa0bb794`](https://sepolia.scrollscan.com/address/0x2e22bc79b58117015bf458045488e09aaa0bb794#code)

- **Base Sepolia**:

  - CrosschainSender Contract (AVS Logic Hook): [`0x201cE172d07566BEa747D18848534f4d8aDBe69f`](https://base-sepolia.blockscout.com/address/0x201cE172d07566BEa747D18848534f4d8aDBe69f?tab=contract)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
