# NFT Minter

A decentralized application (DApp) for creating and minting NFTs on the blockchain. Users can connect their wallet, upload NFT metadata, and mint unique digital assets.

## Features

- Connect Web3 wallets (MetaMask)
- Mint NFTs directly from the web interface
- Upload and manage NFT metadata
- Smart contract integration
- Responsive UI
- Blockchain transaction tracking

## Tech Stack

### Frontend
- React.js
- JavaScript
- HTML/CSS

### Blockchain
- Solidity
- Ethereum / Polygon
- Web3.js / Ethers.js

### Storage
- IPFS
- Pinata

## Project Structure

```bash
NFTminter/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── contracts/
│   └── assets/
│
├── smart-contract/
├── package.json
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/SupremeOne3000/NFTminter.git
cd NFTminter
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm start
```

The application will run on:

```bash
http://localhost:3000
```

## Environment Variables

Create a `.env` file in the root directory:

```env
REACT_APP_RPC_URL=your_rpc_url
REACT_APP_CONTRACT_ADDRESS=your_contract_address
REACT_APP_PINATA_API_KEY=your_pinata_key
REACT_APP_PINATA_SECRET_KEY=your_pinata_secret
```

## Smart Contract Deployment

Compile the contract:

```bash
npx hardhat compile
```

Deploy:

```bash
npx hardhat run scripts/deploy.js --network <network_name>
```

## Usage

1. Open the application.
2. Connect your MetaMask wallet.
3. Upload NFT details.
4. Provide image and metadata.
5. Click **Mint NFT**.
6. Confirm the transaction in MetaMask.
7. View the minted NFT on the blockchain explorer.

## Screenshots

Add screenshots of:
- Home Page
- Wallet Connection
- NFT Minting Page
- Successful Transaction

## Future Improvements

- NFT Marketplace Integration
- Batch NFT Minting
- Multi-chain Support
- NFT Collection Management
- Royalties Support

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add feature"
```

4. Push branch

```bash
git push origin feature-name
```

5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Author

**Mithun M**

- GitHub: https://github.com/SupremeOne3000
- LinkedIn: https://www.linkedin.com/in/mithun-m-307608291/
