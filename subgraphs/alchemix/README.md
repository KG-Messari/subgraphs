# Alchemix Yield Protocol Subgraph

## Useful Links

- https://alchemix.fi/
- https://alchemix-finance.gitbook.io/v2/
- Add here

## Calculation Methodology v1.0.0

### Total Value Locked (TVL) USD

Sum across all Vaults:

`Vault Deposits + Deposits in Transmuter`

Ignores ALCX staked. 

### Total Revenue USD

Sum across all Vaults:

`Harvested Yield on Vaults + Harvested Yield on Transmuter Funds`

### Protocol-Side Revenue USD
Portion of the Total Revenue allocated to the Protocol

Sum across all Vaults:

`(Harvested Yield on Vaults + Harvested Yield on Transmuter Funds) * 10%`

<Add notes to consider if any - delete if none>

### Supply-Side Revenue USD
Portion of the Total Revenue allocated to the Supply-Side

Sum across all Vaults

`(Harvested Yield on TVL + Harvested Yield on Transmuter Funds) * 90%`

### Total Unique Users

Count of  Unique Addresses which have interacted with the protocol via any transaction

`Deposits`

`Withdrawals`

###  Reward Token Emissions Amount

To be added

###  Protocol Controlled Value

To be added
