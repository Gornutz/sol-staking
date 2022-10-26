# Soft Staking for Crypto Cubs Contract


Three major steps for soft staking the green paw crypto cub NFTs.

1. First step is to add metadata onchain for the greenpaws mint NFTs. This is permission call could only be called by the person who has authority.
2. Transfer $eggplant token from our main wallet to vault eggplant wallet which will be used to distribute the tokens 
3. Claim Reward which checks owner and last claim date on the PDA of NFT mint and check check if the current signer and owner stored is same then user can claim the reward else it reset the timer and put the new owner as the current signer.


## Flow diagram

![eggplant drawio](https://user-images.githubusercontent.com/85603888/148696001-ca195b7f-a210-4636-b744-b0d420eac80c.png)


## Architecture
