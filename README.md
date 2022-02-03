# awesome-cardano

<img src="https://10iyd315iql1cp7mg1jed84g-wpengine.netdna-ssl.com/wp-content/uploads/2021/04/cardano-logo.png" alt="Cardano Image" style="height: 70px; width:250;"/>

This is meant to provide resources for the entire Cardano developer ecosystem. There are a number of disparate resources, so having a centralized location to link to both official and community documentation is helpful.

### Contents
  - [Organization Sites](#organization-sites)
  - [Smart Contracts](#smart-contracts)
  - [Wallets](#wallets)
  - [Developer Components](#developer-components)
  
### Organization Sites
  - [Cardano Foundation Official GitHub](https://github.com/cardano-foundation)
  - [IOHK Official GitHub](https://github.com/input-output-hk/)

### Smart Contracts
- Plutus 
  - Documentation
    - https://plutus-apps.readthedocs.io/en/latest/plutus/explanations/pab.html
    - https://plutus.readthedocs.io/en/latest/plutus/explanations/pab.html
    - https://plutus-pioneer-program.readthedocs.io/en/latest/
    - https://plutonomicon.github.io/plutonomicon/DistributedMap
  - Repositories
    - https://github.com/input-output-hk/plutus-apps
    - https://github.com/input-output-hk/plutus
    - https://github.com/input-output-hk/plutus-pioneer-program
    - https://github.com/input-output-hk/Alonzo-testnet
    - https://github.com/Plutonomicon/plutonomicon
    - https://github.com/input-output-hk?q=plutus&type=all&language=&sort=


### Wallets
- [Daedalus](https://daedaluswallet.io/)
  - Daedalus is a full node wallet. This means that unlike light wallets (e.g.Yoroi, Adalite etc.) Daedalus downloads a full copy of the Cardano blockchain and independently validates every transaction in its history. That way you get maximum security and completely trustless operation, without centrally hosted 3rd party servers.
  - Resources:
      - https://github.com/input-output-hk/daedalus 
- [Yoroi](https://yoroi-wallet.com/)
  - Yoroi is a light wallet for Cardano. It’s simple, fast and secure. Yoroi is an Emurgo product, engineered by IOHK. And it follows best practices for software in the industry including a comprehensive security audit. Daedalus and Yoroi are complements to what they try to achieve. Yoroi looks to be a day to day wallet for a Cardano user.
  - Build methods: Browser Extensions, iOS App, Android App
  - Resources:
    - https://github.com/emurgo/yoroi-ergo-backend 
    - https://github.com/Emurgo/yoroi-frontend 
-  [Adalite](https://adalite.io/)
  - An open-source client-side interface for direct interaction with the Cardano blockchain.

### Developer Components
- [Cardano GraphQL](https://github.com/input-output-hk/cardano-graphql )
  - Cross-platform, typed, and queryable API for Cardano. The project contains multiple packages for composing GraphQL services to meet specific application demands, and a docker-compose stack serving the included cardano-graphql-server Dockerfile and the extended hasura Dockerfile. 
  - Build methods: Docker, source
  - Resources
    - 
    - https://input-output-hk.github.io/cardano-graphql/ 
    - https://github.com/input-output-hk/cardano-graphql/wiki 
- [Cardano Adestria](https://github.com/input-output-hk/cardano-graphql)
  - Adrestia is a collection of products which makes it easier to integrate with Cardano. It comes in different flavours: SDK or high-level APIs. --   - Depending on the use-cases you have and the control that you seek, you may use any of the components below.
  - Build methods: Docker, binaries, source
  - Resources
  - https://input-output-hk.github.io/cardano-rest/submit-api/ 
  - https://input-output-hk.github.io/cardano-rest/explorer-api/ 
- Low-level SDK
  - [cardano-addresses](https://github.com/input-output-hk/cardano-addresses): Address generation, derivation & mnemonic manipulation.
  - [cardano-coin-selection](https://github.com/input-output-hk/cardano-coin-selection): Algorithms for coin selection and fee balancing.
  - [cardano-transactions](https://github.com/input-output-hk/cardano-transactions): Utilities for constructing and signing transactions.
  - [bech32](https://github.com/input-output-hk/bech32): Haskell implementation of the Bech32 address format (BIP 0173).
- [Cardano-rosetta](https://github.com/input-output-hk/cardano-rosetta)
  - Rosetta is an open standard designed to simplify blockchain deployment and interaction.
  - Build methods: Docker, source
  - [Construction API Documentation](https://www.rosetta-api.org/docs/construction_api_introduction.html)
  - [Data API Documentation](https://www.rosetta-api.org/docs/data_api_introduction.html)
  - [Cardano Rosetta Docs](https://github.com/input-output-hk/cardano-rosetta/blob/master/docs)
  - [Developer Docs](https://github.com/input-output-hk/cardano-rosetta/blob/master/docs)
- [Cardano db-sync](https://github.com/input-output-hk/cardano-db-sync )
  - The purpose of Cardano DB Sync is to follow the Cardano chain and take information from the chain and an internally maintained copy of ledger state. Data is then extracted from the chain and inserted into a PostgreSQL database. SQL queries can then be written directly against the database schema or as queries embedded in any language with libraries for interacting with an SQL database.
  - Build methods: Docker, binaries, source 
- [Cardano Ledger Specs](https://github.com/input-output-hk/cardano-ledger-specs)
  - This repository contains the formal specifications, executable models, and implementations of the Cardano Ledger.
- Specification Papers
  - [Plutus integration formal specification: the formal mathematical specification of the addition of Plutus scripts to the ledger rules, following on from the multi-asset formal specification](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/specs.alonzo-ledger/latest/download-by-type/doc-pdf/alonzo-changes).
  - [Multi-asset formal specification: the formal mathematical specification of the addition of multi-assets to the Shelley era ledger rules](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/specs.shelley-ma/latest/download-by-type/doc-pdf/shelley-ma).
  - [Multi-asset binary format specification (CDDL): the binary formats for the ledger with multi-assets using CBOR CDDL schema notation](https://github.com/input-output-hk/cardano-ledger-specs/tree/master/shelley-ma/shelley-ma-test/cddl-files).
  - [Shelley design specification: the primary design document for Cardano Shelley](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/delegationDesignSpec/latest/download-by-type/doc-pdf/delegation_design_spec).
  - [Shelley ledger formal specification: the formal mathematical specification of the Shelley era ledger rules](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/shelleyLedgerSpec/latest/download-by-type/doc-pdf/ledger-spec).
  - [Shelley binary format specification (CDDL): the binary formats for the Shelley ledger using CBOR CDDL schema notation](https://github.com/input-output-hk/cardano-ledger-specs/tree/master/shelley/chain-and-ledger/shelley-spec-ledger-test/cddl-files).
  - [Non-integer calculations specification: details on the parts of the Shelley specification that use real numbers](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/nonIntegerCalculations/latest/download-by-type/doc-pdf/non-integer-calculations).
  - [Stake pool ranking specification: details for a robust stake pool ranking mechanism](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/specs.pool-ranking/latest/download-by-type/doc-pdf/pool-ranking).
  - [Byron chain specification: the formal mathematical specification of the Byron era chain-level rules](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/byronChainSpec/latest/download-by-type/doc-pdf/blockchain-spec).
  - [Byron ledger specification: the formal mathematical specification of the Byron era ledger rules](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/byronLedgerSpec/latest/download-by-type/doc-pdf/ledger-spec).
  - [Byron binary format specification (CDDL): the binary formats for the Byron ledger using CBOR CDDL schema notation](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/blocksCDDLSpec/latest/download-by-type/doc-pdf/binary).
  - [Explanation of the small-step-semantics framework: a guide to the notation and style used by our ledger rules](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/semanticsSpec/latest/download-by-type/doc-pdf/small-step-semantics).
  - Resources
    - https://github.com/input-output-hk/cardano-ledger-specs#cardano-ledger 
- [Cardano SMASH](https://docs.cardano.org/projects/smash/en/latest/)
  - The purpose of SMASH is to aggregate common metadata about stakepools that are registered on the Cardano blockchain, including the name of the stakepool, its “ticker” name etc. This metadata can be curated and provided as a service to delegators, stake pool operators, exchanges etc., enabling independent validation and/or disambiguation of stakepool “ticker” names, for example.
  - Resources
    - [Cardano SMASH Docs](https://docs.cardano.org/projects/smash/en/latest/)
- [Cardano RTView](https://docs.cardano.org/en/latest/rt-view/rt-view.html)
  - RTView enables developers, testers, and general users who are running nodes that are connected to the real cluster to see what is going on and how the nodes are performing. It gives visibility on: how much memory and CPU is being used, the state of the blockchain, how many blocks have been forged by a particular node, how many transactions have been processed, and so on.

### Cardano Blockchain Explorer
  - [Official IOHK explorer](https://explorer.cardano.org/en.html)
  - [Adastat](https://adastat.net/)
  - [Blockchair](https://blockchair.com/cardano)
  - [Cardanoscan](https://cardanoscan.io/)

### IOHK Research Papers
- Delegation and Incentive Specifications
- General Cardano Formal Specifications

### Stakepools
- There are two ways an ada holder can earn rewards: by delegating their stake to a stake pool run by someone else, or by running their own stake pool. The amount of stake delegated to a given stake pool is the primary way the Ouroboros protocol chooses who should add the next block to the blockchain, and receive a monetary reward for doing so. The more stake is delegated to a stake pool (up to a certain point), the more likely it is to make the next block – and the rewards that it earns are shared between everyone who delegated their stake to that stake pool.
- Resources:
https://cardano-foundation.gitbook.io/stake-pool-course/
https://developers.cardano.org/en/testnets/cardano/get-started/creating-a-stake-pool/ 
https://cardano.org/stake-pool-operation/ 
[CoinCashew Guide: How to build a Cardano Stake Pool](https://www.coincashew.com/coins/overview-ada/guide-how-to-build-a-haskell-stakepool-node)
[video guide: How to create a Cardano stake pool](https://www.youtube.com/playlist?list=PLyThQPJpttTJ4r9wUdlWi1DMty4nAT85d)
[building a Cardano stake pool using CNTools](https://www.youtube.com/watch?v=UN4rSRr7LDk&feature=youtu.be)
[big pey’s stake pool video tutorials](https://www.youtube.com/playlist?list=PLyThQPJpttTJ4r9wUdlWi1DMty4nAT85d)


### Miscellaneous
  - Haskell
    - [Learn You a Haskell](http://learnyouahaskell.com/chapters)
    - [Haskell and Cyrpto Mongolia 2020](https://www.youtube.com/playlist?list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm)
  - NixOS
    - [Official Nix Docker image](https://hub.docker.com/r/nixos/nix/)
      - docker pull nixos/nix
  - [IOHK Research Papers](https://iohk.io/en/research/library/)
    - [Delegation and Incentive Specifications](https://hydra.iohk.io/build/6141104/download/1/delegation_design_spec.pdf)
    - [General Cardano Formal Specifications](https://hydra.iohk.io/build/2473732/download/1/ledger-spec.pdf)
    - Proof of Stake 
      - [Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol](https://eprint.iacr.org/2016/889.pdf)
    - Native Assets
      - [UTXO with Multi-Asset Support](https://files.zotero.net/eyJleHBpcmVzIjoxNjE5MzA1ODI4LCJoYXNoIjoiMjI2ZGM2YjY0N2ZhNGRlYWE1NzI5ZmVhMjcyODVmZWEiLCJjb250ZW50VHlwZSI6ImFwcGxpY2F0aW9uXC9wZGYiLCJjaGFyc2V0IjoiIiwiZmlsZW5hbWUiOiJDaGFrcmF2YXJ0eSBldCBhbC4gLSAyMDIwIC0gVVRYT21hVVRYTyB3aXRoIE11bHRpLUFzc2V0IFN1cHBvcnQucGRmIn0%3D/64af4d3d4084667ec87c50e140f738664501ecbcc71a160c41971a3e5b046536/Chakravarty%20et%20al.%20-%202020%20-%20UTXOmaUTXO%20with%20Multi-Asset%20Support.pdf)
    - Shelley
      - [Introduction to the design of the Data Diffusion and Networking for Cardano Shelley](https://files.zotero.net/eyJleHBpcmVzIjoxNjE5MzA1Mjk3LCJoYXNoIjoiYjg2OTdhOTI3MTE5NTMwNDVjMzVmNmZlMTYxOGJjNzciLCJjb250ZW50VHlwZSI6ImFwcGxpY2F0aW9uXC9wZGYiLCJjaGFyc2V0IjoiIiwiZmlsZW5hbWUiOiJDb3V0dHMgZXQgYWwuIC0gSW50cm9kdWN0aW9uIHRvIHRoZSBkZXNpZ24gb2YgdGhlIERhdGEgRGlmZnVzaW9uIGEucGRmIn0%3D/f059ea067030764f26a60564e53659a4068657c9ba5bb53ddf04aba5a8ad94ae/Coutts%20et%20al.%20-%20Introduction%20to%20the%20design%20of%20the%20Data%20Diffusion%20a.pdf)
      - [The Shelley Networking Protocol](https://hydra.iohk.io/build/4314538/download/2/network-spec.pdf)
      - Byron
        - [Byron Ledger Specification](https://hydra.iohk.io/job/Cardano/cardano-ledger-specs/byronLedgerSpec/latest/download-by-type/doc-pdf/ledger-spec)
      - Plutus papers
        - [Alonzo Formal Specs](https://hydra.iohk.io/build/6131346/download/1/alonzo-changes.pdf)
        - [Unraveling Recursion](https://doi.org/10.1007/978-3-030-33636-3_15)
        - [System F in Agda](https://doi.org/10.1007/978-3-030-33636-3_10)
        - [The Extended UTXO Model](https://hydra.iohk.io/job/Cardano/plutus/linux.docs.papers.eutxo/latest/download-by-type/doc-pdf/eutxo)
        - [UTXOma: UTXO with Multi-Asset Support](https://hydra.iohk.io/job/Cardano/plutus/linux.docs.papers.utxoma/latest/download-by-type/doc-pdf/utxoma)
        - [Native Custom Tokens in the Extended UTXO Model](https://hydra.iohk.io/job/Cardano/plutus/linux.docs.papers.eutxoma/latest/download-by-type/doc-pdf/eutxoma)
  - CIPs (Cardano Improvement Proposals)
    - [Cardano CIPs](https://cips.cardano.org/) 
    - [Cardano Foundation CIP Github](https://github.com/cardano-foundation/CIPs)
  - Project Catalyst
    - [Cardano Catalyst Project](https://cardanocataly.st/)
    - [CF Catalyst Guide](https://forum.cardano.org/t/user-guide-ways-to-participate-in-project-catalyst/49405)
    -[IOHK Catalyst Blog Post](https://iohk.io/en/blog/posts/2021/02/12/our-million-dollar-baby-project-catalyst/)

### Ecosystem Overview
