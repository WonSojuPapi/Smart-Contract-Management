# Smart Contract Management

This project is a decentralized application (DApp) for managing smart contracts on the Ethereum blockchain. It allows users to interact with deployed smart contracts, deposit and withdraw funds, and view account balances.

## Features

- **MetaMask Integration:** Seamless integration with MetaMask for interacting with the Ethereum blockchain.
- **Deposit and Withdraw:** Users can deposit and withdraw funds from the deployed smart contract.
- **Account Balance:** Real-time display of the user's account balance.
- **Error Handling:** Comprehensive error handling for various scenarios.
- **User Interface:** Clean and intuitive user interface for easy navigation.

## Usage

1. **Install MetaMask:**
   - Install the MetaMask browser extension and create or import an Ethereum account.

2. **Connect to Ethereum Network:**
   - Make sure MetaMask is connected to the desired Ethereum network.

3. **Install Visual Studio Code:**
   - Editing code and to run the program.

4. **Interact with the DApp:**
   - Open the application in your browser.
   - Connect your MetaMask wallet.
   - View your account address and balance.
   - Deposit or withdraw funds from the smart contract.
   - Monitor transaction status and balance updates.

## Deployment
Step by step
1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

## Author

Jakkin Elero
3.2 BSIT

## License

This project is licensed under the [MIT License](LICENSE).

