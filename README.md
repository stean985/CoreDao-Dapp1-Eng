1- clone the repository with the command: git clone https://github.com/stean985/CoreDao-Dapp1-Fr.git

2- navigate to the directory: cd /CoreDao-Dapp1/Backend
3- create a json file with the name: secret.json
4- open the secret.json file and paste the line below:
{‘PrivateKey’: ‘the private key of your e-wallet wallet’}


5- install the Hardhat dependencies with the command: npm install --save-dev hardhat
6- compile the intellignet Storage.sol contract with the command: npx hardhat compile
7- and finally deploy the smart contract with the command: npx hardhat run ./scripts/deploy-and-call.js
the result will look like this:

>npx hardhat run scripts/deploy-and-call.js
Storage contract deployed to: 0x48F68BF4A1b1fE6589B9D0a5ad0dF0520582edA2
call retrieve(): BigNumber { value: ‘0’ }
call store(), set value to 100
call retrieve() again: BigNumber { value: ‘100’ }


8- navigate to the directory: cd /CoreDao-Dapp1/Frontend
9- install all the dependencies (e.g. Node.js modules) with the command: npm install
10- test the project with the command: npm run dev

Translated with DeepL.com (free version)
