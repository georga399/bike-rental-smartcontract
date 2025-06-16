# Bike rental DAML model


[![Language](https://img.shields.io/badge/Language-DAML-blueviolet)](https://daml.com)

## Core concepts

The system is built around several smart contracts (templates) that represent both assets and agreements between parties:

- BikeProvider (Party): The company that owns the bikes.

- Customer (Party): The customer who can rent a bike.

- Bike (Contract): The digital asset representing a physical bike with a unique ID.

- BikeRentalProposal (Contract): A one-way rental offer from the BikeProvider to the Customer.

- BikeRentalAgreement (Contract): A two-way agreement that occurs once the Customer accepts the offer.

## Prerequisites
Install [DAML SDK](https://docs.daml.com/getting-started/installation.html).

## Getting started
1. Clone the repo:
    ```sh
    git clone https://github.com/georga399/bike-rental-smartcontract
    ```

2. Build project:
    ```sh
    daml build
    ```

3. Run tests:
     ```sh
    daml test
    ```
