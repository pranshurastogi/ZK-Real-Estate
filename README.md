# Udacity Blockchain Capstone

The capstone project is to build a decentralized real estate marketplace.


## Install

To install, download or clone the repo, then:

    npm install
    cd eth-contracts/
    truffle compile

## Test

To run truffle tests:

    truffle test


## Rinkeby Details

See rinkeby_deployment.txt for Contract address and other information

## Owner account address - 
` 0x6038c699e6bc985605d36819E10B722981a2D5cc `

## Mint details on Etherscan

* [Mint Tokens - Asset ID](https://rinkeby.etherscan.io/address/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5#events)


## Open Sea details 

* [House No- Asset ID 1] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/1)
* [House No- Asset ID 2] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/2)
* [House No- Asset ID 3] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/3)
* [House No- Asset ID 4] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/4)
* [House No- Asset ID 5] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/5)
* [House No- Asset ID 6] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/6)
* [House No- Asset ID 7] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/7)
* [House No- Asset ID 8] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/8)
* [House No- Asset ID 9] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/9)
* [House No- Asset ID 10] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/10)
* [House No- Asset ID 111] (https://rinkeby.opensea.io/assets/0x4c4e0708cb3f55c54bafc7026e77ecfbd5e203b5/111)


Sold House - Asset ID 111, 1, 6,7,8


## Deploying

- Create a .env file (in [eth-contracts](./eth-contracts)) with `MNEMONIC` & [Infura](https://infura.io) `ENDPOINT_KEY`
- `truffle compile`
- `truffle migrate --network rinkeby`

## Tests

```
truffle test
Using network 'development'.


Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.



  Contract: TestERC721Mintable
    match erc721 spec
      ✓ should return total supply
      ✓ should get token balance (91ms)
      ✓ should return token uri
      ✓ should transfer token from one owner to another (285ms)
    have ownership properties
      ✓ should return contract owner
      ✓ should fail minting when address is not contract owner
    have pausable properties
      ✓ can pause and unpause (151ms)
      ✓ should return pause status (40ms)
      ✓ should fail minting when contract is paused (96ms)

  Contract: Test SolnSquareVerifier
    test token minting by providing solution
      ✓ should mint token for correct proof (741ms)
      ✓ should not allow solution reuse (722ms)
      ✓ should not mint token for incorrect proof (1295ms)

  Contract: Test SquareVerifier
    test verification
      ✓ should return true for correct proof (658ms)
      ✓ should return false for incorrect proof (628ms)


  14 passing (13s)



```
## Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
