# How to use

```sh
# Install dependencies
yarn
# Run command to get list of staked NFTs of a given user
ts-node cli.ts check_staked_nfts -w <user_wallet>
# For example
ts-node cli.ts check_staked_nfts -w BjW98JuAaX1515hdXzBNweoq2nVQVaUNWyJpK1rWMAax
# Note: RPC can be updated in .env file

# Get the details of the mint
ts-node cli.ts check_staked_mint -m <mint_of_nft>
ts-node cli.ts check_staked_mint -m 58uW28uH5XX9Y8GJY6eYqZM51rYoXR6DbWPsLqKnrPXh
```
