Platforms and protocols
=======================

Index:

[Bitcoin](#bitcoin)  
[Bitcoin Lightning Network](#bitcoin-lightning-network)  
[Bitmessage](#bitmessage)  
[BitShares](#bitshares)  
[Corda](#corda)  
[Counterparty](#counterparty)  
[Ethereum](#ethereum)  
[Eris Industries](#eris-industries)  
[Factom](#factom)  
[IOTA](#iota)  
[IPFS](#ipfs)  
[Lisk](#lisk)  
[MaidSafe](#maidsafe)  
[Namecoin](#namecoin)  
[NXT](#nxt)  
[Omni](#omnimastercoin)  
[Ripple](#ripple)  
[Sia](#sia)  
[Storj](#storj)  


Bitcoin
-------

### How to get started: ###

[Bitcoin Developer Examples](https://bitcoin.org/en/developer-examples) - Find examples of how to build programs using Bitcoin.  

### Where to ask questions: ###

[Bitcoin StackExchange](https://bitcointalk.org/index.php?board=6.0)  
[BitcoinTalk Development & Technical Discussion Forum](https://bitcoin.stackexchange.com/)  
[IRC Channel #bitcoin-dev](https://webchat.freenode.net/?channels=bitcoin-dev)

### Quick reference: ###

[JSON RPC API Calls](https://en.bitcoin.it/wiki/Original_Bitcoin_client/API_Calls_list)  
[Script Opcodes](https://en.bitcoin.it/wiki/Script)  
[Bitcoin Developer Reference](https://bitcoin.org/en/developer-reference)  

### Resources: ###

[Bitcoin Developer Documentation](https://bitcoin.org/en/developer-documentation)  
[Bitcoin Wiki](https://en.bitcoin.it/)  
[Bitcoin SubReddit](https://www.reddit.com/r/bitcoin)  
[Hashmal](https://github.com/kefkius/hashmal) - Open source IDE for Bitcoin transaction scripts (experimental software).  


Bitcoin Lightning Network
-------------------------

A trustless second-layer scalability solution for Bitcoin payments. It works by routing them though a network of micropayment channels, which makes Bitcoin transactions instant, irreversible and more private, with near zero fees.

Lightning network is not an application or a library, it's a protocol specification, like HTTP. The most popular implementation of the protocol is the [lightning network daemon (LND)](https://github.com/lightningnetwork/lnd) written in Go, but there are [other implementations](https://github.com/bcongdon/awesome-lightning-network#implementations) as well. It is being integrated into various Bitcoin wallets.

### How to get started: ###

If you want to set up your own lightning node, [here is a step by step tutorial](http://lightning.community/lnd/faucet/2017/01/19/lightning-network-faucet/) on how to do it on the Bitcoin testnet with btcd, lnd, and the testnet faucet. [Here are some other tutorials](https://github.com/bcongdon/awesome-lightning-network#tutorials), including the use of lnd's RPC API in your applications.

### Where to ask questions: ###

[Lightning community slack channel](https://lightningcommunity.slack.com/join/shared_invite/enQtMjk0OTYxNzI4NzExLTFhZDA5YTYxZDU2YWQyOTQzN2ZkMzk3ZGUwNGM0NjE2NzQyNjAyZTkwOTFkZjJmMmMyNzlmNmE5YTRmMGFhM2Q)  

### Quick reference: ###

[CLI command / RPC API reference](http://api.lightning.community)  

### Resources: ###

[Awesome Lightning Network](https://github.com/bcongdon/awesome-lightning-network) - links to applications, libraries, specifications, tutorials and other resources  
[LND Github repository](https://github.com/lightningnetwork/lnd)  
[Hompeage](http://lightning.network) - contains video presentations, the whitepaper and other documents  
[Lightning Labs Twitter channel](https://twitter.com/lightning)  
[Lightning Community blog](http://lightning.community/)  
[Lightning Labs blog](https://blog.lightning.engineering/)  

### Online tools: ###

[Bitcoin testnet faucet lightning network](https://faucet.lightning.community/)  
[Testnet lightning network channel explorer](https://explorer.acinq.co/#/)  


Bitmessage
----------

A decentralized, encrypted, peer-to-peer, trustless communications protocol.

### How to get started: ###

Clone the [PyBitmessage](https://github.com/Bitmessage/PyBitmessage) repository, the [Compiling instructions](https://bitmessage.org/wiki/Compiling_instructions) will tell you how to compile it on your operating system. To use Bitmessage as a platform for your project, you also need to enable the API by [adding a these lines to your keys.dat file](https://bitmessage.org/wiki/API_Reference#Enable_the_API).

### Where to ask questions: ###

[Bitmessage Forum](https://bitmessage.org/forum/index.php?board=1.0)

### Quick reference: ###

[Bitmessage API Reference](https://bitmessage.org/wiki/API_Reference)

### Resources: ###

[Bitmessage Wiki](https://bitmessage.org/wiki/Main_Page)  
[Frequently asked questions](https://bitmessage.org/wiki/FAQ)  
[Bitmessage Help](https://bitmessage.org/wiki/PyBitmessage_Help)  
[GitHub repository](https://github.com/Bitmessage/PyBitmessage)  
[Bitmessage protocol whitepaper](https://bitmessage.org/bitmessage.pdf)  
[Bitmessage SubReddit](https://www.reddit.com/r/bitmessage/)  


BitShares
---------

A peer to peer polymorphic digital asset exchange.

### How to get started: ###

[Getting started with BitShares](https://bitshares.org/get-started)  

### Where to ask questions: ###

[BitShares forum](https://bitsharestalk.org/)  
[Chat - IRC channels](http://wiki.bitshares.org/index.php/IRC)  

### Quick reference: ###

[BitShares API](http://wiki.bitshares.org/index.php/BitShares/API)  

### Resources: ###

[BitShares Wiki](http://wiki.bitshares.org/index.php/Main_Page)  
[BitShares repository on GitHub](https://github.com/BitShares/bitshares)  
[Whitepaper](http://docs.bitshares.org/)  
[BitShares SubReddit](https://www.reddit.com/r/BitShares/)  
[Facebook page](https://www.facebook.com/officialbitshares)  
[Twitter channel](https://twitter.com/_bitshares)  
[BitShares Newsletter](https://bitshares.org/newsletter/)  
[BitShares TV](http://bitshares.tv/) - BitShares news and information video channel  
[AboutBTS](http://www.aboutbts.com/) - latest news on BitShares  


Corda
-----

An open-source blockchain project, designed for business, that allows you to build interoperable blockchain networks that transact in strict privacy.

### How to get started: ###

Either download the [DemoBench](https://www.corda.net/downloads/) or follow the [Quickstart Guide](https://docs.corda.net/quickstart-index.html) to quickly spin up a network of nodes.

Then familiarise yourself with the [Key Concepts](https://docs.corda.net/key-concepts.html) and write your own CorDapp by following our [Hello, World! tutorial](https://docs.corda.net/hello-world-introduction.html).

### Where to ask questions: ###

[cordaledger Slack team](http://slack.corda.net/)  
[Stack Overflow](https://stackoverflow.com/questions/tagged/corda)

### Quick reference: ###

[Corda Key Concepts](https://docs.corda.net/key-concepts.html)  
[Corda API](https://docs.corda.net/corda-api.html)

### Resources: ###

[Official documentation](https://docs.corda.net/)  
[Sample applications](https://www.corda.net/samples/)  
[GitHub organisation](https://github.com/corda/)  
[Project homepage](https://www.corda.net/)


Counterparty
------------

A platform for free and open financial tools on the Bitcoin network.

### How to get started: ###

First, set up a local counterparty node. Luckily, there is an automated installer that simplifies the process. Follow this [guide to set up a federated node](http://counterparty.io/docs/federated_node/). For experimenting and development, choose Testnet, not Mainnet during the installation. Testnet has two advantages for this purpose. 1 - you don't have to download and parse the huge Bitcoin blockchain. 2 - you can get testnet bitcoins for free, and then convert them to XCP, so you can try all kinds of functions without paying with real money.

Once your federated node has downloaded and parsed the blockchain, you can use counterparty, but you need some of the XCP currency to actually do something. Also, transactions cost a small amount of BTC for miner fees. To get testnet BTC for free, visit one of the Testnet faucets, like [this one](http://faucet.xeno-genesis.com/). Enter a testnet address form your counterparty wallet, and it will send you some Testnet BTC. Next, go to your wallet, and use the "Burn for XCP" function on part of your BTC. They will be converted to the XCP currency.

### Where to ask questions: ###

[Official Counterparty Forums](https://counterpartytalk.org/)

### Quick reference: ###

[Counterparty API](http://counterparty.io/docs/api/)  
[Counterblock API](http://counterparty.io/docs/counterblock_api/)  

### Resources: ###

[Official documentation](http://counterparty.io/docs/)  
[Counterparty Support Central](http://support.counterparty.io/support/home)  
[GitHub repositories](https://github.com/CounterpartyXCP)  
[Counterparty homepage](http://counterparty.io/)  
[Counterparty SubReddit](https://www.reddit.com/r/counterparty_xcp/)  
[Transifex translation project](https://www.transifex.com/projects/p/counterwallet/)  


Ethereum
--------

A decentralized Web 3.0 publishing platform featuring stateful user-created digital contracts and a Turing-complete contract programming language.

### How to get started: ###

There is now a user friendly tutorial on the [official Ethereum website](https://www.ethereum.org/). It will guide you through the basics, from installing the software to run a node, to building smart contracts in Solidity and deploying them to the blockchain.

For more information, see the [Ethereum Homestead Documentation](http://www.ethdocs.org/en/latest/)  

### Where to ask questions: ###

[Official Forum](https://forum.ethereum.org/)  
[StackExchange](https://ethereum.stackexchange.com/)  
[Q&A on StackOverflow](http://stackoverflow.com/search?tab=newest&q=ethereum)  
[IRC and Skype channels](https://forum.ethereum.org/discussion/1495/chat-with-the-ethereum-community-on-skype-and-irc)  
[Gitter chat rooms](https://gitter.im/orgs/ethereum/rooms)  

### Quick reference: ###

[JavaScript API](https://github.com/ethereum/wiki/wiki/JavaScript-API)  
[JSON RPC](https://github.com/ethereum/wiki/wiki/JSON-RPC)  

### Resources: ###

[Main site](https://www.ethereum.org)  
[Official Blog](http://blog.ethereum.org/)  
[Homestead Documentation](http://www.ethdocs.org/en/latest/) - up to date documentation  
[Solidity Language Documentation](https://solidity.readthedocs.org/en/latest/) - docs for solidity, the most popular Ethereum programming language  
[Frontier Guide](http://ethereum.gitbooks.io/frontier-guide/content/) - docs from the previous ethereum phase  
[Ethereum Wiki](https://github.com/ethereum/wiki/wiki)  
[Developer-focused site](https://ethdev.com/)  
[State of the DApps](http://dapps.ethercasts.com/) - a list of known Ethereum DApps under development  

### Social media: ###

[Ethereum SubReddit](https://www.reddit.com/r/ethereum/)  
[YouTube channel](http://www.youtube.com/ethereumproject)  
[Facebook page](https://www.facebook.com/ethereumproject)  
[Google Plus](http://google.com/+EthereumOrgOfficial)  
[Meetups](http://ethereum.meetup.com/)  

### Frameworks and libraries: ###

[Truffle](http://truffleframework.com/) - A development framework for Ethereum ([source code](https://github.com/trufflesuite/truffle))  
[Embark](https://iurimatias.github.io/embark-framework/) - another framework ([source code](https://github.com/iurimatias/embark-framework))  
[Dapple](https://github.com/nexusdev/dapple) - solidity development tool set  
[Spore](https://github.com/mhhf/spore) - A package manager for DApps based on IPFS  

### Smart contract development tools: ###
[Remix](http://remix.ethereum.org) - web-based solidity IDE, with integrated JS VM for easy debugging  
[TestRPC](https://www.npmjs.com/package/ethereumjs-testrpc) - a mock RPC that simulates the blockchain for local development and testing  
[MetaMask](https://metamask.io/) - Chrome extension that lets you connect Remix to real ethereum testnet, or a local TestRPC instance. It can also be used for debugging DAPP UIs built with Web3.  
[Blockchain explorer for the Ropsten testnet](https://ropsten.etherscan.io/) on Etherscan  
[Ropsten testnet faucet](https://faucet.metamask.io/) by MetaMask  

### Other online tools: ###

[Network Status](https://ethstats.net/) - a rich, real-time visualization of Ethereum network statistics  
[EtherScan](https://etherscan.io/) - blockchain explorer  
[EtherChain](https://etherchain.org/) - another blockchain expolerer  
[Browser-solidity](https://chriseth.github.io/browser-solidity/) - Solidity realtime compiler and runtime ([source code](https://github.com/chriseth/browser-solidity))  
[EtherParty](https://etherparty.com/) - an online platform simplifying DApp development for non-technical people with no programming skills. It will contain an easy to use drag-and-drop visual editor and a set of pre-built contracts to pick and modify (coming soon, currently in Beta).  

Eris Industries
---------------

A company that released a set of ethereum-compatible open source tools that allow people to launch custom blockchains with more direct control over mining and privileges.

### How to get started: ###

See [Eris quick-start guide](https://www.reddit.com/r/erisindustries/comments/31qoxr/new_readers_an_eris_quickstart_guide/) for a quick introduction. The Eris tools can be easily installed through [Docker](https://www.docker.com/) using `docker pull eris/erisdb` and `docker pull eris/decerver`.

You can then launch your own blockchain. The [eris:db tutorial page](https://erisdb.erisindustries.com/tutorials/) and this blog post called [How to Roll Your Own (Thelonious) Chain](https://eng.erisindustries.com/tutorials/2015/04/25/make-thelonious-chain/) explain how this is done. There is also this [decerver tutorial](https://erisserver.erisindustries.com/tutorials/) that shows how to run DApps on the new blockchain.

The virtual machine is fully compatible with Ethereum, so you can write smart contracts in Solidity or one of the other supported programming languages. See the [Ethereum](#ethereum) section for smart contract programming tutorials.

### Where to ask questions: ###

[Official support on Freshdesk](https://eris.freshdesk.com/support/home)    
[Official support email address](mailto:support@erisindustries.com)  
[IRC Channel #erisindustries](https://webchat.freenode.net/?channels=erisindustries) on Freenode  

### Quick reference: ###

[Atë API Reference](https://erisserver.erisindustries.com/tutorials/) - Atë is the scripting component of decerver.  

### Resources: ###

[Homepage](https://erisindustries.com/)  
[ErisIndustries SubReddit](https://www.reddit.com/r/erisindustries)  
[GitHub repositories](https://github.com/eris-ltd)  
[YouTube channel](https://www.youtube.com/c/erisindustries-ltd)  
[Facebook page](https://www.facebook.com/erisindustries)  
[Twitter channel](https://twitter.com/eris_ltd)  
[Meetups](http://www.meetup.com/erisltd/)  

Factom
------

A General Purpose Data Layer for the Blockchain.

### How to get started: ###

The [Binaries Install Guide](https://www.factom.com/howto/binaries-install-guide/) shows how to easily install Factom on Windows, Mac and Linux. Alternatively, you can install it using [go get](https://github.com/FactomProject/FactomDocs/blob/master/communityTesterDirections.md). There are also [other guides](https://www.factom.com/howto/), covering topics like using Factoids and Entry credits, the GUI wallet, and examples of commands you can execute with factom-cli.

Entry credits are sold at the [store](https://www.factom.com/entry-credits/). It costs only 2 USD to get 400 entry credits. For 10 credits, you can create your own chain. Another way is to buy Factoids on an exchange, and [convert them to entry credits](https://www.factom.com/howto/convert-factoids-to-entry-credits/).

### Where to ask questions: ###

There is no official forum yet (at the time I am writing this). [Factom SubReddit](https://www.reddit.com/r/factom/) is where people ask their questions (and they are getting answered). Check the [Frequently Asked Questions](http://factom.org/faq) section first. You can also use the [contact form](http://factom.org/contact) to contact the Factom team directly.  

### Quick reference: ###

[Download Factom API reference (PDF)](https://github.com/FactomProject/FactomDocs/raw/master/FactomAPI.pdf)  

### Resources: ###

[Homepage](http://factom.org/)  
[Offical Blog](http://blog.factom.org)  
[GitHub repositories](https://github.com/factomproject)  
[Download the whitepaper (PDF)](https://github.com/FactomProject/FactomDocs/raw/master/Factom_Whitepaper.pdf)  
[Blockchain Explorer](http://explorer.factom.org/)  
[Factom status](http://factomstatus.com/) - network status and announcements. Check this page if you get errors.

### Social media: ###

[Factom SubReddit](https://www.reddit.com/r/factom/)  
[Twitter channel](https://twitter.com/factomproject)  
[Facebook page](https://facebook.com/factomproject)  
[Google Plus](https://plus.google.com/u/0/108454739564499735232)  
[YouTube channel](https://www.youtube.com/channel/UCZlpFmzDKrSmTObhSPuhdSw)  
[Vimeo](https://vimeo.com/user37461034)  

IOTA
----

A distributed ledger designed for the Internet of Things, using Tangle instead of Blockchain. There are no blocks, new transactions reference and validate the previous ones. This offers scalable microtransactions with zero fees and no need for miners.

### How to get started: ###
There is an easy to use GUI wallet with precompiled binaries for [Windows](https://iota.readme.io/docs/windows), [MAC OS X](https://iota.readme.io/docs/mac-os-x) and [Linux](https://iota.readme.io/docs/linux). It will guide you through the process of creating a seed/password, etc.

If you want to use IOTA for an actual IoT device, you should get the IOTA Reference Implementation (IRI) instead of the GUI wallet. Either use a precompiled IRI [release](https://github.com/iotaledger/iri/releases), or compile the [source code](https://github.com/iotaledger/iri) yourself. Next step is to get a "neighbor", another node that will pair with you. The easiest way is to go to the `#nodesharing` channel IOTA's [Slack](https://slack.iota.org/) and ask there. You should also read the [documentation](https://iota.readme.io/docs) to see how IOTA works and what you can do with it.

You can get tokens form [/r/IOTAFaucet](https://www.reddit.com/r/IOTAFaucet/), a faucet implemented as a Reddit bot.

[Learn.IOTA](https://learn.iota.org/) has a section for [tutorials](https://learn.iota.org/tutorials) for various programming languages and use cases, but it is very new and as of September 2017, there is not much content there, the categories are mostly empty, but since anyone form the community can submit new tutorials, it may change soon.

### Where to ask questions: ###
[Official Forum](https://forum.iota.org/)  
[Slack](https://slack.iota.org/)  

### Quick reference: ###
[API Reference](https://iota.readme.io/docs/getnodeinfo)  

### Resources: ###
[Reddit](https://www.reddit.com/r/Iota/) - active discussion, lots of links  
[YouTube](https://www.youtube.com/channel/UC8xt_puwPKpLwP_UTAa7YIQ) - almost empty  
[Documentation](https://iota.readme.io/docs)  
[Whitepaper](http://iotatoken.com/IOTA_Whitepaper.pdf)  
[GitHub](https://github.com/iotaledger)  
[Blog](https://learn.iota.org/blog)  

### Online tools: ###
[IOTA Converters](https://laurencetennant.com/iota-tools/) - converts normal units to trits/trytes, and dollars to iota according to the exchange rate.  
[IOTA Tools](https://iota.felixseele.de/) - includes address checksum calculator and transaction decoder.  
[iota.tips](http://www.iota.tips/) - tangle explorer  
[iotasear.ch](https://iotasear.ch/) - tangle explorer  
[thetangle.org](https://thetangle.org/) - tangle explorer  

IPFS
----

A P2P distributed file system.

### How to get started: ###

[Installation guide](http://ipfs.io/docs/install/)  
[Getting started](http://ipfs.io/docs/getting-started/)  

### Where to ask questions: ###

[Google Groups](https://groups.google.com/forum/#!forum/ipfs-users)  
[IRC Channel #ipfs](https://webchat.freenode.net/?channels=ipfs)

### Quick reference: ###

[Command reference](http://ipfs.io/docs/commands/)  
[API reference](http://ipfs.io/docs/api/)  

### Resources: ###

[Homepage](http://ipfs.io/)  
[Main GitHub repository](https://github.com/ipfs/ipfs) - links to other repositories  
[Awesome IPFS](https://github.com/ipfs/awesome-ipfs) - useful resources for using IPFS and building things on top of it  
[Official blog](https://ipfs.io/blog/)  
[Whitepaper download](https://github.com/ipfs/ipfs/blob/master/papers/ipfs-cap2pfs/ipfs-p2p-file-system.pdf?raw=true)  
[YouTube channel](https://www.youtube.com/channel/UCdebzB67qU_VBRrae9Vjxww)  
[Twitter channel](https://twitter.com/ipfsbot)

Lisk
----

### How to get started: ###

There is a wallet called Lisk Nano, available precompiled for [Windows, MAC OS X and Linux](https://lisk.io/download). This is useful if you only intend to use Lisk as a currency.

If you want to build smart contacts on top of it, you need Lisk Core. It can be [compiled from source](https://docs.lisk.io/docs/core-pre-installation-source), there is a [precompiled binary for Linux](https://docs.lisk.io/docs/core-pre-installation-binary). A [docker image](https://docs.lisk.io/docs/core-pre-installation-docker) is available but will only run on distributions that support Docker Community Edition (CE). Installation instructions for mainnet and testnet using all 3 methods are [here](https://docs.lisk.io/docs/core-installation).

When you have Lisk Core installed, learn how to use its [API](https://docs.lisk.io/docs/lisk-api). API calls can be issued using the command line interface tool [Lisky](https://www.npmjs.com/package/lisky).

To write Lisk applications using JavaScript, get [Lisk-JS](https://liskhq.github.io/lisk-js/index.html), a JavaScript library that can run on the back end using Node.js, or in the browser as a Browserify module, or a standalone script (the link also offers a CDN hosted version).


### Where to ask questions: ###
[Forum](https://forum.lisk.io/)  
[Community chat](https://lisk.chat/home)  
[Developer chat](http://gitter.im/LiskHQ/lisk)  

### Quick reference: ###

[API Reference - command line](https://docs.lisk.io/docs/lisk-api)  
[API Reference - JavaScript](https://liskhq.github.io/lisk-js/example/api.html)  

### Resources: ###
[Website](https://lisk.io/)  
[Blog](https://blog.lisk.io/)  
[GitHub](https://github.com/LiskHQ)  
[Twitter](https://mobile.twitter.com/LiskHQ)  
[Facebook](https://www.facebook.com/Lisk-1118720888180640)  

### Online tools: ###
[Block explorer](https://explorer.lisk.io/)  
[Lisk-JS experiment](https://liskhq.github.io/lisk-js/example/experiment.html) - on line demonstration of using Lisk testnet from JavaScript.

MaidSafe
--------

A platform for building decentralized applications.

### How to get started: ###

Follow the build instructions for your opearting system - [Linux](https://github.com/maidsafe/MaidSafe/wiki/Build-Instructions-for-Linux), [OS X](https://github.com/maidsafe/MaidSafe/wiki/Build-Instructions-for-OS-X) or [Windows](https://github.com/maidsafe/MaidSafe/wiki/Build-Instructions-for-Windows). Then take a look at the [Introduction for app builders](http://maidsafe.net/app-builders) to familiarize yourself with the compenents of the MaidSafe Library stack.

### Where to ask questions: ###

[SAFE Network forum](https://forum.safenetwork.io/)  

### Quick reference: ###

### Resources: ###

[Developer Wiki](https://github.com/maidsafe/MaidSafe/wiki)  
[Project Homepage](http://maidsafe.net/)  
[Official Blog](http://blog.maidsafe.net/)  
[Google Groups](https://groups.google.com/forum/#!forum/maidsafe-development)  
[MaidSafe SubReddit](https://www.reddit.com/r/maidsafe/)  


Namecoin
--------

Blockchain-based decentralized DNS and personal identity registration.

### How to get started: ###

[Install and configure Namecoin](https://wiki.namecoin.info/index.php?title=Install_and_Configure_Namecoin)  

### Where to ask questions: ###

[Official Namecoin Forum](https://forum.namecoin.info/)  

### Quick reference: ###

[ID namespace specification](https://wiki.namecoin.info/index.php?title=Identity) - personal identity registration  
[Domain name system specification](https://wiki.namecoin.info/index.php?title=Domain_Name_Specification) - the .bit domain  

### Resources: ###

[Namecoin Wiki](https://wiki.namecoin.info/)  
[Frequently asked questions](https://wiki.namecoin.info/index.php?title=FAQ)  
[Namecoin Design](https://github.com/namecoin/namecoin/blob/namecoinq/DESIGN-namecoin.md)  
[Old wiki](http://dot-bit.org/Main_Page_old)  
[Namecoin SubReddit](https://www.reddit.com/r/Namecoin/)  


NXT
---

An open source cryptocurrency and payment network.

### How to get started: ###

Follow [this guide](http://nxt.org/get-started/) to set up everything you'll need. Then look at the [developer information](http://nxt.org/developers/) which shows how to build your own applications on the NXT platform.

### Where to ask questions: ###

[NXT Forum](https://nxtforum.org/)  
[IRC Channel](http://nxt.org/irc-channel/)  

### Quick reference: ###

[High-level API reference](http://wiki.nxtcrypto.org/wiki/Nxt_API)

### Resources: ###

[Official website](http://nxt.org/)  
[NXT SubReddit](https://www.reddit.com/r/nxt)  


Omni/Mastercoin
---------------

A protocol for Decentralized Trading on Bitcoin.

### How to get started: ###

### Where to ask questions: ###

### Quick reference: ###

[Omniwallet API](https://github.com/mastercoin-MSC/omniwallet#read-api-http-get)  
[Master Core API documentation](https://github.com/mastercoin-MSC/mastercore/blob/mscore-0.0.8/doc/apidocumentation.md)  

### Resources: ###

[Project homepage](http://www.omnilayer.org/)  
[Official Blog](http://blog.omni.foundation/)  
[GitHub](https://github.com/mastercoin-MSC)  
[Omni SubReddit](https://www.reddit.com/r/omni/)  
[Facebook page](https://www.facebook.com/groups/1501816626750032/)   
[Twitter channel](https://twitter.com/Omni_layer)  


Ripple
------

A payment system, currency exchange and remittance network by Ripple Labs.

### How to get started: ###

### Where to ask questions: ###

[Ripple Forum](https://forum.ripple.com/)  

### Quick reference: ###

[API reference](https://ripple.com/build/ripple-rest/)  

### Resources: ###

[Official website](https://ripple.com/)  
[Knowledge center](https://ripple.com/knowledge-center/)  
[GitHub](https://github.com/ripple)  
[Ripple SubReddit](https://www.reddit.com/r/Ripple/)  

Sia
---

Decentralized cloud storage.

### How to get started: ###
Install the Sia Daemon, which is available precompiled for [Windows, MAC OS X and Linux](http://sia.tech/apps/#daemon). You can also compile if from [source](https://github.com/NebulousLabs/Sia). Follow the [API quickstart guide](https://blog.sia.tech/api-quickstart-guide-f1d160c05235) to learn how to access the API. A complete specification of API calls is in the [API documentation](https://github.com/NebulousLabs/Sia/blob/master/doc/API.md).

To get some tokens to play with - there is currently no free faucet (as of September 2017), but you can exchange as small amount of any other cryptocurrency for SIA using [Shapeshift.io](https://shapeshift.io/). Other option are listed [here](http://sia.tech/get-siacoin/).

### Where to ask questions: ###
[Official forum](https://forum.sia.tech/)  
[Discord](https://discord.gg/sFCT3Ar)  

### Quick reference: ###
[API Reference](https://github.com/NebulousLabs/Sia/blob/master/doc/API.md)  

### Resources: ###
[Reddit](https://www.reddit.com/r/siacoin/)  
[Twitter](https://mobile.twitter.com/SiaTechHQ)  
[Website](http://sia.tech/)  
[Blog](https://blog.sia.tech/)  

### Online tools: ###
[Sia Explorer](http://explore.sia.tech/) - block explorer  

Storj
-----

Secure, private, and encrypted cloud storage, based on blockchain technology and peer-to-peer protocols.

### How to get started: ###

### Where to ask questions: ###

[StorjTalk Forum](https://storjtalk.org/)  
[IRC Channel #storj](http://webchat.freenode.net/?channels=storj)

### Quick reference: ###

### Resources: ###

[Project homepage](http://storj.io/)  
[GitHub](https://github.com/Storj/)  
[Official Blog](http://blog.storj.io/)  
[Whitepaper](http://storj.io/storj.pdf)  
[Storj SubReddit](https://www.reddit.com/r/storj/)  
