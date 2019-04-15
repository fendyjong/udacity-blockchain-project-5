# Star Notary - Udacity Blockchain Project 5

## Specification
### Versions
- Truffle: 5.0.12
- OpenZeppelin: 2.2.0

## Token
- Name: Simple Token
- Symbol: EGT

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
truffle migrate --reset --network rinkeby
```
