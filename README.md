# DocuChain: Decentralized Document Authentication Using IPFS

**VerifiChain** is a cutting-edge solution designed to provide a decentralized platform for authenticating documents by harnessing the capabilities of Blockchain technology and the InterPlanetary File System (IPFS). This system records document hashes on the Blockchain, while securely storing the actual documents on IPFS. This dual-layer approach ensures that documents remain untampered and easily retrievable by authorized users.

## Key Features

- **Robust Security**: Employs Blockchain and IPFS to safeguard document integrity.
- **Decentralized Framework**: Removes reliance on a central authority, minimizing risks associated with single points of failure.
- **Streamlined Verification**: Facilitates a swift verification process without intermediary involvement.
- **Intuitive User Experience**: Offers a simple interface for uploading and verifying documents.
- **Diverse Document Support**: Accepts a wide range of document types and formats.

## Prerequisites

- Ensure Node.js and npm are installed on your system.
- Set up a MetaMask Wallet for secure interactions.
- Obtain IPFS API credentials (key and secret) from [Infura](https://infura.io).

## Setup Instructions

1. **Clone the Project Repository**:
   ```bash
   git clone https://github.com/DevAloshe/BlockChain-Based-Document-Verfication-With-IPFS.git
   ```

2. **Install Dependencies**:
   Navigate into the project directory and install necessary packages:
   ```bash
   cd BlockChain-Based-Document-Verfication-With-IPFS
   npm install
   ```

3. **Deploy the Smart Contract**:
   Utilize the Remix online IDE to deploy the `contract.sol`. After deployment, copy the contract address and insert it into the `app.js` file. Also, configure the network URL and network explorer URL as per your MetaMask settings.

4. **Launch the Application**:
   Use the Live Server extension to open the application in your browser.

5. **Configure Infura for Document Viewing**:
   To access the documents, create an account on [Infura](https://infura.io) and use the provided API ID and secret in the `app.js` file within the `uploadToInfura` function.

## How to Use VerifiChain

1. **Authorize Exporters**: As the system owner, you need to add exporters by clicking the "Add Exporter" button and entering their MetaMask address.

2. **Upload Your Document**: Click the "Upload Document" button, select the file you wish to upload, and proceed. The document will be encrypted and uploaded to IPFS, with its hash securely stored on the Blockchain.

3. **Document Verification**: To verify a document, click the "Verify Document" button. Choose the document you want to verify and hit the verify button. The system will retrieve the document from IPFS, decrypt it, and compare its hash with the one stored on the Blockchain.

4. **Receive Verification Results**: The application will display whether the document is authentic or has been tampered with.

## License Information

This project operates under the MIT License. Please refer to the LICENSE.md file for further details.

## Acknowledgments

- MetaMask Documentation, Solidity, Web3.js Resources, IPFS Documentation, Truffle Framework Guides
