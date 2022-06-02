# oracle-cryptozombies

Sample project to illustrate how a solidity oracle works.

## Contents

- `/caller` : Folder containing files for caller smart contract
  - caller-contract.sol : The caller smart contract
  - eth-price-oracle-contract-interface.sol : The interface of the oracle smart contract.

- `/oracle` : Folder containing files for oracle smart contract
  - eth-price-oracle-contract.sol : The oracle smart contract
  - caller-contractt-interface.sol : The interface of the caller smart contract.

- `/js` : Folder containing javascript files
  - eth-price-oracle.js : Node.js service to get and return expected data.
  - client.js : Act as the frontend of this example. 
