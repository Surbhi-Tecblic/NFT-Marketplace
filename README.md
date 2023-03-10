
//Install metamask 
1 Clone the project locally, change into the directory, and install the dependencies:
#Install Node Modules
   npm install
    
2 Start the local Hardhat node
   npx hardhat node

3 With the network running, deploy the contracts to the local network in a separate terminal window
   npx hardhat run --network localhost scripts/deploy.js

//For Deploying on Mumbai Network 
   npx hardhat run --network mumbai scripts/deploy.js
4 Start the app
   npm run dev

Configuration
//Create .env file and set this settings from infura

  PROJECT_ID=2HOJiGDa1CaqLJEHkNgqe9smzxy
  PROJECT_SECRET_KEY=ef137d8ad1be6f6808d745feb6b32249
  SUB_DOMAIN=https://tecblic-nft-marketplace.infura-ipfs.io





