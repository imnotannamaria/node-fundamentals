# Financial API with Node & Express

## Project requirements

- create an account
- get the customer's bank statement
- make a deposit
- make a withdrawal
- fetch the customer's bank statement by date
- update customer account data
- get customer account data
- delete an account

## Business rules

- It is not possible to register an account with an existing CPF
- Unable to deposit to a non-existing account
- Unable to fetch statement on non-existing account
- Unable to withdraw from a non-existing account
- Unable to delete a non-existing account
- It is not possible to withdraw when the balance is insufficient

## Deploy

To deploy this project, run

```bash
  yarn
```

```bash
  yarn dev
```