# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
Hardhat version 2.10.1

Usage: hardhat [GLOBAL OPTIONS] <TASK> [TASK OPTIONS]

GLOBAL OPTIONS:

  --config           	A Hardhat config file. 
  --emoji            	Use emoji in messages. 
  --help             	Shows this message, or a task's help if its name is provided 
  --max-memory       	The maximum amount of memory that Hardhat can use. 
  --network          	The network to connect to. 
  --show-stack-traces	Show stack traces. 
  --tsconfig         	A TypeScript config file. 
  --verbose          	Enables Hardhat verbose logging 
  --version          	Shows hardhat's version. 


AVAILABLE TASKS:

  check             	Check whatever you need
  clean             	Clears the cache and deletes all artifacts
  compile           	Compiles the entire project, building all artifacts
  console           	Opens a hardhat console
  coverage          	Generates a code coverage report for tests
  flatten           	Flattens and prints contracts and their dependencies
  gas-reporter:merge	
  help              	Prints this message
  node              	Starts a JSON-RPC server on top of Hardhat Network
  run               	Runs a user-defined script after compiling the project
  test              	Runs mocha tests
  typechain         	Generate Typechain typings for compiled contracts
  verify            	Verifies contract on Etherscan

To get help for a specific task run: npx hardhat help [task]
