# Solidity Development (Ethereum Based)

The [cryptozombies.io](cryptozombies.io) tutorial is pretty fun to learn solidity with, it will give you a better idea of actual use cases for blockchain.

**Remix** - The easiest solidity IDE to start with.
http://remix.ethereum.org

**Solidity Best Practices** collected from all projects.

**Solidity Style Guide**: You don't want to fail fast and break things when coding smart contracts, you might not be able to fix them, so make sure your code is readable from the beginning. Besides, everyone can see your code in the blockchain, avoid public shame and code beautifully.

Remix tutorials (or just experiment)

Learn to run a **geth** node locally

Implement the **crowdsale** example from the Ethereum.org website in Remix
https://www.ethereum.org/crowdsale

Work through the [ethernaut](https://ethernaut.openzeppelin.com/) tutorials to improve the security of your contracts.

Implement an ERC20 token and deploy it to a testnet (ropsten)

Check OpenZeppelin for libraries (and maybe tutorials) [here](https://blog.openzeppelin.com/guides/)

**Truffle** tutorials
  
  * [Tips on Ethereum build environments](https://medium.com/@davekaj/solidity-tips-and-tricks-for-beginners-building-their-first-dapp-on-ethereum-fed32d6a19ac)
  * [More tips on Ethereum build environments](https://medium.com/coinmonks/what-we-learned-building-our-first-dapp-28b01f9fc244)
  * https://www.udemy.com/blockchain-developer/learn/v4/content
  * [Assert, Require, Revert](https://medium.com/@kscarbrough1/writing-solidity-unit-tests-for-testing-assert-require-and-revert-conditions-using-truffle-2e182d91a40f)

Like it or not, every time that it is possible to avoid writing in Solidity, people have done so. JavaScript can be used for front-ends and contract testing. Likewise, any computation that can be moved from the blockchain to the front-end should be moved, to minimize costs.

## EIP
  * [erc725alliance](https://erc725alliance.org/) - ERC-725, Ethereum Identity Standard
  * [thesecuritytokenstandard](https://thesecuritytokenstandard.org/) - Standard for STO, EIP 1400, 1410, 1411


## Security and Specific actions

**VERY IMPORTANT about security** https://etherscan.io/solcbuginfo

**(Security) Transfer Ether to a contract**
  * https://ethereum.stackexchange.com/questions/28759/transfer-to-contract-fails
  * https://solidity.readthedocs.io/en/develop/units-and-global-variables.html?highlight=transfer#address-related
  * https://vomtom.at/solidity-send-vs-transfer/
  * https://medium.com/coinmonks/smart-contracts-how-to-transfer-ether-ba464ec005c6

**Articles about security**
  * https://blog.sigmaprime.io/solidity-security.html
  * https://solidity.readthedocs.io/en/latest/security-considerations.html
  * https://medium.com/loom-network/how-to-secure-your-smart-contracts-6-solidity-vulnerabilities-and-how-to-avoid-them-part-1-c33048d4d17d
  * https://consensys.github.io/smart-contract-best-practices/
  * https://consensys.github.io/smart-contract-best-practices/known_attacks/
  * https://vessenes.com/more-ethereum-attacks-race-to-empty-is-the-real-deal/
  * https://consensys.github.io/smart-contract-best-practices/security_notifications/
  * https://haseebq.com/the-authoritative-guide-to-blockchain-development/
  * https://ethereum.stackexchange.com/questions/28972/who-is-msg-sender-when-calling-a-contract-from-a-contract

## Useful tools for Solidity development
  * [ethereum-developer-tools-list](https://github.com/ConsenSys/ethereum-developer-tools-list)

### Other
  * [Manage metamask](techhq_development/manage_metamask.md)
  * [Manage Ganache UI app](techhq_development/manage_ganache_ui.md)

# Quorum (Solidity Development)
*to be written*


# Hyperledger Fabric Development
## Useful URL
  * https://hyperledger-fabric.readthedocs.io
  * [Hyperledger Composer Modeling Language](https://hyperledger.github.io/composer/v0.16/reference/cto_language)

## Useful tools for development
  * [hyperledger composer](https://hyperledger.github.io/composer/latest/)
  * [hyperledger explorer](https://www.hyperledger.org/projects/explorer)
  * [hyperledger cello](https://www.hyperledger.org/projects/cello)

## Documentation to build a frontend
  * [Transaction Processor Functions](https://hyperledger.github.io/composer/v0.19/reference/js_scripts)
  * [Querying and filtering business network data](https://hyperledger.github.io/composer/latest/business-network/query.html#using-filters)
  * [Where filter](https://loopback.io/doc/en/lb2/Where-filter.html)

# Bitcoin Cash
## Useful Urls
  * https://developer.bitcoin.com/
  * https://github.com/dsmurrell/awesome-bitcoin-cash
  * [bitcoin cash rest api explorer](https://rest.bitcoin.com/#/block/blockDetails)

# NEM
## Useful Urls
  * [Setting up your workstation](https://nemtech.github.io/getting-started/setup-workstation.html)
