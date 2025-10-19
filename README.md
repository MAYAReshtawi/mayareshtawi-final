# Blockchain Final Project

This project was developed as a final academic submission to demonstrate the concept of Blockchain integration using Remix and PHP.

---

## Overview

This project is a complete Blockchain application integrating a Smart Contract deployed via Remix and a PHP/XAMPP-based frontend interface. It demonstrates the flow of creating, storing, and verifying blockchain-based certificates in a decentralized manner while maintaining a user-friendly interface for interaction.

Key features include:

- Smart Contract for certificate management (deployable via Remix)
- PHP frontend dashboard for viewing and managing certificates
- XAMPP-based backend server for handling requests
- Full blockchain flow demonstration from deployment to interaction

---

## Project Structure

```
Blockchain-Final-Project/
│
├─ smart_contracts/
│   └─ Certificate.sol        # Solidity smart contract
│
├─ frontend/
│   ├─ index.php               # Main dashboard page
│   ├─ register.php            # User registration page
│   ├─ view_certificate.php    # Page to view issued certificates
│   └─ assets/                 # CSS, JS, images
│
├─ backend/
│   └─ db_config.php           # Database connection settings
│
└─ README.md
```

---

## Running the Frontend (PHP/XAMPP)

1. Install **XAMPP** or any PHP local server.
2. Copy the `frontend/` and `backend/` folders into `htdocs` (or equivalent web directory).
3. Start **Apache** and **MySQL** servers via XAMPP.
4. Open your browser and navigate to:
   ```
   http://localhost/frontend/index.php
   ```
5. Register a new user or login to access the dashboard.
6. Use the dashboard to issue, view, or manage blockchain certificates.

---

## Deploying the Smart Contract via Remix

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Create a new file `Certificate.sol` inside `smart_contracts/`.
3. Copy the Solidity code from `Certificate.sol`.
4. Compile the contract using the Solidity compiler.
5. Deploy the contract to **JavaScript VM**, **Injected Web3**, or a test network.
6. Use the deployed contract address in your PHP frontend configuration to interact with the blockchain.

---

## Full Setup Summary

- **Frontend:** PHP/XAMPP
- **Backend:** MySQL (via XAMPP)
- **Smart Contract:** Solidity (Remix IDE)
- **Workflow:** 
  1. Deploy the smart contract via Remix.
  2. Configure frontend with contract address.
  3. Start XAMPP server for PHP/MySQL backend.
  4. Access the dashboard to interact with blockchain features.

---

## Notes

- Ensure XAMPP ports 80 and 3306 are free before starting the server.
- The project demonstrates the blockchain concept but runs in a local test environment.
- For full functionality, connect the frontend to the correct deployed contract address.
- PHP sessions are used for user authentication and dashboard access.
- Styling and interface are simplified for demonstration purposes.

---

**End of README**
