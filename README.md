# Mainnet-Forking

Mainnet forking is particularly useful when you're developing applications that interact with existing protocols or when you need to test complex DeFi interactions without the cost and risk of using the actual mainnet.

node setup: npx hardhat node --fork "https://eth-mainnet.g.alchemy.com/v2/6NBASdqVHgOteJgLfzu-9--wDvGH6Awy"
run script: npx hardhat run scripts/mainnet-forking.ts --network localhost
