<h1 align="center"> Blockchain-Based Academic Credential Verification </h1>
<h3 align="center"> Secure Academic Certificate Issuance and Verification using Blockchain Technology </h3>

---

## About

Blockchain-Based Academic Credential Verification is a decentralized application developed to provide a secure, transparent, and tamper-proof platform for issuing, storing, and verifying academic credentials.

Traditional certificate verification systems rely on centralized databases, making them vulnerable to document forgery, unauthorized modifications, and time-consuming verification procedures. This project addresses these challenges by leveraging blockchain technology and decentralized storage to ensure that every issued credential is authentic and verifiable.

The system enables educational institutions to issue digital certificates securely, while students can access and share their credentials with employers or other organizations for instant verification.

---

## Project Highlights

- Secure issuance of academic certificates.
- Blockchain-based immutable credential records.
- Decentralized storage using IPFS.
- Student and institution login portals.
- Digital certificate verification.
- Secure document sharing.
- Ethereum smart contract integration.
- Transparent and tamper-proof verification process.

---

## System Overview

- Educational institutions issue certificates through the platform.
- Certificate metadata is securely stored on the Ethereum blockchain.
- Certificate files are stored using IPFS.
- Every certificate is associated with a unique blockchain transaction.
- Students can securely access and share their certificates.
- Employers and organizations can instantly verify credential authenticity.

---

## Technologies Used

- Ethereum Blockchain
- Solidity Smart Contracts
- React.js
- Node.js
- IPFS (InterPlanetary File System)
- MetaMask
- Truffle Framework
- Web3.js

---

## System Architecture

```
Institution Portal
        │
        ▼
Certificate Generation
        │
        ▼
Hash Generation
        │
        ▼
Upload to IPFS
        │
        ▼
Store Hash on Ethereum Blockchain
        │
        ▼
Student Dashboard
        │
        ▼
Certificate Sharing
        │
        ▼
Credential Verification
```

---

## Features

### Institution

- Register and authenticate institution
- Upload academic certificates
- Manage student records
- Verify uploaded certificates
- View issued credentials

### Student

- Secure login
- Access academic certificates
- Download certificates
- Share certificates securely
- View credential history

### Verifier

- Verify certificate authenticity
- View certificate information
- Check blockchain transaction details

---

## Installation

### Prerequisites

- Node.js
- MetaMask
- Ganache or Ethereum Test Network
- Truffle

### Clone Repository

```bash
git clone https://github.com/Divyanshi-00001/Blockchain-Based-Academic-Credential-Verification.git
```

Move to the project directory

```bash
cd Blockchain-Based-Academic-Credential-Verification
```

Install dependencies

```bash
npm install
```

Compile smart contracts

```bash
truffle compile
```

Deploy smart contracts

```bash
truffle migrate
```

Start the React application

```bash
cd client
npm start
```

Open the application

```
http://localhost:3000
```

---

## Folder Structure

```
Blockchain-Based-Academic-Credential-Verification/

│── client/
│── contracts/
│── migrations/
│── test/
│── build/
│── src/
│── README.md
│── package.json
│── truffle-config.js
```

---

## Future Enhancements

- QR Code based certificate verification
- Multi-University support
- NFT-based academic credentials
- Mobile application
- AI-assisted certificate fraud detection
- Cloud deployment
- Multi-factor authentication

---

## Applications

- Universities
- Colleges
- Training Institutes
- Government Organizations
- Recruitment Agencies
- Corporate HR Verification

---

## Contributing

Contributions are welcome.

To contribute:

- Fork the repository.
- Create a feature branch.
- Commit your changes.
- Submit a Pull Request.

---

## Authors

This project is developed for academic and educational purposes.

---

