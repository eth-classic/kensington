# Kensington testnet

A temporary Atlantis-enabled, proof-of-work testnet for Ethereum Classic.

### Parity Ethereum

```bash
parity --chain ./parity.json
```

### Geth Classic

```bash
geth --chain ./gethc.json
```

### Multi Geth

##### Genesis file (legacy)

```bash
geth init --datadir ~/.ethereum/kensington ./mgeth.json
geth --datadir ~/.ethereum/kensington --networkid 88

```

##### Parity chain spec (experimental)

```bash
geth --chainspec.parity ./parity.json
```
