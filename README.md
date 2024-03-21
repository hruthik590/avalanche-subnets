# ERC20 Token and Vault Contract

Hey there! 👋 Welcome to our ERC20 Token and Vault Contract project. Here's a simple guide to help you understand what these contracts are all about and how you can use them.

## What's Inside?

So, we have two main contracts in this repository:

### ERC20 Token Contract

Think of this as the magic factory that creates tokens. With this contract, you can:

- **Mint Tokens**: Create new tokens.
- **Transfer Tokens**: Send tokens from one account to another.
- **Approve Transfers**: Allow other people or contracts to transfer tokens on your behalf.
- **Check Balances**: See how many tokens are in an account.

### Vault Contract

Now, this is like a safe deposit box for your tokens. Here's what you can do with it:

- **Deposit Tokens**: Put your ERC20 tokens into the vault for safekeeping.
- **Withdraw Tokens**: Take your tokens out of the vault when you need them.
- **Control Access**: Decide who can deposit or withdraw tokens from the vault.

## How to Use

Alright, let's break it down into simple steps:

### ERC20 Token Contract

1. **Get it Ready**: Deploy this contract on the Ethereum blockchain.
2. **Create Tokens**: If you're the owner, you can make new tokens using the `mint` function.
3. **Send Tokens**: Transfer tokens to your friends or anyone you want using the `transfer` function.
4. **Allow Transfers**: Let others transfer tokens for you by approving them with the `approve` function.
5. **Check Balance**: Want to know how many tokens you have? Just use the `balanceOf` function.

### Vault Contract

1. **Set it Up**: Deploy this contract on the Ethereum blockchain.
2. **Store Tokens**: Put your ERC20 tokens into the vault using the `deposit` function.
3. **Retrieve Tokens**: When you need your tokens back, use the `withdraw` function.
4. **Manage Access**: Control who can deposit or withdraw tokens by adjusting permissions with the `setDepositPermission` and `setWithdrawPermission` functions.
