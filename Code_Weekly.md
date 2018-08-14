# XMAX Code Weekly


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
