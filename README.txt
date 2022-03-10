REMIX EXAMPLE PROJECT

Remix example project is present when Remix loads for the very first time or there are no files existing in the File Explorer. 
It contains 3 directories:

1. 'contracts': Holds three contracts with different complexity level, denoted with number prefix in file name.
2. 'scripts': Holds two scripts to deploy a contract. It is explained below.
3. 'tests': Contains one test file for 'Ballot' contract with unit tests in Solidity.

SCRIPTS

The 'scripts' folder contains example async/await scripts for deploying the 'Storage' contract.
For the deployment of any other contract, 'contractName' and 'constructorArgs' should be updated (along with other code if required). 
Scripts have full access to the web3.js and ethers.js libraries.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.

Output from script will appear in remix terminal.


Transaction Hash:
0x6d52621cb548f3ab962746bcdb21e501479ddac09700f0e0d01ee43bc7e33074 
Status:
Success
Block:
10304330 2 Block Confirmations
Timestamp:
59 secs ago (Mar-10-2022 12:11:08 PM +UTC)
From:
0xc02797392e775a51122d03834e8f3ffe83e04c16 
To:
[Contract 0xd3d59244fef5f9af0fb9d67ff0a42fba8ebd5542Created] 
Value:
0 Ether ($0.00)
Transaction Fee:
0.001118845005817994 Ether ($0.00)
Gas Price:
0.000000002500000013 Ether (2.500000013 Gwei)
Gas Limit & Usage by Txn:
447,538 | 447,538 (100%)
Gas Fees:
Base: 0.000000013 Gwei |Max: 2.500000026 Gwei |Max Priority: 2.5 Gwei
Burnt & Txn Savings Fees:
🔥 Burnt: 0.000000000005817994 Ether ($0.00)💸 Txn Savings: 0.000000000005817994 Ether ($0.00)
