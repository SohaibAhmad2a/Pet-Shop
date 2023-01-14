# PetShop
I redesigned the Dapp given on the following link https://trufflesuite.com/guides/pet-shop/#background. In order to use the Dapp, follow the steps:
* Install the truffle
* Intialize the truffle with command **truffle unbox pet-shop**
* Paste Adoption.sol from this repository to contracts directory
* Paste 2_deploy_contracts.js from this repository to migrations directory
* Migrate the smart contract to Ganache using the command **truffle migrate**
* Paste TestAdoption.sol file from this repository into the test directory
* Run command **truffle test**
* Open /src/js/app.js and replace app.js of the directory with this app.js given in this repository
* run **npm run dev**
What is happening? You created a contract named **Adoption.sol** and migrated it to Ganache using truffle. You then created front end using app.js. Now front end is onnected to Blockchain via Web3 to Ganache. This is it...
