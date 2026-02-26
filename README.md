# SwapSquad

## Overview

SwapSquad is a hackathon project designed to facilitate peer-to-peer exchanges through a decentralized application model. The platform enables users to interact directly without reliance on centralized intermediaries.

This repository contains the full source code for the project, including application logic and user interface components.

## Objective

The goal of SwapSquad is to:

* Enable direct peer-to-peer interactions
* Reduce dependency on centralized platforms
* Improve transparency in digital exchanges
* Demonstrate blockchain-integrated application development

## Core Functionality

SwapSquad allows users to:

* Connect a compatible Web3 wallet
* Create marketplace listings
* Browse available listings
* Initiate and complete transactions

All state-changing operations are executed through smart contract interactions.

## Technology Stack

This project uses the following technologies:

* Frontend: JavaScript-based web application framework
* Backend: Python-based API service
* Smart Contracts: Solidity
* Blockchain Network: TRON

## Installation

### Prerequisites

* Node.js (recommended v16 or higher)
* Python 3.8 or higher
* TRON-compatible wallet extension

### Clone the Repository

```bash
git clone https://github.com/russelljoa/SwapSquad.git
cd SwapSquad
```

### Backend Setup

Navigate to the backend directory and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Run the backend service:

```bash
flask run
```
### Frontend Setup

Navigate to the frontend directory and install dependencies:

```bash
npm install
npm start
```

Ensure the frontend is configured with the correct smart contract address and network settings.

## Usage

1. Connect a TRON-compatible wallet.
2. Create or browse listings.
3. Initiate a transaction.
4. Confirm and complete the transaction on-chain.


## Contributors

* Russell Joarder
* Karl Boma
* Jaya Iskandar
