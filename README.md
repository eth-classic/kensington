# Kensington testnet

A temporary Atlantis-enabled, proof-of-work testnet for Ethereum Classic.

Consensus Monitoring Dashboard: http://35.226.196.242:3000/

Atlantis Hardfork: `100`

### Parity Ethereum

Required version: 2.4.7+

```bash
parity --chain ./parity.json
```

### Geth Classic

Required version: 6.0.2+

```bash
geth --chain ./gethc.json
```

### Multi Geth

Required version: 1.9.1+

##### Genesis file (legacy)

```bash
geth init --datadir ~/.ethereum/kensington ./mgeth.json
geth --datadir ~/.ethereum/kensington --networkid 88

```

##### Parity chain spec (experimental)

```bash
geth --chainspec.parity ./parity.json
```

_Other testnets for Atlantis are available: [Kotti](https://github.com/goerli/testnet#meta-data-kotti-classic) (Parity Ethereum, Multi Geth) or [Morden](https://github.com/eth-classic/morden) (Parity Ethereum, Geth Classic)._
