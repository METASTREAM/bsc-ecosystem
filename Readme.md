# BSC Developer Ecosystem

A guide to available tools, components, and platforms for developing applications on BSC. 

This list was spurred by the [ConsenSys](https://github.com/ConsenSys/ethereum-developer-tools-list), and we verified most of the parts on BSC. 
We hope both new and experienced blockchain developers can benefit from this list.

## Contributions are welcome!

Feel free to submit a pull request, with anything from small fixes to tools you'd like to add (or remove!). If adding a new tool, please add a **brief description** that you think new developers would understand.

- Projects that do not have a working product will not be added.
- Projects that are deprecated or no longer maintained will be removed.
- Projects that are paid/restricted services without open source code or developer reviews will be further vetted.
## Developer Tools

We separate the support of tools/infra into:

- :heavy_check_mark: seamless support.  
- :white_check_mark: need custom config bsc network.

### Developing Smart Contracts
#### Smart Contract Languages

| Name  | Description  | Support|
|  ---  |---|---|
|  [Solidity](https://solidity.readthedocs.io/en/latest/)|Ethereum smart contracting language|:heavy_check_mark:|
| [Vyper](https://vyper.readthedocs.io/en/latest/) | New experimental pythonic programming language| :heavy_check_mark:|

#### Frameworks

| Name  | Description  | Support |
|  ---  |---|---|
|[Truffle](https://trufflesuite.com/)| Most popular smart contract development, testing, and deployment framework.| :white_check_mark:|
|[Embark](https://github.com/embark-framework/embark)| Framework for DApp development | :white_check_mark: |
|[Waffle](https://getwaffle.io/)| Framework for advanced smart contract development and testing, small, flexible, fast (based on ethers.js)| :white_check_mark: |
|[Dapp](https://dapp.tools/dapp/)| - Framework for DApp development, successor to DApple| :white_check_mark: |
|[OpenZeppelin SDK](https://openzeppelin.com/sdk/)| OpenZeppelin SDK: A suite of tools to help you develop, compile, upgrade, deploy and interact with smart contracts.| :white_check_mark:|
|[0xcert](https://github.com/0xcert/framework/)| JavaScript framework for building decentralized applications|:white_check_mark:|

#### IDEs
| Name  | Description  | Support|
|  ---  |---|---|
|[Remix](https://remix.ethereum.org/)| Web IDE with built in static analysis, test blockchain VM|:heavy_check_mark:|
|[Intellij Solidity Plugin]| Open-source plug-in for [JetBrains IntelliJ Idea IDE](https://jetbrains.com/idea/)|:heavy_check_mark:|

### Other tools
| Name  | Description  | Support|
|  ---  |---|---|
|[Buidler](https://buidler.dev/)| Extensible developer tool that helps smart contract developers increase productivity by reliably bringing together the tools they want.| :white_check_mark: |
|[Azure Blockchain Dev Kit for BSC for VSCode](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain)| VSCode extension that allows for creating smart contracts and deploying them inside of Visual Studio Code|:white_check_mark:|


### Test blockchain networks
| Name  | Description  | Support |
|  ---  |---|---|
|[bscnode](https://docs.binance.org/smart-chain/developer/fullnode.html) | Run an BSC node for development |:heavy_check_mark:|
|[Ganache](https://github.com/trufflesuite/ganache)| App for test BSC blockchain with visual UI and logs, except for some precompile contract, the rest is same|:heavy_check_mark:|
|[Local BSC Network](https://github.com/ConsenSys/local_ethereum_network)| User can simply set up a bsc network using clique consensus|:heavy_check_mark:|

#### Test Ether faucets

| Name  | Description  | Support |
|  ---  |---|---|
|[BSC faucet](https://testnet.binance.org/faucet-smart)| BSC testnet faucet, support BEP20 as well |:heavy_check_mark:|


### Communicating with BSC
#### Frontend BSC APIs
| Name  | Description  | Support |
|  ---  |---|---|
|[Web3.js](https://github.com/ethereum/web3.js/)| Javascript Web3 | :heavy_check_mark: | 
|[Eth.js](https://github.com/ethjs)| Javascript Web3 alternative | :heavy_check_mark: |
|[Ethers.js](https://github.com/ethers-io/ethers.js/)| Javascript Web3 alternative, useful utilities and wallet features | :heavy_check_mark:|
|[light.js](https://github.com/paritytech/js-libs/tree/master/packages/light.js)| A high-level reactive JS library optimized for light clients| :heavy_check_mark:|
|[Web3Wrapper](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper)| Typescript Web3 alternative|:heavy_check_mark:|
|[Ethereumjs](https://github.com/ethereumjs/) | A collection of utility functions for Ethereum like [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util) and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx)|:heavy_check_mark:|
|[flex-contract](https://github.com/merklejerk/flex-contract) and [flex-ether](https://github.com/merklejerk/flex-ether)|  Modern, zero-configuration, high-level libraries for interacting with smart contracts and making transactions.|:heavy_check_mark:|
|[web3x](https://github.com/xf00f/web3x)|  A TypeScript port of web3.js. Benefits includes tiny builds and full type safety, including when interacting with contracts.|:heavy_check_mark:|
|[Nethereum](https://github.com/Nethereum/)| Cross-platform Ethereum development framework | :heavy_check_mark: |
|[Drizzle](https://github.com/truffle-box/drizzle-box)| Redux library to connect a frontend to a blockchain| 10| 
|[Tasit SDK](https://github.com/tasitlabs/tasitsdk)| A JavaScript SDK for making native mobile Ethereum dapps using React Native| :heavy_check_mark:|
|[Subproviders](https://0x.org/docs/tools/subproviders)| Several useful subproviders to use in conjunction with [Web3-provider-engine](https://github.com/MetaMask/web3-provider-engine) (including a LedgerSubprovider for adding Ledger hardware wallet support to your dApp)| :heavy_check_mark: |
|[web3-react](https://github.com/NoahZinsmeister/web3-react)| React framework for building single-page Ethereum dApps | :heavy_check_mark: |
|[ethvtx](https://github.com/ticket721/ethvtx)| ethereum-ready & framework-agnostic redux store configuration. [docs](https://ticket721.github.io/ethvtx/)| :heavy_check_mark:|
|[ChainAbstractionLayer](https://github.com/liquality/chainabstractionlayer)| Communicate with different blockchains (including Ethereum) using a single interface.| :heavy_check_mark:|
|[Delphereum](https://github.com/svanas/delphereum)|a Delphi interface to the Ethereum blockchain that allows for development of native dApps for Windows, macOS, iOS, and Android.|:heavy_check_mark:|

#### Backend BSC APIs
| Name  | Description  | Support|
|  ---  |---|---|
|[Web3.py](https://github.com/ethereum/web3.py)| Python Web3| :heavy_check_mark:|
|[Web3.php](https://github.com/sc0Vu/web3.php) |PHP Web3| :heavy_check_mark: |
|[Ethereum-php](https://github.com/digitaldonkey/ethereum-php)| PHP Web3| :heavy_check_mark: |
|[Web3j](https://github.com/web3j/web3j) | Java Web3| :heavy_check_mark:|
|[Nethereum](https://nethereum.com/)|.Net Web3 | :heavy_check_mark: |
|[Ethereum.rb](https://github.com/EthWorks/ethereum.rb)| Ruby Web3 | :heavy_check_mark:|
|[Web3.hs](https://hackage.haskell.org/package/web3) |Haskell Web3 | :heavy_check_mark: |
|[KEthereum](https://github.com/komputing/KEthereum) | Kotlin Web3 | :heavy_check_mark: |
|[Eventeum](https://github.com/ConsenSys/eventeum)| A bridge between Ethereum smart contract events and backend microservices, written in Java by Kauri| :heavy_check_mark: |
|[Ethereumex](https://github.com/mana-ethereum/ethereumex)| Elixir JSON-RPC client for the Ethereum blockchain | :heavy_check_mark: |
|[Ethereum-jsonrpc-gateway](https://github.com/HydroProtocol/ethereum-jsonrpc-gateway)| A gateway that allows you to run multiple Ethereum nodes for redundancy and load-balancing purposes. Can be ran as an alternative to (or on top of) Infura. Written in Golang.| :heavy_check_mark: | 
|[EthContract](https://github.com/AgileAlpha/eth_contract) | A set of helper methods to help query ETH smart contracts in Elixir|:heavy_check_mark:|
|[Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) |A MESG Service to interact with any Ethereum contract based on its address and ABI.| :heavy_check_mark:| 
|[Ethereum Service](https://github.com/mesg-foundation/service-ethereum)| A MESG Service to interact with events from Ethereum and interact with it.|:heavy_check_mark:|
|[Marmo](https://marmo.io/)| Python, JS, and Java SDK for simplifying interactions with Ethereum. Uses relayers to offload transaction costs to relayers.|:heavy_check_mark:|

#### Bootstrap/out of box tools
| Name  | Description  | Support |
|  ---  |---|---|
|[Truffle boxes](https://trufflesuite.com/boxes)| Packaged components for the Ethereum ecosystem| :white_check_mark: |
|[Private networks deployment scripts](https://github.com/ConsenSys/private-networks-deployment-scripts)| Out-of-the-box deployment scripts for private PoA networks| :heavy_check_mark: |
|[Local Ethereum Network](https://github.com/ConsenSys/local_ethereum_network)| Out-of-the-box deployment scripts for private PoW networks| :heavy_check_mark: |
|[Cheshire](https://github.com/endless-nameless-inc/cheshire) | A local sandbox implementation of the CryptoKitties API and smart contracts, available as a Truffle Box| :heavy_check_mark: |
|[aragonCLI](https://github.com/aragon/aragon-cli) | aragonCLI is used to create and develop Aragon apps and organizations.| :heavy_check_mark: |
|[ArcJS](https://github.com/daostack/arc.js) | Library that facilitates javascript application access to the DAOstack Arc ethereum smart contracts.| :heavy_check_mark: |
|[Blocknative](https://blocknative.com) |Assist.js is an embeddable widget that improves Dapp usability. The tool programmatically identifies and outlines clear actions for end-users to follow when interacting with MetaMask to overcome — and even prevent — common pitfalls and obstacles.|:heavy_check_mark:|

#### Ethereum ABI (Application Binary Interface) tools

| Name  | Description  | Support |
|  ---  |---|---|
|[ABI decoder](https://github.com/ConsenSys/abi-decoder) | library for decoding data params and events from Ethereum transactions| :heavy_check_mark: |
|[ABI-gen](https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen)| Generate Typescript contract wrappers from contract ABI's.|:heavy_check_mark: |
|[Ethereum ABI UI](https://github.com/hiddentao/ethereum-abi-ui) | Auto-generate UI form field definitions and associated validators from an Ethereum contract ABI|:heavy_check_mark: |
|[headlong](https://github.com/esaulpaugh/headlong/) | type-safe Contract ABI and Recursive Length Prefix library in Java| :heavy_check_mark: |
|[Truffle Pig](https://npmjs.com/package/trufflepig) | a development tool that provides a simple HTTP API to find and read from Truffle-generated contract files, for use during local development. Serves fresh contract ABIs over http.|  :heavy_check_mark:|
|[Ethereum Contract Service](https://github.com/mesg-foundation/service-ethereum-contract) | A MESG Service to interact with any Ethereum contract based on its address and ABI.|  :heavy_check_mark: |
|[Nethereum-CodeGenerator](https://github.com/StefH/Nethereum-CodeGenerator) | A web based generator which creates a Nethereum based C# Interface and Service based on Solidity Smart Contracts.|  :heavy_check_mark:| 


### Infrastructure
#### Ethereum Clients
| Name  | Description  | Support|
|  ---  |---|---|
|[Seth](https://github.com/dapphub/dapptools/tree/master/src/seth)| Seth is an Ethereum client tool—like a "MetaMask for the command line"|:white_check_mark: |
|[Ankr](https://www.ankr.com/) | support deploy BSC by one click, and provide instant API access to major blockchain and DeFi protocols.| :heavy_check_mark:|


#### Messaging
| Name  | Description  | Support|
|  ---  |---|---|
|[Whisper](https://github.com/ethereum/wiki/wiki/Whisper)| Communication protocol for DApps to communicate with each other, a native base layer service of the Ethereum web3 stack|:white_check_mark:|
|[DEVp2p Wire Protocol](https://github.com/ethereum/devp2p/blob/master/rlpx.md)| Peer-to-peer communications between nodes running Ethereum/Whisper| :white_check_mark:|
|[Pydevp2p](https://github.com/ethereum/pydevp2p) | Python implementation of the RLPx network layer| :heavy_check_mark:|
|[3Box Threads](https://docs.3box.io/api/messaging)| API to allow developers to implement IPFS persisted, or in memory peer to peer messaging.|:white_check_mark:|

### Testing Tools
| Name  | Description  | Support|
|  ---  |---|---|
|[Solidity code coverage](https://github.com/0xProject/0x-monorepo/tree/development/packages/sol-coverage)| Solidity code coverage tool |  :heavy_check_mark:| 
|[Solidity coverage](https://github.com/sc-forks/solidity-coverage) | Alternative code coverage for Solidity smart-contracts|  :heavy_check_mark:|
|[Solidity function profiler](https://github.com/EricR/sol-function-profiler) | Solidity contract function profiler|  :heavy_check_mark: |
|[Sol-profiler](https://github.com/Aniket-Engg/sol-profiler) | Alternative and updated Solidity smart contract profiler|   :heavy_check_mark: |
|[Espresso](https://github.com/hillstreetlabs/espresso) | Speedy, parallelised, hot-reloading solidity test framework|  :heavy_check_mark:|
|[Eth tester](https://github.com/ethereum/eth-tester) | Tool suite for testing Ethereum applications|  :heavy_check_mark:|
|[Cliquebait](https://github.com/f-o-a-m/cliquebait) | Simplifies integration and accepting testing of smart contract applications with docker instances that closely resembles a real blockchain network|  :heavy_check_mark:|
|[Hevm](https://github.com/dapphub/dapptools/tree/master/src/hevm) | The hevm project is an implementation of the Ethereum virtual machine (EVM) made specifically for unit testing and debugging smart contracts|  :heavy_check_mark: |
|[Ethereum graph debugger](https://github.com/fergarrui/ethereum-graph-debugger) | Solidity graphical debugger |  :heavy_check_mark:|
|[Tenderly CLI](https://github.com/Tenderly/tenderly-cli)|Speed up your development with human readable stack traces|  :heavy_check_mark:|
|[Solhint](https://github.com/protofire/solhint) | Solidity linter that provides security, style guide and best practice rules for smart contract validation|  :heavy_check_mark:|
|[Ethlint](https://github.com/duaraghav8/Ethlint) | Linter to identify and fix style & security issues in Solidity, formerly Solium|  :heavy_check_mark:|
|[Decode](https://github.com/hacker-DOM/decode) | npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand|  :heavy_check_mark:|
|[truffle-assertions](https://github.com/rkalis/truffle-assertions) | An npm package with additional assertions and utilities used in testing Solidity smart contracts with truffle. Most importantly, it adds the ability to assert whether specific events have (not) been emitted.|  :heavy_check_mark: |
|[Psol](https://github.com/Lamarkaz/psol) | Solidity lexical preprocessor with mustache.js-style syntax, macros, conditional compilation and automatic remote dependency inclusion.| :heavy_check_mark:|
|[solpp](https://github.com/merklejerk/solpp) | Solidity preprocessor and flattener with a comprehensive directive and expression language, high precision math, and many useful helper functions.| :heavy_check_mark:|
|[Decode and Publish](https://flightwallet.github.io/decode-eth-tx/) | Decode and publish raw ethereum tx. Similar to https://live.blockcypher.com/btc-testnet/decodetx/| :heavy_check_mark:|
|[Doppelgänger](https://getdoppelganger.io/) | a library for mocking smart contract dependencies during unit testing. | :heavy_check_mark:|
|[rocketh](https://github.com/wighawag/rocketh) | A simple lib to test ethereum smart contract that allow to use whatever web3 lib and test runner you choose.| :heavy_check_mark:|
|[pytest-cobra](https://github.com/cobraframework/pytest-cobra) | PyTest plugin for testing smart contracts for Ethereum blockchain.|  :heavy_check_mark: |


### Security Tools
| Name  | Description  | Support  |
|  ---  |------------- | -----------------------------|
| [MythX](https://mythx.io/) | Security verification platform and tools ecosystem for Ethereum developers |  :heavy_check_mark: |
| [Mythril](https://github.com/ConsenSys/mythril) | Open-source EVM bytecode security analysis tool |  :heavy_check_mark: |
| [Oyente](https://github.com/melonproject/oyente) | Alternative static smart contract security analysis |  :heavy_check_mark: |
| [Securify](https://securify.chainsecurity.com/) | Security scanner for Ethereum smart contracts |  :heavy_check_mark: |
| [SmartCheck](https://tool.smartdec.net/) | Static smart contract security analyzer |  :heavy_check_mark: |
| [Ethersplay](https://github.com/crytic/ethersplay) | EVM disassembler |  :heavy_check_mark: |
| [Evmdis](https://github.com/Arachnid/evmdis) | Alternative EVM disassembler |  :heavy_check_mark: |
| [Hydra](https://github.com/IC3Hydra/Hydra) | Framework for cryptoeconomic contract security, decentralised security bounties |  :heavy_check_mark: |
| [Solgraph](https://github.com/raineorshine/solgraph) | Visualise Solidity control flow for smart contract security analysis |  :heavy_check_mark: |
| [Manticore](https://github.com/trailofbits/manticore) | Symbolic execution tool on Smart Contracts and Binaries |  :heavy_check_mark: |
| [Slither](https://github.com/crytic/slither) | A Solidity static analysis framework |  :heavy_check_mark: |
| [Adelaide](https://github.com/sec-bit/adelaide) | The SECBIT static analysis extension to Solidity compiler |  :heavy_check_mark: |
| [solc-verify](https://github.com/SRI-CSL/solidity/) | A modular verifier for Solidity smart contracts |  :heavy_check_mark: |
| [Solidity security blog](https://github.com/sigp/solidity-security-blog) | Comprehensive list of known attack vectors and common anti-patterns |  :heavy_check_mark: |
| [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens) | A Collection of Vulnerabilities in ERC20 Smart Contracts With Tokens Affected |  :heavy_check_mark: |
| [Free Smart Contract Security Audit](https://callisto.network/smart-contract-audit/) | Free smart contract security audits from Callisto Network |  :heavy_check_mark: |
| [Piet](https://piet.slock.it) | A visual Solidity architecture analyzer |  :heavy_check_mark: |

### Monitoring
### Other Miscellaneous Tools
| Name  | Description  | Support|
|  ---  |------------- | -----------------------------|
| [Neufund - Smart Contract Watch](https://github.com/Neufund/smart-contract-watch) | A tool to monitor a number of smart contracts and transactions | :white_check_mark: |
| [BlockScout](https://github.com/poanetwork/blockscout) | A tool for inspecting and analyzing EVM based blockchains. The only full featured blockchain explorer for Ethereum networks. | :white_check_mark: |
| [Terminal](https://terminal.co/) | A control panel for monitoring dapps. Terminal can be used to monitor your users, dapp, blockchain infrastructure, transactions and more. | :white_check_mark: |
| [Ethereum-watcher](https://github.com/HydroProtocol/ethereum-watcher) | An extensible framework written in Golang for listening to on-chain events and doing something in response. | :white_check_mark: |

### Other Miscellaneous Tools
| Name  | Description  | Support|
|  ---  |------------- | -----------------------------|
| [aragonPM](https://hack.aragon.org/docs/apm-intro.html) | a decentralized package manager powered by aragonOS and Ethereum. aragonPM enables decentralized governance over package upgrades, removing centralized points of failure. |  :heavy_check_mark:  |
| [Truffle boxes](https://www.trufflesuite.com/boxes) | Packaged components for building DApps fast. | :white_check_mark: |
| [Solc](https://solidity.readthedocs.io/en/latest/using-the-compiler.html) | Solidity compiler |  :heavy_check_mark:  |
| [Sol-compiler](https://sol-compiler.com/) | Project-level Solidity compiler |  :heavy_check_mark:  |
| [Solidity cli](https://github.com/pubkey/solidity-cli) | Compile solidity-code faster, easier and more reliable |  :heavy_check_mark:  |
| [Solidity flattener](https://github.com/poanetwork/solidity-flattener) | Combine solidity project to flat file utility. Useful for visualizing imported contracts or for verifying your contract on Etherscan |  :heavy_check_mark:  |
| [Sol-merger](https://github.com/RyuuGan/sol-merger) | Alternative, merges all imports into single file for solidity contracts |  :heavy_check_mark:  |
| [RLP](https://github.com/ethereumjs/rlp) | Recursive Length Prefix Encoding in JavaScript |  :heavy_check_mark:   |
| [Eth crypto](https://github.com/pubkey/eth-crypto) | Cryptographic javascript-functions for Ethereum and tutorials to use them with web3js and solidity |  :heavy_check_mark: |
| [Parity Signer](https://github.com/paritytech/parity-signer) | mobile app allows signing transactions |  :heavy_check_mark: |
| [py-eth](http://py-eth.com) | Collection of Python tools for the Ethereum ecosystem |  :heavy_check_mark: |
| [truffle-flattener](https://github.com/nomiclabs/truffle-flattener) | Concats solidity files developed under Truffle with all of their dependencies |  :heavy_check_mark: |
| [Decode](https://github.com/hacker-DOM/decode) | npm package which parses tx's submitted to a local testrpc node to make them more readable and easier to understand |  :heavy_check_mark: |
| [TypeChain](https://github.com/ethereum-ts/TypeChain) | Typescript bindings for Ethereum smartcontracts |  :heavy_check_mark: |
| [EthSum](https://ethsum.netlify.com) | A Simple Ethereum Address Checksum Tool |  :heavy_check_mark: |
| [PHP based Blockchain indexer](https://github.com/digitaldonkey/ethereum-php-eventlistener) | allows indexing blocks or listening to Events in PHP |   :white_check_mark:   |
| [Purser](https://github.com/JoinColony/purser) | JavaScript universal wallet tool for Ethereum-based wallets. Supports software, hardware, and Metamask -- brings all wallets into a consistent and predictable interface for dApp development. |  :heavy_check_mark:  |
| [Node-Metamask](https://github.com/JoinColony/node-metamask) | Connect to MetaMask from node.js |  :heavy_check_mark:   |
| [Solidity-docgen](https://github.com/OpenZeppelin/solidity-docgen) | Documentation generator for Solidity projects |  :heavy_check_mark:  |
| [Ethereum ETL](https://github.com/blockchain-etl/ethereum-etl) | Export Ethereum blockchain data to CSV or JSON files |  :white_check_mark:  |
| [prettier-plugin-solidity](https://github.com/prettier-solidity/prettier-plugin-solidity) | Prettier plugin for formatting Solidity code |  :heavy_check_mark:  |
| [Unity3dSimpleSample](https://github.com/Nethereum/Unity3dSimpleSample) | Ethereum and Unity integration demo |  :heavy_check_mark:   |
| [Flappy](https://github.com/Nethereum/Nethereum.Flappy) | Ethereum and Unity integration demo/sample |  :heavy_check_mark:   |
| [Wonka](https://github.com/Nethereum/Wonka) | Nethereum business rules engine demo/sample |  :heavy_check_mark:  |
| [Resolver-Engine](https://github.com/Crypto-Punkers/resolver-engine) | A set of tools to standarize Solidity import and artifact resolution in frameworks. |  :heavy_check_mark:  |
| [Ethereum-tx-sender](https://github.com/HydroProtocol/ethereum-tx-sender) | A useful library written in Golang to reliably send a transaction — abstracting away some of the tricky low level details such as gas optimization, nonce calculations, synchronization, and retries. |  :heavy_check_mark:  |


#### Popular Smart Contract Libraries
| Name  | Description  | Support|
|  ---  |------------- | -----------------------------|
| [Zeppelin](https://github.com/OpenZeppelin/openzeppelin-contracts) | Contains tested reusable smart contracts like SafeMath and OpenZeppelin SDK [library](https://github.com/OpenZeppelin/openzeppelin-sdk) for smart contract upgradeability |  :heavy_check_mark:  |
| [cryptofin-solidity](https://github.com/cryptofinlabs/cryptofin-solidity) | A collection of Solidity libraries for building secure and gas-efficient smart contracts on Ethereum. |  :heavy_check_mark: |
| [Modular Libraries](https://github.com/Modular-Network/ethereum-libraries) | A group of packages built for use on blockchains utilising the Ethereum Virtual Machine |  :heavy_check_mark:  |
| [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) | A gas-efficient Solidity date and time library |  :heavy_check_mark:  |
| [Aragon](https://github.com/aragon/aragon) | DAO protocol. Contains [aragonOS smart contract framework](https://github.com/aragon/aragonOS) with focus on upgradeability and governance |  :heavy_check_mark:  |
| [ARC](https://github.com/daostack/arc) | an operating system for DAOs and the base layer of the DAO stack. |  :heavy_check_mark:  |
| [0x](https://github.com/0xProject) | DEX protocol |  :heavy_check_mark:  |
| [Token Libraries with Proofs](https://github.com/sec-bit/tokenlibs-with-proofs) | Contains correctness proofs of token contracts wrt. given specifications and high-level properties |  :heavy_check_mark:  |
| [Provable API](https://github.com/provable-things/ethereum-api) | Provides contracts for using the Provable service, allowing for off-chain actions, data-fetching, and computation |  :heavy_check_mark:  |

#### Prebuilt UI Components

| Name  | Description  | Support|
|  ---  |------------- | -----------------------------|
| [aragonUI](https://ui.aragon.org) | A React library including Dapp components |  :heavy_check_mark:  |
| [components.bounties.network](https://components.bounties.network) | A React library including Dapp components |  :heavy_check_mark:  |
| [ui.decentraland.org](https://github.com/decentraland/ui) | A React library including Dapp components |  :heavy_check_mark:  |
| [dapparatus](https://github.com/austintgriffith/dapparatus) | Reusable React Dapp components |  :heavy_check_mark:  |
| [Metamask ui](https://github.com/MetaMask/metamask-extension/tree/develop/ui/app/components) | Metamask React Components |  :heavy_check_mark:  |
| [DappHybrid](https://github.com/Nethereum/Nethereum.DappHybrid) | A cross-platform hybrid hosting mechanism for web based decentralised applications |  :heavy_check_mark:  |
| [Nethereum.UI.Desktop](https://github.com/Nethereum/Nethereum.UI.Desktop) | Cross-platform desktop wallet sample |  :heavy_check_mark:  |
| [eth-button](https://eth-button.github.io/eth-button/) | Minimalist donation button |  :heavy_check_mark:  |
| [Rimble Design System](https://rimble.consensys.design/) | Adaptable components and design standards for decentralized applications. |  :heavy_check_mark:  |
| [3Box Plugins](https://docs.3box.io/build/plugins) | Drop in react components for social functionality. Including comments, profiles and messaging. |  :heavy_check_mark:  |
| [Atra Blockchain Services](https://console.atra.io) | Atra provides web services to help you build, deploy, and maintain decentralized applications on the Ethereum blockchain. |  :heavy_check_mark:  |

#### Dapp Tools

| Name  | Description  | Support |
|  ---  |------------- | -----------------------------|
|[approve.sh](https://dappcn.mathwallet.xyz/approve.sh/)|manage approval of account| :heavy_check_mark: | 