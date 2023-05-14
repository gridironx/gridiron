<!--
order: 8
-->

# Clients

A user can query the `x/incentives` module using the CLI, JSON-RPC, gRPC or REST.

## CLI

Find below a list of `gridirond` commands added with the `x/incentives` module. You can obtain the full list by using the `gridirond -h` command.

### Queries

The `query` commands allow users to query `incentives` state.

**`incentives`**

Allows users to query all registered incentives.

```go
gridirond query incentives incentives [flags]
```

**`incentive`**

Allows users to query an incentive for a given contract.

```go
gridirond query incentives incentive CONTRACT_ADDRESS [flags]
```

**`gas-meters`**

Allows users to query all gas meters for a given incentive.

```bash
gridirond query incentives gas-meters CONTRACT_ADDRESS [flags]
```

**`gas-meter`**

Allows users to query a gas meter for a given incentive and user.

```go
gridirond query incentives gas-meter CONTRACT_ADDRESS PARTICIPANT_ADDRESS [flags]
```

**`params`**

Allows users to query incentives params.

```bash
gridirond query incentives params [flags]
```

### Proposals

The `tx gov submit-legacy-proposal` commands allow users to query create a proposal using the governance module CLI:

**`register-incentive`**

Allows users to submit a `RegisterIncentiveProposal`.

```bash
gridirond tx gov submit-legacy-proposal register-incentive CONTRACT_ADDRESS ALLOCATION EPOCHS [flags]
```

**`cancel-incentive`**

Allows users to submit a `CanelIncentiveProposal`.

```bash
gridirond tx gov submit-legacy-proposal cancel-incentive CONTRACT_ADDRESS [flags]
```

**`param-change`**

Allows users to submit a `ParameterChangeProposal``.

```bash
gridirond tx gov submit-legacy-proposal param-change PROPOSAL_FILE [flags]
```

## gRPC

### Queries

| Verb   | Method                                                     | Description                                   |
| ------ | ---------------------------------------------------------- | --------------------------------------------- |
| `gRPC` | `gridiron.incentives.v1.Query/Incentives`                     | Gets all registered incentives                |
| `gRPC` | `gridiron.incentives.v1.Query/Incentive`                      | Gets incentive for a given contract           |
| `gRPC` | `gridiron.incentives.v1.Query/GasMeters`                      | Gets gas meters for a given incentive         |
| `gRPC` | `gridiron.incentives.v1.Query/GasMeter`                       | Gets gas meter for a given incentive and user |
| `gRPC` | `gridiron.incentives.v1.Query/AllocationMeters`               | Gets all allocation meters                    |
| `gRPC` | `gridiron.incentives.v1.Query/AllocationMeter`                | Gets allocation meter for a denom             |
| `gRPC` | `gridiron.incentives.v1.Query/Params`                         | Gets incentives params                        |
| `GET`  | `/gridiron/incentives/v1/incentives`                          | Gets all registered incentives                |
| `GET`  | `/gridiron/incentives/v1/incentives/{contract}`               | Gets incentive for a given contract           |
| `GET`  | `/gridiron/incentives/v1/gas_meters`                          | Gets gas meters for a given incentive         |
| `GET`  | `/gridiron/incentives/v1/gas_meters/{contract}/{participant}` | Gets gas meter for a given incentive and user |
| `GET`  | `/gridiron/incentives/v1/allocation_meters`                   | Gets all allocation meters                    |
| `GET`  | `/gridiron/incentives/v1/allocation_meters/{denom}`           | Gets allocation meter for a denom             |
| `GET`  | `/gridiron/incentives/v1/params`                              | Gets incentives params                        |
