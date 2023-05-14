<!--
order: 2
-->

# Quick Connect

Quickly connect your app or client to Gridiron services {synopsis}

## Public Available Endpoints

Below is a list of publicly available endpoints that you can use to connect to the Gridiron mainnet and
public testnets:

::: tip
You can also use [chainlist.org](https://chainlist.org/) to add the node directly to [Metamask](./../users/wallets/metamask.md#automatic-import).
:::

<!-- markdown-link-check-disable -->
### Mainnet

| Address                                       | Category               | Maintainer                              |
| --------------------------------------------- | ---------------------- | --------------------------------------- |
| `https://grpc.bd.gridiron.org:9090`              | `Cosmos` `gRPC`        | [Blockdaemon](https://blockdaemon.com/) |
| `https://rest.bd.gridiron.org:1317`              | `Cosmos` `REST`        | [Blockdaemon](https://blockdaemon.com/) |
| `https://tendermint.bd.gridiron.org:26657`       | `Tendermint` `RPC`     | [Blockdaemon](https://blockdaemon.com/) |
| `https://eth.bd.gridiron.org:8545`               | `Ethereum` `JSON-RPC`  | [Blockdaemon](https://blockdaemon.com/) |
| `wss://eth.bd.gridiron.org:8546`                 | `Ethereum` `Websocket` | [Blockdaemon](https://blockdaemon.com/) |
| `https://gridiron-json-rpc.stakely.io`           | `Ethereum` `JSON-RPC`  | [Stakely](https://stakely.io/)          |
| `https://gridiron-rpc.stakely.io`                | `Cosmos` `RPC`         | [Stakely](https://stakely.io/)          |
| `https://gridiron-lcd.stakely.io`                | `Cosmos` `REST`        | [Stakely](https://stakely.io/)          |
| `https://jsonrpc-gridiron-ia.cosmosia.notional.ventures/` | `Ethereum` `JSON-RPC`  | [Notional](https://notional.ventures/)  |
| `https://rpc-gridiron-ia.cosmosia.notional.ventures:443`  | `Tendermint` `RPC`     | [Notional](https://notional.ventures/)  |
| `https://grpc-gridiron-ia.cosmosia.notional.ventures:443` | `Tendermint` `gRPC`    | [Notional](https://notional.ventures/)  |
| `https://api-gridiron-ia.cosmosia.notional.ventures:443`  | `Tendermint` `RPC`     | [Notional](https://notional.ventures/)  |
| `https://rpc.gridiron.nodestake.top`             | `Tendermint` `RPC`     | [NodeStake](https://nodestake.top/)     |
| `https://grpc.gridiron.nodestake.top`            | `Cosmos` `gRPC`        | [NodeStake](https://nodestake.top/)     |
| `https://api.gridiron.nodestake.top`             | `Cosmos` `REST`        | [NodeStake](https://nodestake.top/)     |
| `https://jsonrpc.gridiron.nodestake.top`         | `Ethereum` `JSON-RPC`  | [NodeStake](https://nodestake.top/)     |
| `https://rpc.gridiron.chaintools.tech/`          | `Tendermint` `RPC`     | [ChainTools](https://chaintools.tech/)  |
| `https://gridiron.grpcui.chaintools.host`        | `Cosmos` `gRPC`        | [ChainTools](https://chaintools.tech/)  |
| `https://api.gridiron.chaintools.tech/`          | `Tendermint` `API`     | [ChainTools](https://chaintools.tech/)  |
| `https://rpc.gridiron.silknodes.io`              | `Tendermint` `RPC`     | [Silk Nodes](https://silknodes.io/)     |
| `https://grpc.gridiron.silknodes.io`             | `Cosmos` `gRPC`        | [Silk Nodes](https://silknodes.io/)     |
| `https://api.gridiron.silknodes.io`              | `Cosmos` `REST`        | [Silk Nodes](https://silknodes.io/)     |
| `https://gridiron-mainnet.public.blastapi.io`    | `Ethereum` `JSON-RPC`  | [BLAST](https://blastapi.io/)           |
| `wss://gridiron-mainnet.public.blastapi.io`      | `Ethereum` `Websocket` | [BLAST](https://blastapi.io/)           |
| `https://gridiron-evm.publicnode.com`            | `Ethereum` `JSON-RPC`  | [PublicNode (by Allnodes)](https://gridiron.publicnode.com/) |
| `https://gridiron-rpc.publicnode.com`            | `Tendermint` `RPC`     | [PublicNode (by Allnodes)](https://gridiron.publicnode.com/) |
| `https://gridiron-rest.publicnode.com`           | `Cosmos` `REST`        | [PublicNode (by Allnodes)](https://gridiron.publicnode.com/) |
| `https://gridiron-api.validatrium.club`           | `Tendermint` `API`        | [Validatrium](https://validatrium.com/) |
| `https://gridiron-rpc.validatrium.club`           | `Tendermint` `RPC`        | [Validatrium](https://validatrium.com/) |
| `https://gridiron-rpc.gateway.pokt.network`      | `Ethereum` `JSON-RPC`  | [PocketNetwork](https://www.pokt.network/)  |

### Testnet
<!-- markdown-link-check-disable -->

| Address                                      | Category               | Maintainer                              |
| -------------------------------------------- | ---------------------- | --------------------------------------- |
| `https://grpc.bd.gridiron.dev:9090`             | `Cosmos` `gRPC`        | [Blockdaemon](https://blockdaemon.com/) |
| `https://rest.bd.gridiron.dev:1317`             | `Cosmos` `REST`        | [Blockdaemon](https://blockdaemon.com/) |
| `https://tendermint.bd.gridiron.dev:26657`      | `Tendermint` `RPC`     | [Blockdaemon](https://blockdaemon.com/) |
| `https://eth.bd.gridiron.dev:8545`              | `Ethereum` `JSON-RPC`  | [Blockdaemon](https://blockdaemon.com/) |
| `wss://eth.bd.gridiron.dev:8546`                | `Ethereum` `Websocket` | [Blockdaemon](https://blockdaemon.com/) |
| `https://gridiron-testnet-rpc.polkachu.com:443` | `Tendermint` `RPC`     | [Polkachu](https://polkachu.com)        |
| `https://rpc-t.gridiron.nodestake.top`          | `Tendermint` `RPC`     | [NodeStake](https://nodestake.top/)     |
| `https://grpc-t.gridiron.nodestake.top`         | `Cosmos` `gRPC`        | [NodeStake](https://nodestake.top/)     |
| `https://api-t.gridiron.nodestake.top`          | `Cosmos` `REST`        | [NodeStake](https://nodestake.top/)     |
| `https://jsonrpc-t.gridiron.nodestake.top`      | `Ethereum` `JSON-RPC`  | [NodeStake](https://nodestake.top/)     |
| `https://gridiron-testnet-rpc.qubelabs.io`      | `Tendermint` `RPC`     | [Qubelabs](https://qubelabs.io/)        |
| `https://gridiron-testnet-lcd.qubelabs.io`      | `Cosmos` `REST`        | [Qubelabs](https://qubelabs.io/)        |
| `https://gridiron-testnet-grpc.qubelabs.io`     | `Cosmos` `gRPC`        | [Qubelabs](https://qubelabs.io/)        |
