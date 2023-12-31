# ETH e-commerce Project

This project consisted in creating an e-commerce in which payments were made with ETH. For this we leveraged both the local network created in the Faucet project and the database created on the SQL project as the e-commerce's product database.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Demo](#demo)

## Overview

This project combined several concepts and achievements of previous projects. An Express server to interact with the MySQL database and a React front end (making use of tools such as React Router or Context) to interact with the local network and make the purchases were developed.

## Features

- Homepage with the list of available products.
- Product page to add desired amount to cart.
- Cart page to make payment, i.e., a transaction to the e-commerce's wallet from the wallet connected to the app.

## Installation and usage

See the [Faucet](https://github.com/arynyestos/CodeCryptoFaucetProject) and [SQL](https://github.com/arynyestos/CodeCryptoSqlProject) projects to see the installation processes for the local network and the database, respectively, and launch them. Once those are installed and launched you can follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/arynyestos/CodeCryptoEthEcommerce.git
   ```

2. Navigate to the project directory:

   ```bash
   cd CodeCryptoEthEcommerce
   ```

3. Navigate to the "front" directory:

   ```bash
   cd .\front\
   ```
   
4. Install dependencies:
   ```bash
   yarn
   ```
     
## Usage
   
1. Open terminal on the server directory:
   ```bash
   cd .\server\  
   ```
2. Run the server:
    ```bash
    node server 
    ```
3. Run the front end:
   ```bash
   yarn dev
   ```

## Technologies Used
- Docker
- Express
- SQL
- React
- Geth

## Demo

Below you can a video showcasing the functionality of the project: a product is selected, thus navigating to the product's page, an amount is selected and the product is added to the cart. Then, navigating to the cart, the payment is made (although Metamask wasn't captured by the screen recording software, the transaction hash is displayed below).

https://github.com/arynyestos/CodeCryptoEthEcommerce/assets/33223441/3b357e40-4d51-4d10-b467-52db5205e39b





