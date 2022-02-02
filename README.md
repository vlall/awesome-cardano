# awesome-cardano
This repository tries to provide resources for the entire Cardano developer ecosystem. There are a number of disparate resources, so having a centralized location to link to both official and community documentation is helpful.

[Cardano Foundation Official GitHub](https://github.com/cardano-foundation)

[IOHK Official GitHub](https://github.com/input-output-hk/)


### Smart Contracts
- Plutus 
  - Documentation
    - https://plutus-apps.readthedocs.io/en/latest/plutus/explanations/pab.html
    - https://plutus.readthedocs.io/en/latest/plutus/explanations/pab.html
    - https://plutus-pioneer-program.readthedocs.io/en/latest/
  - Repositories
    - https://github.com/input-output-hk/plutus-apps
    - https://github.com/input-output-hk/plutus
    - https://github.com/input-output-hk/plutus-pioneer-program
    - https://github.com/input-output-hk/Alonzo-testnet
    - https://github.com/input-output-hk?q=plutus&type=all&language=&sort=

### Wallets
- Daedalus
  - Description: Daedalus is a full node wallet. This means that unlike light wallets (e.g.Yoroi, Adalite etc.) Daedalus downloads a full copy of the Cardano blockchain and independently validates every transaction in its history. That way you get maximum security and completely trustless operation, without centrally hosted 3rd party servers.
  - Resources:
      - https://daedaluswallet.io/
      -  https://github.com/input-output-hk/daedalus 
- Yoroi
  - Description: Yoroi is a light wallet for Cardano. It’s simple, fast and secure. Yoroi is an Emurgo product, engineered by IOHK. And it follows best practices for software in the industry including a comprehensive security audit. Daedalus and Yoroi are complements to what they try to achieve. Yoroi looks to be a day to day wallet for a Cardano user.
  - Build methods: Browser Extensions, iOS App, Android App
  - Resources:
    - https://yoroi-wallet.com/
    - https://github.com/emurgo/yoroi-ergo-backend 
    - https://github.com/Emurgo/yoroi-frontend 
- Adalite
  - Description: An open-source client-side interface for direct interaction with the Cardano blockchain.
  - Resources:
  - https://adalite.io/ 

### Developer Components
- Cardano GraphQL
  - Description: Cross-platform, typed, and queryable API for Cardano. The project contains multiple packages for composing GraphQL services to meet specific application demands, and a docker-compose stack serving the included cardano-graphql-server Dockerfile and the extended hasura Dockerfile. 
  - Build methods: Docker, source
  - Resources
    - https://github.com/input-output-hk/cardano-graphql 
    - https://input-output-hk.github.io/cardano-graphql/ 
    - https://github.com/input-output-hk/cardano-graphql/wiki 
- Cardano Adestria
  - Description: Adrestia is a collection of products which makes it easier to integrate with Cardano. It comes in different flavours: SDK or high-level APIs. --   - Depending on the use-cases you have and the control that you seek, you may use any of the components below.
  - Build methods: Docker, binaries, source
  - Resources
  - https://input-output-hk.github.io/adrestia/ 
  - https://input-output-hk.github.io/cardano-rest/submit-api/ 
  - https://input-output-hk.github.io/cardano-rest/explorer-api/ 
- Low-level SDK
  - cardano-addresses: Address generation, derivation & mnemonic manipulation.
  - cardano-coin-selection: Algorithms for coin selection and fee balancing.
  - cardano-transactions: Utilities for constructing and signing transactions.
  - bech32: Haskell implementation of the Bech32 address format (BIP 0173).
- Cardano-rosetta 
  - Description: Rosetta is an open standard designed to simplify blockchain deployment and interaction.
  - Build methods: Docker, source
- Resources
  - Construction API Documentation Users of the Cardano Rosetta Construction API 
  - Data API Documentation Users of the Cardano Rosetta Data API 
- Cardano Rosetta Docs Cardano Rosetta specific documentation 
- Developer Core or external developers of cardano-rosetta-server 
- Cardano db-sync
  - Description: The purpose of Cardano DB Sync is to follow the Cardano chain and take information from the chain and an internally maintained copy of ledger state. Data is then extracted from the chain and inserted into a PostgreSQL database. SQL queries can then be written directly against the database schema or as queries embedded in any language with libraries for interacting with an SQL database.
  - Build methods: Docker, binaries, source
  - Resources
  - https://github.com/input-output-hk/cardano-db-sync 
- Cardano Ledger Specs
  - Description: This repository contains the formal specifications, executable models, and implementations of the Cardano Ledger.
- Specification Papers
  - Plutus integration formal specification: the formal mathematical specification of the addition of Plutus scripts to the ledger rules, following on from the multi-asset formal specification.
  - Multi-asset formal specification: the formal mathematical specification of the addition of multi-assets to the Shelley era ledger rules.
  - Multi-asset binary format specification (CDDL): the binary formats for the ledger with multi-assets using CBOR CDDL schema notation.
  - Shelley design specification: the primary design document for Cardano Shelley.
  - Shelley ledger formal specification: the formal mathematical specification of the Shelley era ledger rules.
  - Shelley binary format specification (CDDL): the binary formats for the Shelley ledger using CBOR CDDL schema notation.
  - Non-integer calculations specification: details on the parts of the Shelley specification that use real numbers.
  - Stake pool ranking specification: details for a robust stake pool ranking mechanism.
  - Byron chain specification: the formal mathematical specification of the Byron era chain-level rules.
  - Byron ledger specification: the formal mathematical specification of the Byron era ledger rules.
  - Byron binary format specification (CDDL): the binary formats for the Byron ledger using CBOR CDDL schema notation.
  - Explanation of the small-step-semantics framework: a guide to the notation and style used by our ledger rules.
- Resources
  - https://docs.cardano.org/en/latest/explore-cardano/cardano-architecture-overview/index.html 
  - https://github.com/input-output-hk/cardano-ledger-specs#cardano-ledger 
- Cardano SMASH
  - Description: The purpose of SMASH is to aggregate common metadata about stakepools that are registered on the Cardano blockchain, including the name of the stakepool, its “ticker” name etc. This metadata can be curated and provided as a service to delegators, stake pool operators, exchanges etc., enabling independent validation and/or disambiguation of stakepool “ticker” names, for example.
- Resources
  - Cardano SMASH Docs
- Cardano RTView
  - Description: RTView enables developers, testers, and general users who are running nodes that are connected to the real cluster to see what is going on and how the nodes are performing. It gives visibility on: how much memory and CPU is being used, the state of the blockchain, how many blocks have been forged by a particular node, how many transactions have been processed, and so on.


### Ecosystem Overview



### Cardano Blockchain Explorer
  - https://explorer.cardano.org/en.html 
Haskell
  - http://learnyouahaskell.com/chapters
  - https://www.youtube.com/playlist?list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm 

### NixOS
  - Official Nix Docker image
  - docker pull nixos/nix

### IOHK Research Papers
- Delegation and Incentive Specifications
- General Cardano Formal Specifications

### Proof of Stake
- Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol
Native Assets
- UTXO with Multi-Asset Support
Shelley
Introduction to the design of the Data Diffusion and Networking for Cardano Shelley
The Shelley Networking Protocol 
Byron
Byron Ledger Specification
Plutus papers
Alonzo Formal Specs
Unraveling Recursion (published version)
System F in Agda (published version)
The Extended UTXO Model (in press)
UTXOma: UTXO with Multi-Asset Support (in press)
Native Custom Tokens in the Extended UTXO Model (in press)