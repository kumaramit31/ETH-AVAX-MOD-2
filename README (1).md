# Smart Contract Management - ETH + AVAX

This project demonstrates a simple Ethereum smart contract with 2-3 functions. The contract will be deployed on the Ethereum blockchain, and the values returned by these functions will be displayed in the frontend of the application.

# Frontend Application

The frontend application will be a simple web page that interacts with the deployed smart contract. It will use web3.js to connect to the Ethereum network and call the smart contract functions. The returned values will be displayed on the web page.

# Prerequisites

1. Node.js and npm (Node Package Manager) installed on your machine.
2. A web browser to view the frontend application.
3. An Ethereum wallet (e.g., MetaMask) connected to the Ropsten test network (or any other test network).


# Getting started

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

# License

This project is licensed under the MIT License.