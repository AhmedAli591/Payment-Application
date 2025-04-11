# Payment Application

This repository simulates a **SALE transaction** process, focusing on the interaction between the **card**, **ATM terminal**, and **server**. The system processes payments by simulating real-world payment scenarios, where funds are deducted from a user’s account in exchange for purchased items or services.

## Project Overview

The Payment Application serves as a basic simulation for a financial transaction system, handling **SALE transactions**. In a **SALE transaction**, an amount is deducted from the user's account for the goods or services they are purchasing. The application simulates the process through communication between various entities such as the user’s **card**, the **ATM terminal**, and the **server**.

While the primary focus is on **SALE transactions**, the project is structured in a way that allows for easy expansion to accommodate other transaction types such as:

- **REFUND**: Returning funds after a purchase.
- **Pre-Authorization**: Verifying that funds are available before completing a transaction.
- **VOID**: Canceling a transaction before completion.

This project aims to provide a foundation for understanding the basic components of payment systems and their interactions.

## Features

- **SALE Transaction Simulation**: Implements the process of deducting funds from a user's account for a purchase.
- **Card Simulation**: Mimics the behavior of a payment card in the transaction process.
- **Server Simulation**: Simulates communication between the ATM terminal and the server to process and validate the transaction.
- **Scalable Architecture**: Easily extendable for future integration of other transaction types like **REFUND**, **Pre-Authorization**, and **VOID**.
- **Secure Transaction Flow**: Basic implementation of payment transaction flow, with potential for adding encryption and security features in future updates.

## Project Structure

- **`card.c`**: Contains code simulating the card behavior, including information storage and transaction initiation.
- **`terminal.c`**: Simulates the ATM terminal's role in initiating and processing the transaction.
- **`server.c`**: Handles the server-side logic to validate and approve or deny transactions.
- **`main.c`**: Coordinates the interaction between the card, terminal, and server.

## Future Enhancements

The current implementation is a foundational system that can be extended with the following features:

- **Refund functionality**: Add support for refund transactions to return funds to the user.
- **Pre-authorization support**: Implement a system to pre-authorize payments, ensuring that funds are available before proceeding with the transaction.
- **Security improvements**: Enhance the security of transactions by integrating encryption techniques and more advanced authentication methods.
- **Expanded transaction types**: Implement additional transaction types such as **VOID**, **PRE-AUTHORIZATION**, and **CASHBACK**.
