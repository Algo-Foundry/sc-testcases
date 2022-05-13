# Test cases assignment


## Setup instructions

### 1. Install packages
```
yarn install
```

### 2. Update environement variables
1. Copy `.env.example` to `.env`.
2. Add account information (address and mnemonic) into the `.env` file.

#### Get account mnemonic
To get the mnemonic of an account in goal CLI, replace the `<account address>` run this command in your sandbox directory.
```
./sandbox goal account export -a <account address>
```

### 3. Use .env file
```
source .env
```
