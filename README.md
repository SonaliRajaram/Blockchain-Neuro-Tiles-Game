## Blockchain Memory Game

A decentralized memory game built on the Ethereum blockchain. Players match cards to earn unique NFT rewards, demonstrating blockchain integration with interactive web applications.
It is built for Mild Cognitive Impairement (MCI) Patients to improve their memory retention.

## Features

1. Smart Contract Integration: Mint NFTs as rewards for matching cards using an ERC-721 smart contract.
2. Decentralized Ownership: Tokens are stored on the Ethereum blockchain, ensuring true digital ownership.
3. MetaMask Support: Connect your Ethereum wallet for secure authentication and transactions.
4. Web3.js Integration: Seamless communication between the React frontend and Ethereum blockchain.
5. Local Blockchain Testing: Use Ganache for safe, local development and testing.
6. Gas Fee Awareness: Real blockchain transactions with visible gas costs.
7. Responsive UI: Built with React for a smooth, interactive user experience.

## Project Structure
```
Blockchain_Memory_Game/ 
├── src/ 
│ ├── abis/
│ │ ├── MemoryToken.json 
│ ├── contracts/ 
│ │ ├── MemoryToken.sol 
│ │ ├── Migrations.sol 
│ ├── components/ 
│ │ ├── App.js 
│ │ ├── App.css 
│ ├── images/ 
│ │ ├── pen.png, book.png, etc. 
│ ├── brain.png 
│ ├── index.js 
│ ├── index.html 
├── migrations/ 
│ ├── 1_initial_migration.js 
│ ├── 2_deploy_contracts.js 
├── truffle-config.js 
├── package.json 
├── README.md
```

## Installation & Setup
Prerequisites
-- Node.js (v16 or higher recommended)
-- Truffle globally:
-- npm install -g truffle
-- Ganache (GUI or CLI)
-- MetaMask browser extension

## Steps
1.Clone the repository:
```sh
git clone <repository-url>
cd Blockchain_Memory_Game
```
2.Install dependencies:
```sh
npm install
```
3.Start Ganache:
```sh
Open Ganache GUI or run ganache-cli in terminal.
```
4.Compile and deploy smart contracts:
```sh
truffle compile
truffle migrate --reset
```
5.Start the React development server
```sh
npm start
```
6.Connect MetaMask:
```sh
Add the Ganache network to MetaMask (http://127.0.0.1:7545, Chain ID: 1337 or 5777).
Import an account using a Ganache private key.
```

## Usage
1. Open your browser and go to:
```sh
http://localhost:3000
```
2. Connect MetaMask and select the correct network.
3. Play the memory game—match cards to mint NFT rewards!
4. View your collected tokens in the UI.

## Testing
To run smart contract tests:
```sh
truffle test
```

## Build for Production
To build the React app for production:
```sh
npm run build
```

## Contributing
Contributions are welcome!

1. Fork the repository.
2. Create a feature branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m "Add new feature").
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.
   
For major changes, please open an issue first to discuss your proposal.


