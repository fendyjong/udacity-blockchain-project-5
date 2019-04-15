# Star Notary - Udacity Blockchain Project 5
DApps for claiming, buy, transfer, exchange star with blockchain Ethereum.

## Specification
### Versions
- Truffle: 5.0.12
- OpenZeppelin: 2.2.0

## Token
- Name: SimpleToken
- Symbol: MGT

Create a `.secret` file which include mnemonic (metamask seed).

## Develop
Run test on the contract

```
$ truffle develop
$ compile
$ migrate --reset
$ test
```

## Run in Rinkeby network
Deploy contract to rinkeby test network
```
$ truffle migrate --reset --network rinkeby
```
