# Offchain Data Storing Using Pinata & IPFS

## Overview
This project demonstrates how to store data off-chain using [Pinata](https://www.pinata.cloud/) and [IPFS](https://ipfs.tech/), with JWT authentication and local file uploads. It is designed to help developers understand how to securely and efficiently store files outside of a blockchain, while still maintaining verifiability and accessibility.

## What is Off-Chain Data Storage?
Off-chain data storage refers to storing data outside the blockchain network. While blockchains are excellent for immutability and transparency, they are not efficient for storing large files due to cost and scalability limitations. Off-chain storage allows you to keep large or non-critical data elsewhere, while storing only references (like hashes or URLs) on-chain.

**Benefits:**
- Reduces blockchain bloat
- Lowers transaction costs
- Enables storage of large files
- Maintains data integrity via cryptographic hashes

**References:**
- [Off-chain storage explained (Ethereum Foundation)](https://ethereum.org/en/developers/docs/data-storage/)
- [What is Off-Chain Storage? (Cointelegraph)](https://cointelegraph.com/learn/what-is-off-chain-storage)

## What is IPFS?
[IPFS](https://ipfs.tech/) (InterPlanetary File System) is a distributed file storage protocol that allows you to store and share files in a peer-to-peer network. Files are addressed by their content hash, ensuring immutability and verifiability.

**Key Features:**
- Content-addressed storage
- Decentralized and peer-to-peer
- Efficient file versioning and deduplication

**References:**
- [IPFS Documentation](https://docs.ipfs.tech/)
- [IPFS Whitepaper](https://ipfs.tech/ipfs-white-paper/)

## What is Pinata?
[Pinata](https://www.pinata.cloud/) is a service that makes it easy to upload, pin, and manage files on IPFS. It provides a user-friendly API, authentication (including JWT), and reliable pinning to ensure your files remain available on the IPFS network.

**References:**
- [Pinata Docs](https://docs.pinata.cloud/)
- [Pinata Blog: What is Pinata?](https://blog.pinata.cloud/what-is-pinata)

## Project Features
- Upload files locally and to IPFS via Pinata
- JWT authentication for secure uploads
- Simple web interface for file management

## Screenshots

### Upload Interface
![Upload Interface](asset/image1.png)

### Uploaded Files
![Uploaded Files](asset/image2.png)

## How to Use
1. Clone the repository
2. Install dependencies: `npm install`
3. Configure your Pinata API keys in the server
4. Run the server: `node server.js`
5. Access the web interface at `http://localhost:PORT`

## License
MIT
