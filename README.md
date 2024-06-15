# BlockBasket - Decentralization of Dairy Supply Chain using Blockchain

## Overview
BlockBasket aims to revolutionize the dairy supply chain by leveraging blockchain technology to ensure transparency, efficiency, and security. Through the use of Ethereum Virtual Machine (EVM) based blockchain, BlockBasket provides real-time data storage and smart contract functionalities to automate processes and transactions in the dairy supply chain.

## Features
- **Real-Time Data Storage**: Collect and store data from various points in the dairy supply chain directly onto the blockchain.
- **Smart Contracts**: Automate data retrieval and payment processes using Solidity-based smart contracts.
- **Decentralization**: Enhance transparency and security by decentralizing the supply chain data.
- **Web3 Integration**: Seamless interaction with the blockchain through a web frontend using Web3.js.
- **User-Friendly Interface**: Manage and monitor supply chain activities with an intuitive web interface.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Blockchain**: Solidity, Ethereum Virtual Machine (EVM)
- **Development Tools**: Remix IDE, Ganache, Hardhat
- **Blockchain Interaction**: Web3.js, Metamask

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/blockbasket.git
   cd blockbasket
   ```

2. **Install Dependencies**:
   Ensure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

3. **Setup Ganache**:
   Download and install [Ganache](https://www.trufflesuite.com/ganache) to create a local blockchain for development and testing.

4. **Configure Hardhat**:
   Initialize Hardhat in your project:
   ```bash
   npx hardhat
   ```
   Follow the prompts to create a basic sample project. Replace the `hardhat.config.js` content with your configuration details, including network settings for Ganache.

5. **Compile and Deploy Smart Contracts**:
   Compile your Solidity smart contracts using Hardhat:
   ```bash
   npx hardhat compile
   ```
   Deploy the contracts to your local Ganache blockchain:
   ```bash
   npx hardhat run scripts/deploy.js --network ganache
   ```

6. **Connect Metamask**:
   Install [Metamask](https://metamask.io/) browser extension and configure it to connect to your local Ganache blockchain.

7. **Run the Application**:
   Start the development server:
   ```bash
   npm start
   ```
   Open your browser and navigate to `http://localhost:3000` to interact with the application.

## Usage
1. **Data Entry**: Use the web interface to input data from different points in the dairy supply chain.
2. **Smart Contracts**: View and execute smart contracts to fetch data from the blockchain and automate payment processes.
3. **Monitoring**: Track the flow of products and payments through the supply chain with real-time updates.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [Solidity](https://soliditylang.org/)
- [Remix IDE](https://remix.ethereum.org/)
- [Ganache](https://www.trufflesuite.com/ganache)
- [Hardhat](https://hardhat.org/)
- [Web3.js](https://web3js.readthedocs.io/)
- [Metamask](https://metamask.io/)

## Contact
For any inquiries or issues, please contact:
* Name: Sumit Patil
* Email: sumitpatilplk920@gmail.com
* GitHub: sumitpatil05

---

Thank you for using BlockBasket! Transforming the dairy supply chain with blockchain technology!
