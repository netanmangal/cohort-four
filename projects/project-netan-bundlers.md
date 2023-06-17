# ROP-5 - Bundlers (EIP-4337)

ROP-5 - Ethereum Supply Network Health Framework - Bundlers (EIP-4337)

(In progress) - (I warmly embrace the chance to make necessary modifications based on the inputs and guidance provided by the esteemed mentors under the Ethereum Protocol Fellowship Program).

## Motivation

The release of long-awaited AA (EIP-4337) aims to acheive the goal of allowing userrs to use smart contract wallets. This proposal focuses on providing the higher-laye solution rather than altering the underlying Ethereum consensus unlike previous attempts (EIP-86 / EIP 1014 and more). In this proposal, a new pseudo-transaction object called UserOperation is introduced. Users send UserOperation objects to a separate mempool dedicated to user operations. Bundlers bundle multiple UserOperations into a single transaction by calling a special contract called EntryPoint. This transaction is then included in a block.

The motivation to carry out this project is the advance the goal of RIG Open Problem #5 - to develop the practical frameworks to monitor Ethereum Supply Chain Health rooted in data specifications, analysis and to discuss and create tested and robust metrics - for Bundlers which are key INFRA components enabling Account Abstraction.

## Project description

 - Capture and store bundler-related information, such as bundler activities, transaction inclusion/exclusion, fee structures, and order of transactions in the mempool
 - Collaborate with existing bundler projects to understand and research regarding bundler dynamics and it's impact on Ethereum ecosystem.

## Specification

 The latest specification for EIP-4337 can be found here - https://eips.ethereum.org/EIPS/eip-4337.

## Roadmap

 - [ ] Understanding the specifications pertaining to bundlers (2 weeks).
 - [ ] Design data collection mechanisms from the existing bundler infra (2 weeks).
 - [ ] Implement the data collection component to capture bundler-related information from the Ethereum network (4 weeks).

## Possible challenges

  - Figuring out the necessary implementational details, specifications and key constraints for EIP-4337 bundlers.
  - Adapt to constant evolution of bundlers and it's technical specs.
  - Gathering appropriate metrices accurately and comprehensively to support the advancement of Ethereum Supply Network Health Framework (ROP 5).
  - Outreaching industry partners to acquire the required permissions to collect the specific data points (if any will be required).

## Goal of the project

 - Extablish the key metrics as indicators for Ethereum Supply Chain Health pertaining to Bundlers purposed for AA.
 - Foster collaboration and knowledge sharing amoung bundler projects, reseachers and the Ethereum Community.
 - I would like to advance this research and wish to work towards studying the potential of Bundler Extractable Value (BEV).


### Mentors

#### Internal
 - Barnabé Monnot (barnabe.mannot@ethereum.org)

 #### External
  - Thomas Thiery (thomas.thiery@ethereum.org)
  - Davide Crapis (davide.crapis@ethereum.org)

## Resources

This section will contain the relevant work links for the project.
