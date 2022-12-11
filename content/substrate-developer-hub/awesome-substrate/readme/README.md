# Awesome Substrate Overview

A curated list of awesome projects and resources related to the Substrate blockchain development framework.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/substrate-developer-hub/awesome-substrate/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 substrate-developer-hub/awesome-substrate](https://github.com/substrate-developer-hub/awesome-substrate) · ⭐ 615 · 🏷️ Decentralized Systems

[ [Daily](/content/substrate-developer-hub/awesome-substrate/README.md) / [Weekly](/content/substrate-developer-hub/awesome-substrate/week/README.md) / Overview ]

---

# Awesome Substrate [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> An awesome list is a list of awesome things curated by the Substrate community.

Substrate is a framework for building upgradable, modular and efficient
blockchains. Substrate is an open-source library of [Rust](https://www.rust-lang.org/) code that is
maintained by [Parity Technologies](https://www.parity.io/). Source code available on
[GitHub (⭐7.7k)](https://github.com/paritytech/substrate).

## Contents

*   [Resources](#resources)
*   [Support](#support)
*   [Social](#social)
*   [Events](#events)
*   [Blogs](#blogs)
*   [Videos](#videos)
*   [Templates](#templates)
*   [FRAME Pallets](#frame-pallets)
*   [Framework Extensions](#framework-extensions)
*   [Client Libraries](#client-libraries)
*   [Mobile](#mobile)
*   [Tools](#tools)
*   [Products and Services](#products-and-services)
*   [Alternative Implementations](#alternative-implementations)
*   [SCALE Codec](#scale-codec)

## Resources

*   [DotJobs](https://dotjobs.net/) - A job board for the Substrate and Polkadot ecosystem projects, maintained by [Stateless.Money](https://stateless.money/).
*   [Developer Hub GitHub](https://github.com/substrate-developer-hub/) - Substrate Developer Hub repositories.
*   [Ecosystem Projects](https://substrate.io/ecosystem/projects/) - Projects and teams building with Substrate.
*   [Polkadot Stack (⭐692)](https://github.com/w3f/Grants-Program/blob/master/docs/polkadot_stack.md) - An `awesome list` maintained by our friends at [Web3 Foundation](https://web3.foundation/).
*   [Official Homepage](https://substrate.io/) - Vision, ecosystem, opportunities, and much more.
    *   [Docs](https://docs.substrate.io/) - Developer documentation.
    *   [Tutorials](https://docs.substrate.io/tutorials) - Guided exercises to get you started.
    *   [How-to guides](https://docs.substrate.io/how-to-guides) - Workflows outlined to achieve a specific goal.
    *   [Reference Docs](https://docs.substrate.io/rustdocs) - Versioned API documentation.
*   Technical Papers
    *   [Polkadot Lightpaper](https://polkadot.network/Polkadot-lightpaper.pdf)
    *   [Polkadot: Vision for a heterogeneous multi-chain framework (⭐187)](https://github.com/polkadot-io/polkadotpaper/raw/master/PolkaDotPaper.pdf)
    *   [Overview of Polkadot and its Design Considerations](https://arxiv.org/abs/2005.13456.pdf)
        *   [Chinese Translation (⭐30)](https://github.com/AmadeusGB/Overview-of-Polkadot) (by community)

## Support

*   [Builders Program](https://substrate.io/ecosystem/substrate-builders-program/) - White-glove solutions and dedicated support team for visionary teams using Substrate.
*   [Stack Exchange](https://substrate.stackexchange.com/) - The best place for all technical questions.
*   [Web3 Foundation Grants](https://web3.foundation/grants) - Funding for ecosystem development.
*   [Polkadot Treasury](https://wiki.polkadot.network/docs/learn-treasury#creating-a-treasury-proposal) - The Treasury funds are allocated through the voting on spending proposal.

## Social

*   [Substrate Devs Chat (Telegram)](https://t.me/substratedevs) - Chat with other Substrate developers, also bridged to [matrix](https://matrix.to/#/#substratedevs:matrix.org).
*   [Twitter](https://twitter.com/substrate_io) - Follow us to stay up-to-date.

## Events

*   [Sub0 Developer Conference](https://sub0.parity.io/) - Semiannual, online and in-person for all
    things Substrate.
*   [Substrate Seminar](https://substrate.io/ecosystem/resources/seminar/) - Bi-weekly
    collaborative learning sessions.

## Blogs

*   [DotLeap](https://dotleap.com/) - Polkadot and Substrate Community blog and newsletter.
*   [Official](https://www.parity.io/blog/tag/parity-substrate) - Published by Parity.

## Videos

*   [Parity YouTube](https://www.youtube.com/c/paritytech)
    *   [Substrate Seminar (YouTube Archive)](https://www.youtube.com/playlist?list=PLp0_ueXY_enXRfoaW7sTudeQH10yDvFOS)
    *   [Sub0 Conference Oct. 2020](https://www.youtube.com/playlist?list=PLp0_ueXY_enUZk1RuEAU9ly5h0wy5FuLs)
    *   [Sub0 Conference Dec. 2019](https://www.youtube.com/playlist?list=PLp0_ueXY_enWZ4UZE7rM0hdT8Z_ZTjU5V)
    *   [Sub0 Conference Apr. 2019](https://www.youtube.com/playlist?list=PLp0_ueXY_enWqrfP_vR4PLhzQj76fLT8y)
*   [Polkadot Network Technical Explainers](https://www.youtube.com/playlist?list=PLOyWqupZ-WGuAuS00rK-pebTMAOxW41W8)
*   [Seminar Crowdcast](https://www.crowdcast.io/e/substrate-seminar-2/) - Upcoming events and latest recordings.
    *   [Old Seminar Crowdcast](https://www.crowdcast.io/e/substrate-seminar/) - Archive only.
*   [Substrate: A Rustic Vision for Polkadot by Gavin Wood at Web3 Summit 2018](https://www.youtube.com/watch?v=0IoUZdDi5Is)

## Templates

*   [Base (⭐719)](https://github.com/substrate-developer-hub/substrate-node-template) - Minimal FRAME-based
    node, derived from [upstream (⭐7.7k)](https://github.com/paritytech/substrate/tree/master/bin/node-template).
*   [Frontier (⭐390)](https://github.com/paritytech/frontier/tree/master/template) - Fronter enabled EVM and Ethereum RPC compatible Substrate node, ready for hacking.
*   [Front-End (⭐251)](https://github.com/substrate-developer-hub/substrate-front-end-template) - Polkadot-JS API and [React](https://reactjs.org/) app to build front-ends for Substrate-based chains.
*   [Parachain (⭐163)](https://github.com/substrate-developer-hub/substrate-parachain-template) - Cumulus enabled Substrate node, derived from [upstream (⭐535)](https://github.com/paritytech/cumulus/tree/master/parachain-template).
*   [`substrate-stencil`](https://github.com/kaichaosun/substrate-stencil) - A template for a Substrate node that includes staking and governance capabilities.
*   [polkadot-js-api-ts-template (⭐13)](https://github.com/kianenigma/polkadot-js-api-ts-template) - A template project to kickstart hacking on top of `@polkadot/api`

## FRAME Pallets

*   [Chainlink Feed Pallet (⭐132)](https://github.com/smartcontractkit/chainlink-polkadot) - Chainlink feed token interface.
*   [Official in Substrate (⭐7.7k)](https://github.com/paritytech/substrate/tree/master/frame) - Large collection, Parity maintained.
*   [Open Runtime Module Library (ORML) (⭐362)](https://github.com/open-web3-stack/open-runtime-module-library) - Community maintained collection of Substrate runtime modules.
*   [Sunshine Bounty (⭐44)](https://github.com/sunshine-protocol/sunshine-bounty/tree/master/pallets) - Distributed autonomous organization (DAO) for administering a bounty program.
*   [Sunshine Identity (⭐31)](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/identity/pallet) - Keybase-inspired identity management.
*   [Sunshine Faucet (⭐31)](https://github.com/sunshine-protocol/sunshine-keybase/tree/master/faucet/pallet) - Dispense resources for a development chain.
*   [RMRK Pallets (⭐65)](https://github.com/rmrk-team/rmrk-substrate) - Nested, conditional & Multi-resourced NFTs.

## Framework Extensions

*   [Bridges (⭐222)](https://github.com/paritytech/parity-bridges-common) - A collection of tools for cross-chain communication.
*   [Cumulus (⭐535)](https://github.com/paritytech/cumulus) - A set of tools for writing Substrate-based Polkadot parachains.
*   [FRAME](https://docs.substrate.io/v3/runtime/frame/) - A system for building Substrate runtimes.
*   [Frontier (⭐390)](https://github.com/paritytech/frontier) - End-to-end Ethereum emulation for Substrate chains.
*   [ink! (⭐1.1k)](https://github.com/paritytech/ink) - Rust smart contract language for Substrate chains.
*   [IntegriTEE](https://book.integritee.network/) - Trusted off-chain execution framework that uses [Intel SGX](https://en.wikipedia.org/wiki/Software_Guard_Extensions) trusted execution environments.
*   [Polkadot-JS](https://polkadot.js.org/) - Rich JavaScript API framework for front-end development.

## Client Libraries

*   [.Net API (⭐31)](https://github.com/usetech-llc/polkadot_api_dotnet) - Maintained by [Usetech](https://usetech.com/blockchain/).
*   [.NET Substrate API (⭐17)](https://github.com/ajuna-network/Ajuna.NetApi) - Used in [nuget](https://www.nuget.org/packages/Ajuna.NetApi/), and [Unity Example (⭐5)](https://github.com/ajuna-network/SubstrateNET/tree/master/SubstrateNET.UnityDemo); Maintained by [Ajuna Network](https://ajuna.io/).
*   [.NET Toolchain/SDK (⭐11)](https://github.com/ajuna-network/Ajuna.SDK) - Toolchain for Substrate .NET. Pre-generated [SubstrateNET (⭐5)](https://github.com/ajuna-network/SubstrateNET); Maintained by Ajuna Network.
*   [`go-substrate-gen`](https://github.com/Aphoh/go-substrate-gen) - Generate Go (de)serialization/client code from Substrate metadata.
*   [`sube`](https://github.com/virto-network/sube) - Lightweight Rust client library and CLI with support for type information.
*   [`subxt`](https://github.com/paritytech/substrate-subxt) - Official Rust client.
*   [C++ API (⭐17)](https://github.com/usetech-llc/polkadot_api_cpp) - Maintained by Usetech.
*   [Go RPC Client (⭐159)](https://github.com/centrifuge/go-substrate-rpc-client/) - Maintained by [Centrifuge](https://centrifuge.io/).
*   [Kotlin Client (⭐15)](https://github.com/NodleCode/substrate-client-kotlin) - Maintained by [Nodle.io](https://github.com/NodleCode).
*   [Polkadot-JS API (⭐1k)](https://github.com/polkadot-js/api/) - Semi-official JavaScript library for Substrate-based chains.
*   [Python Interface (⭐178)](https://github.com/polkascan/py-substrate-interface) - Maintained by [Polkascan Foundation](https://polkascan.org/).
*   [Rust API Client (⭐193)](https://github.com/scs/substrate-api-client) - Rust client maintained by [Supercomputing Systems AG](https://www.scs.ch/).
*   [Subscan Go Utilities (⭐156)](https://github.com/itering/subscan-essentials) - SS58 and more, developed by Subscan.
*   [Sub-Api (⭐0)](https://github.com/kodadot/packages/tree/main/sub-api) - Friendly wrapper for Polkadot.js API maintained by KodaDot.

## Mobile

*   [Fearless Utils Android (⭐16)](https://github.com/soramitsu/fearless-utils-Android) - Android Substrate tools.
*   [Fearless Utils iOS (⭐8)](https://github.com/soramitsu/fearless-utils-iOS) - iOS Substrate tools.
*   [Nova Substrate SDK Android (⭐3)](https://github.com/nova-wallet/substrate-sdk-android) - Substrate SDK and tools for Android.
*   [Nova Substrate SDK iOS (⭐7)](https://github.com/nova-wallet/substrate-sdk-ios) - Substrate SDK and tools for iOS.
*   [Polkadot-Dart (⭐22)](https://github.com/Pocket4D/Polkadot-Dart) - Dart Substrate API.
*   [PolkaWallet SDK (⭐16)](https://github.com/polkawallet-io/sdk) - Flutter SDK for Substrate-based App.
*   [React-Native-Substrate-Sign (⭐21)](https://github.com/paritytech/react-native-substrate-sign) - Rust library for React Native.

## Tools

*   [`offline-election`](https://github.com/paritytech/substrate-debug-kit/tree/master/offline-election) - Tool to predict nominated proof-of-stake elections.
*   [`offchain::ipfs`](https://rs-ipfs.github.io/offchain-ipfs-manual/) - Substrate infused with [IPFS](https://ipfs.io/).
*   [`polkadot-js-bundle`](https://github.com/shawntabrizi/polkadot-js-bundle) - A standalone JS bundle that contains Polkadot{JS} libraries.
*   [`polkadot-launch`](https://github.com/shawntabrizi/polkadot-launch) - Simple CLI tool to launch a local Polkadot test network.
*   [`polkadot-runtime-prom-exporter`](https://github.com/paritytech/polkadot-runtime-prom-exporter/) - A [Prometheus](https://prometheus.io/) exporter for Polkadot runtime metrics (modifiable for Substrate use).
*   [`polkadot-scripts`](https://github.com/paritytech/polkadot-scripts) - A collection of scripts Parity uses to diagnose Polkadot/Kusama.
*   [`polkadot-starship`](https://github.com/koute/polkadot-starship) - Another tool to launch a local Polkadot test network, with emphasis on the ability to run big testnets.
*   [`srtool-actions`](https://github.com/chevdor/srtool-actions) - GitHub actions to easily use the `srtool` Docker image to build your own runtime.
*   [`srtool-cli`](https://github.com/chevdor/srtool-cli) - CLI frontend for the `srtool` Docker image.
*   [`srtool`](https://github.com/paritytech/srtool) - Docker image to deterministically build a runtime.
*   [`subsee`](https://github.com/ascjones/subsee) - CLI to inspect metadata of a Substrate node as JSON.
*   [`subalfred`](https://github.com/hack-ink/subalfred) - An all-in-one Substrate development toolbox.
*   [`substrate-balance-calculator`](https://github.com/shawntabrizi/substrate-balance-calculator) - Breakdown the balances of your Substrate account.
*   [`substrate-balance-graph`](https://github.com/shawntabrizi/substrate-balance-graph) - Create a graph of the token balance over time of a Substrate address.
*   [`substrate-graph-benchmarks`](https://github.com/shawntabrizi/substrate-graph-benchmarks) - Graph the benchmark output of FRAME pallets.
*   [`substrate-js-utils`](https://github.com/shawntabrizi/substrate-js-utilities) - A set of useful JavaScript utilities for Substrate that uses the Polkadot{JS} API; Also [deployed as a website](https://www.shawntabrizi.com/substrate-js-utilities/).
*   [`substrate-society`](https://github.com/shawntabrizi/substrate-society) - A basic front-end for the FRAME Society pallet.
*   [`substrate-toml-lint`](https://github.com/shawntabrizi/substrate-toml-lint) - A toml parser and checker to avoid common errors in Substrate projects.
*   [`subwasm`](https://github.com/chevdor/subwasm) - CLI to inspect a runtime WASM blob offline. It shows information, metadata and can compare runtimes. It can also help you fetch a runtime directly from a node.
*   [`sup`](https://github.com/clearloop/sup) - Command line tool for generating or upgrading a Substrate node.
*   [`scale-value`](https://github.com/paritytech/scale-value) - Analogous to `serde_json` but for SCALE; Library to decode arbitrary SCALE encoded bytes into a dynamic `Value` given type info from `scale-info`.
*   [`scale-decode`](https://github.com/paritytech/scale-decode) - Decode SCALE bytes into arbitrary custom types by implementing a visitor trait.
*   [Aleph.im](https://aleph.im) - Scalable, decentralized database, file storage, and computation services for Substrate chains and more.
*   [Archive (⭐186)](https://github.com/paritytech/substrate-archive) - Indexing engine for Substrate chains.
*   [Dev Hub Utils (⭐4)](https://github.com/danforbes/substrate-devhub-utils) - *Unofficial* utilities for working with official Substrate Developer Hub resources.
*   [Europa (⭐70)](https://github.com/patractlabs/europa) - A sandbox for the Substrate runtime execution environment.
*   [Fork Off Substrate (⭐101)](https://github.com/maxsam4/fork-off-substrate) - Script to help bootstrap a new chain with the state of a running chain.
*   [fudge (⭐19)](https://github.com/centrifuge/fudge) - Core lib for accessing and (arbitrarily) manipulating substrate databases, including the building and importing of local blocks.
*   [Gantree Library (⭐11)](https://github.com/gantree-io/gantree-lib-nodejs) - A suite of technologies for managing Substrate-powered parachain networks via rapid spin-up & tear-down.
*   [Halva (⭐34)](https://github.com/halva-suite/halva) - A toolchain for improving the experience of developing on Substrate.
*   [Hydra (⭐45)](https://github.com/Joystream/hydra) - A GraphQL framework for Substrate nodes.
*   [Jupiter (⭐52)](https://github.com/patractlabs/jupiter) - Testnet for smart contracts written for the FRAME Contracts pallet and ink!.
*   [Megaclite (⭐1)](https://github.com/patractlabs/megaclite) - Zero-knowledge tools for the Polkadot ecosystem.
*   [Metadata Portal](https://nova-wallet.github.io/metadata-portal/) - A self-hosted webpage that shows the latest metadata and chain specs for any given network.
*   [Minimark (⭐0)](https://github.com/kodadot/packages) - Implementation of RMRK NFT v1/v2 protocol maintained by KodaDot
*   [Nova Polkadot Utils (⭐9)](https://github.com/nova-wallet/nova-utils) - Contains static info & metadata to support client apps in Polkadot ecosystem to map it to various netowrks.
*   [Parity Signer](https://www.parity.io/signer/) - Upcycle an unused mobile phone into an air-gapped hardware wallet.
*   [Polkadot PANIC (⭐40)](https://github.com/SimplyVC/panic_polkadot) - Monitoring and alerting solution for Polkadot nodes by Simply VC, compatible with many Substrate chains.
*   [Polkadot Tool Index](https://wiki.polkadot.network/docs/build-tools-index) - List of tools available for your development with Polkadot and any Substrate chain including Block Explorers, Wallets, Network Monitoring & Reporting, Clients, Benchmarking, Fuzzing, Forking, SCALE Codec, CLI Tools and much more.
*   [Polkadot-JS Apps UI](https://polkadot.js.org/apps/) - Semi-official block explorer & front-end for Substrate-based chains.
*   [Polkadot-JS Extension (⭐849)](https://github.com/polkadot-js/extension) - Browser extension for interacting with Substrate-based chains.
*   [Polkascan](https://polkascan.io/) - Multi-chain block explorer maintained by Polkascan Foundation.
*   [Proxy Hot Wallet Demo (⭐18)](https://github.com/emostov/proxy-hot-wallet) - A demonstration of a secure, convenient, and flexible hot wallet architecture built on Substrate primitives.
*   [Redspot (⭐64)](https://github.com/patractlabs/redspot) - A [Truffle](https://www.trufflesuite.com/truffle)-like toolkit for smart contracts for the FRAME Contracts pallet and ink!.
*   [Sidecar (⭐188)](https://github.com/paritytech/substrate-api-sidecar) - REST service that runs alongside Substrate nodes.
*   [SS58 Transform](https://polkadot.subscan.io/tools/ss58_transform) - Display key's addressees with all SS58 prefixes.
*   [Staking Rewards Collector (⭐65)](https://github.com/w3f/staking-rewards-collector) - A script to parse and output staking rewards for a given Kusama or Polkadot address and cross-reference them with daily price data.
*   [Subkey](https://docs.substrate.io/reference/command-line-tools/subkey/) - Command line utility for working with cryptographic keys.
*   [SubQuery](https://subquery.network) - A GraphQL indexer and query service that allows users to easily create indexed data sources and host them online for free.
    *   [Nova SubQuery API (⭐7)](https://github.com/nova-wallet/subquery-nova) - A SubQuery API implementation for operation history and staking analytics.
*   [Subscan](https://www.subscan.io/) - Multi-network explorer for Substrate-based chains.
*   [Subsquid](https://subsquid.io) - An indexing framework (SDK + infrastructure) to quickly and easily turn Substrate and EVM on-chain data into APIs and host them.
*   [Substate (⭐5)](https://github.com/arrudagates/substate) - 100% no-std/wasm compatible Substrate storage key generator library for Rust.
*   [Substrate debug-kit (⭐96)](https://github.com/paritytech/substrate-debug-kit) - A collection of tools and libraries for debugging Substrate-based chains.
*   [Substrate Docker Builders (⭐17)](https://github.com/ETeissonniere/substrate-nodeops) - A set of Dockerfiles and GitHub Actions to auto-build and push a Docker image for Substrate-based chains.
*   [Substrate Faucet Bot (⭐3)](https://github.com/starkleytech/substrate-faucet) - Python-based faucet for development purposes.
*   [Substrate Graph (⭐28)](https://github.com/playzero/substrate-graph) - GraphQL indexer for Substrate-based chains.
*   [Typechain-Polkadot (⭐9)](https://github.com/Supercolony-net/typechain-polkadot) - Hepls users to generate typescript types from contract ABIs (ink!) and generate runtime code to interact with contracts and deploy them.
*   [TxWrapper (⭐59)](https://github.com/paritytech/txwrapper) - Helpful library for offline transaction creation.
*   [VSCode Substrate](https://marketplace.visualstudio.com/items?itemName=paritytech.vscode-substrate) - Plugin for Visual Studio Code.
*   [Polkaholic.io](https://polkaholic.io) - Multi-chain block explorer with API and DeFi support across 40+ parachains.

## Products and Services

*   [OnFinality](https://onfinality.io) - Free and paid services to shared Substrate based nodes.

## Alternative Implementations

*   [Gossamer (⭐363)](https://github.com/ChainSafe/gossamer) - A Polkadot client implemented in Go; from [ChainSafe](https://chainsafe.io/).
*   [Kagome](https://kagome.readthedocs.io/en/latest/) - A C++17 implementation of the Polkadot client; from [Soramitsu](http://www.soramitsu.co.jp/).
*   [LimeChain AssemblyScript Runtime (⭐12)](https://github.com/LimeChain/as-substrate-runtime) - An account-based Substrate proof-of-concept runtime written in AssemblyScript; from [LimeChain](https://limechain.tech/).

## SCALE Codec

*   [AssemblyScript (⭐18)](https://github.com/LimeChain/as-scale-codec) - Maintained by LimeChain.
*   [C (⭐4)](https://github.com/MatthewDarnell/cScale) - Maintained by Matthew Darnell.
*   [C++ (⭐0)](https://github.com/soramitsu/scale-codec-cpp) - Maintained by Soramitsu.
*   [Codec Definition](https://docs.substrate.io/v3/advanced/scale-codec/) - Official codec documentation.
*   [Go (⭐51)](https://github.com/itering/scale.go) - Maintained by [Itering](https://www.itering.com/).
*   [Haskell (⭐176)](https://github.com/airalab/hs-web3/tree/master/src/Codec) - Maintained by [Robonomics Network](https://robonomics.network/).
*   [Java (⭐52)](https://github.com/emeraldpay/polkaj/tree/master/polkaj-scale) - Maintained by [Emerald](https://emerald.cash/).
*   [Parity SCALE Codec (⭐185)](https://github.com/paritytech/parity-scale-codec) - Reference implementation written in Rust.
*   [Python (⭐51)](https://github.com/polkascan/py-scale-codec) - Maintained by Polkascan Foundation.
*   [Ruby (⭐17)](https://github.com/itering/scale.rb) - Maintained by Itering.
*   [Scales (⭐7)](https://github.com/virto-network/scales) - Serializing SCALE using type information from a type registry.
*   JavaScript / TypeScript implementations:
    *   [paritytech/parity-scale-codec-ts (⭐21)](https://github.com/paritytech/parity-scale-codec-ts) - Maintained by Parity Technologies.
    *   [polkadot-js/api (⭐1k)](https://github.com/polkadot-js/api/tree/master/packages/types) - Maintained by Polkadot-JS.
    *   [scale-ts (⭐8)](https://github.com/unstoppablejs/unstoppablejs/tree/main/packages/scale-ts#scale-ts) - Maintained by Josep M Sobrepere.
    *   [soramitsu/scale-codec-js-library (⭐1)](https://github.com/soramitsu/scale-codec-js-library) - Maintained by Soramitsu.

