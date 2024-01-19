# Transactions API

Node.js application built with TypeScript and powered by the Knex query builder. This API is designed to streamline transaction management, offering a suite of features that empower users to create transactions, list all transactions, retrieve specific transaction details, and calculate the sum of all transaction values.

## Features

- Create a new transactions
- List all transactions
- List list only one transactio
- Sum of a user's transaction values

## Prerequisites

Make sure you have Node.js installed on your machine.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/marceloaraujo28/transactions-crud.git
   ```

2. Install dependencies:

   ```bash
   cd transactions-crud
   npm install
   ```

3. Run database migrations:

   ```bash
   npm run knex migrate:latest
   ```

4. Usage

   ```bash
   npm run dev
   ```

## ENDPOINTS

- `POST /transactions` - Create a new transaction.
- `GET /transactions` - Retrieve all transactions.
- `GET /transactions/:id` - Retrieve one transaction.
- `GET /transactions/summary` - Sum all transactions.

## Installation

API has been tested using Vitest. To run the tests, use the following command:

```bash
npm run test
```
