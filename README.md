# METACRAFTERS-ETH-AVAX-MODULE-4

Transaction Hash: 0x08a309Bb97F5b8AFD2a8970c62569615638A838B
SnowTrace Link: https://testnet.snowtrace.io/address/0x08a309Bb97F5b8AFD2a8970c62569615638A838B

# Introduction
Create a ERC20 token and deploy it on the Avalanche network for Degen Gaming. The smart contract should have the following functionality:

- Minting new tokens: The platform should be able to create new tokens and distribute them to players as rewards. Only the owner can mint tokens.
- Transferring tokens: Players should be able to transfer their tokens to others.
- Redeeming tokens: Players should be able to redeem their tokens for items in the in-game store.
- Checking token balance: Players should be able to check their token balance at any time.
- Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.

# Contract Details
- Token Name: Degen Token
- Symbol: DGN
- Decimals: 18
- Totalsupply
- Owner's address

  # Events performed
  1. Minting new Tokens: It allows the owner to create new tokens.
  2. Burning Tokens: This function allows to burn the specific amount of their own tokens.
  3. Approval: It enables the token holder to grant permission to another address to spend a specific amount of their tokens.
  4. Transferring Tokens: It allows the token holder to send the tokens to another address.
  5. TransferFrom: Allows an approved address to transfer tokens from the sender's address to the recipient address.
  6. Redeemption: It allows the token holder to redeem items using their own tokens.
  7. ClaimReward: Received in game rewards will be transfered to the the wallet linked.
  8. InGamePurchase: To purchase items available in game like pass, skins etc.

The transfer function allows the sender to transfer tokens to another address to. It takes two parameters: to, the address of the recipient, and amount, the amount of tokens to be transferred. The require statement checks whether the amount to be transferred is less than or equal to the balance of the msg.sender. If the condition evaluates to false, meaning the sender does not have enough tokens, the function will revert with the error message "Not enough balance to Transfer!". The _transfer function is called to transfer the tokens from the msg.sender to the to address. It moves amount tokens from the msg.sender to to. The function returns true to indicate that the transfer was successful.


![image](https://github.com/ShivamGupta92/METACRAFTERS-ETH-AVAX-MODULE-4/assets/70855458/1b26719a-4e76-4136-8a10-17d72a7d6cce)
![image](https://github.com/ShivamGupta92/METACRAFTERS-ETH-AVAX-MODULE-4/assets/70855458/0b270359-64db-4fe8-bc74-baaf1b4da476)

# Author
SHIVAM GUPTA

