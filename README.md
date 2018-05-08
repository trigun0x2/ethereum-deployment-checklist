# The smart contract pre-launch checklist
## Purpose
Create a list of important tasks and gotchas to check for before launching a
smart contract. This is not meant to be a security guide.
This is a generic guide and does not cover cases specific to each contract’s
use case.


Feel free to make PRs for things I may have missed.

## Checklist
### Code complete
- [ ]  Lock in compiler version
- [ ]  Lock in dependency versions (npm modules)
- [ ]  Lock in truffle version
- [ ]  Internal code audit
- [ ]  3rd party code audit
### Testnet deployed
- [ ]  Release beta Dapp (if needed)
- [ ]  Test gas usage for each function
- [ ]  Make changes (if needed)
- [ ]  Record release version of code (commit hash)
- [ ]  Record compiled bytecode
- [ ]  Record compiler version
### Mainnet deployed
- [ ]  Verify code on Etherscan (optional)
- [ ]  Launch official Dapp
- [ ]  Launch PR (blog, twitter, etc.)
