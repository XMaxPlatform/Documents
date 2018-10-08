# XMAX Code Weekly


2018/9/25
-----------------------
## Mainchain
* [apirpc]Added Credential Option setting.
* [exception]Log message generation.
## Sidechain
* [test]Develop basic Python library for test scripts.
* [test]Develop transaction creation template.
* [test]Sidechain message creation template.
* [test]Sidechain RPC Call template.
* [script]Collate API JS Library code.
* [V8]Modify virtual machine smart contract runtime process.
## SDK
* [exception]Error tip display support.
* [express]Balance Router implementation.
* [express]Balance Router match format for Ethereum Addresses.
* [RPC]Balance RPC implementation.
* [config|test]Test address configuration and trial run.
* [website]Handles RPC data truncation issues.


2018/9/17
-----------------------
## Mainchain
* [exception]Add more exception handling.
## Sidechain
* [node]Improve the multi node startup logic.
* [consensus]Correct the logical error of bifurcation.
* [script]The contract function of Token is added to verify the completeness of the issuance data, the legality of signature and operation.
## SDK
* [web]Use Strict DI mode to enhance security.
* [wallet-common] Add wallet common module.
* [style]Add and replace font styles.
* [transaction]Access Gas Price,add Gas limit information.
* [transaction]Implement Send transaction logic.
* [transaction]Increase links to historical transactions.
* [config]Increase Ethernet network configuration.
* [account]Add address format validation.


2018/9/10
-----------------------
## Mainchain
* [db]Define the basic structure of the block,prepare for the quick main logic.
* [foundation]Implement automatic reflection logic and related macros so can reduce the difficulty of data definition and the amount of code, and increase the development speed.
* [apirpc]Url handler registration management.
* [exception]Remove old attributes and replace them in Implementation Class.
## Sidechain
* [node]Fixed some crash problems caused by node connection logic when multi node startup.
* [script]The contract supports charging gas fees to prepare for refining gas.
* [transaction]Related basic data structures for token interaction, such as address logic, message sending structure, data cache structure, etc. Prepare for the next step to achieve transaction logic.
## SDK
* [route] add home link.
* [project] Adjust the web site export and export directory.
* [script] Fix the bug of webpage base library in web page reference.
* [script] The base library adds the private key conversion interface.
* [account] According to the calculation of the private key, the address is displayed on the web page。
* [account] Add private key format validation logic and interface.
* [account] Add account information page display.
* [account] Implement async get balance logic.
* [account] Balance information display format adjustment.
* [account] Repair the account drop-down list.
* [config] Project uses test network.


2018/9/3
-----------------------
## Mainchain
* [db]Improve plug-in initialization logic, eliminate abandoned functions, solve the initialization process related problems.
* [db]Add the data structure of the main account table which based on unitedb.
* [db]Define block data structure
## Sidechain
* [node]Multi machine startup node at the same time, initially verify the multi node startup logic of side chain.
* [node]Fix data error caused by data synchronization delay during node startup processing.
* [v8]Limit the maximum number of messages per block.
* [v8]System transactions can settle gas fees.
* [v8]Gas sorting logic.
* [script]After the ERC20 token is transferred to the side chain, the transaction process can be verified in the Ethernet store.
* [script]Modification of ERC20 data structure which causes unit test error.
* [mongodb]Adjust MongoDB to adapt to new Contract ABI main chain.
* [apirpc]Network message request cache processing,
* [apirpc]Add the HTTP handler structure and the corresponding interface.


2018/8/27
-----------------------
* Mainchain：improve table item declaration for unitedb.
* Mainchain：add chain processing module.
* Mainchain：APIRPC plugin network modele.
* Mainchain：improve exception handling.
* Sidechain：independent contract account logic.
* Sidechain：capital tracing mechanism.
* Sidechain：Multi node interconnection.
* Sidechain：improve data packaging.


2018/8/20
-----------------------
* Mainchain：add unitedb.
* Mainchain：unitedb testcase.
* Mainchain：improve RPC plug-in's network function logic.
* Sidechain：split contract account.
* Sidechain：adjust block receipt reflection.
* Sidechain：confirmed block's size calculation and persistence.
* Sidechain：improved token symbol encoding, length is supported to 7 characters.
* Sidechain：simplify interface call.
* Sidechain：data packing mechanism.


2018/8/13
-----------------------
*  Mainchain：fix compiling error without MongoDB lib。
*  Mainchain：optimize plug-in configuration logic for application initialization。
*  Mainchain: database commit logic。
*  Mainchain：data serialization and hash.
*  Mainchain：database operation testcase.
*  Sidechain：improve authority system logic.
*  Sidechain：fix block verification bug.
*  Sidechain：improve MongoDB transaction serialization.
*  Sidechain：modify genesis block structure.
*  Sidechain：fix bugs caused by token precision error.
*  Sidechain：add P2P UPNP.
*  Sidechain：fix V8 dependent environment deployment problem.


2018/8/6
-----------------------
*  Mainchain：data processing logic in memory。
*  Mainchain：add APIRPC plugin。
*  Sidechain：authority system logic。
*  Sidechain：ERC20 transfer interface。
*  Sidechain：ERC20 transferFrom interface。
*  Sidechain：ERC721 balanceOf interface。
*  Sidechain：ERC721 improve Owner finding。
*  Sidechain：ERC721 ownerof interface。
*  Sidechain：implement SafeMath library。


2018/7/30
-----------------------
*  Mainchain：the block verification.
*  Mainchain：implement version merging.
*  Mainchain：auto generating API Documents.
*  Mainchain：P2P network sending/receiving message.
*  Mainchain：P2P UPNP.
*  Mainchain：change int type define.
*  Sidechain：fork switching logic.
*  Sidechain：Configuration Readme.
*  Sidechain：reconstruct plugin manager.
*  Sidechain：change transaction logic.


2018/7/23
-----------------------
*  Mainchain: define message sending and receiving mechanism.
*  Mainchain: add the protocol base library project.
*  Mainchain: configuration description document.
*  Sidechain: The data structure of the authority system.
*  Sidechain: forking logic.
*  Sidechain: support more character types and longer names.
*  Sidechain: type externsion in V8 Virtual Machine
*  Sidechain: ERC20，ERC721 interface: revoke.
*  Sidechain: ERC20 interface: totalsupply，balanceOf.


2018/7/16
-----------------------
*  Mainchain: P2P net framework.
*  Mainchain: database module.
*  Mainchain: implement dynamic loading plugins.
*  Mainchain: plugin dependency analyzer.
*  Sidechain:ERC721 data unit testcase.
*  Sidechain:Issue ERC721 interface.
*  Sidechain: ERC20 & ERC721 Mint interface.
*  Sidechain: Extend ERC20 data.
*  Sidechain: Transaction processing flow.
*  Sidechain: automatic validation logic of an irreversible block.


2018/7/9
-----------------------
*  Mainchain string formatter and logger.
*  First DB structure in mainchain.
*  Configuration resolver in mainchain.
*  Program option manager in mainchain.
*  Message processing when generating blocks in sidechain.
*  Modify windows building evironment of sidechain.
*  ERC20 structure unit testcase of sidechain.
*  Extend ERC721 structure of sidechain.
*  Store executed vm instructions.
*  Sidechain p2p network.


2018/7/2
-----------------------
*  Mainchain Application excuting flow changes.
*  Improve Mainchain base library:exception,any value,any object,short name.
*  Mainchain network testcase.
*  Save and load logic of sidechain.
*  BFT logic of sidechain.
*  Mainchain network testcase.
*  Create sidechain test framework.
*  Add broadcast and synchronization in sidechain nodes.
*  Extend ERC20 Token structure in sidechain. 
*  Change function callback insert from ast parsing stage to bytecode generate stage.
*  Insert a callback function after each instruction.


2018/6/25
-----------------------
*  Switch V8 VM to 6.4.1
*  Add interface to insert intrinsic function,call intrinsic function in every block.
*  Collate the building environment configuration of MongoDB.
*  Add test project of MongoDB ，wrtie testcase.
*  Improve ProtoBuf testcase.
*  Implement any value basetype to save any value.
*  Write any value testcase.
*  Blockbuilder plugin base logic.
*  File API encryption.


2018/6/19
-----------------------
*  Smart contract document for sidechain.
*  Unify naming of plugin system.
*  Proto file build&compile flow.
*  Protobuf testcase.
*  Network plugin for mainchain.
*  Timer structure for mainchain.
*  Timer structure testcase.


2018/6/13
-----------------------
*  Build base module for xmax mainchain:log, basetype, build macro, cmakeconfig.
*  A smart library for Application framework & Plugin.
*  Implement the MongoDB serialization logic of the support-chain and fix some problems.
*  Add configuration and building steps of some necessary libraries to the main chain, including secp256k1, protobuf and boost.
*  embed v8 Virtual Machine: 1、compile js. 2、call js function. 3.js type export.
*  Supplement some smart contract description document on support-chain.
