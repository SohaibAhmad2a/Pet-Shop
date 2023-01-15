# PetShop
I redesigned the Dapp given on the following link https://trufflesuite.com/guides/pet-shop/#background. In order to use the Dapp, follow the steps:
* Install the truffle
* Create a directory, we gave Dog name to it.
* Intialize the truffle with command **truffle unbox pet-shop** in your
* Paste Adoption.sol from this repository to Dog/contracts
* Paste 2_deploy_contracts.js from this repository to Dog/migrations
* Migrate the smart contract to Ganache using the command **truffle migrate**
* Paste TestAdoption.sol file from this repository to migrations/test
* Run command **truffle test**
* Open /src/js/app.js and replace app.js of the directory with app.js given in this repository
* run **npm run dev** <br>
What is happening? You created a contract named **Adoption.sol** and migrated it to Ganache using truffle. You then created front end using app.js. Now front end is connected to Ganache's Blockchain via Web3. This is it...
