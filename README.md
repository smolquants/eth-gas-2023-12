# eth-gas-2023-12

Analysis of EIP-1559 gas markets post-merge; 1 year later.

## Replication

To check the results, clone the repo

```sh
git clone https://github.com/smolquants/eth-gas-2023-12.git
```

Install dependencies with [`hatch`](https://github.com/pypa/hatch) and [`ape`](https://github.com/ApeWorX/ape)

```sh
hatch build
hatch shell
(eth-gas-2023-12) ape plugins install .
```

Setup your environment with an [Alchemy](https://www.alchemy.com) key

```sh
export WEB3_ALCHEMY_PROJECT_ID=<YOUR_PROJECT_ID>
```

Then launch [`ape-notebook`](https://github.com/ApeWorX/ape-notebook)

```sh
(eth-gas-2023-12) ape notebook
```
