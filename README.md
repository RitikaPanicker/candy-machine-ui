# #
User Interface Configuration Guide for Candy Machine

Welcome to the comprehensive guide on configuring the user interface (UI) for your Candy Machine to facilitate a smooth NFT minting experience using the SPL token you've generated. Users will be interacting with their Phantom wallets throughout the minting process.

Before you begin, ensure you have the following prerequisites in place:

A properly configured Candy Machine with specific details in its config.json file, including price, quantity, symbol, seller fee basis points, SPL token account, SPL token, go-live date, and creator details.

A designated Phantom wallet for minting.

A newly created SPL token.

Follow the steps below to set up the UI:

1. SPL Token Setup:
If not done already, create the SPL token by following the guidelines in Lesson Three, and make note of the SPL token's address.

2. Update Candy Machine Config:
Edit the config.json file of your Candy Machine and update the following fields:

splTokenAccount: Replace with the address of the created SPL token account.
splToken: Replace with the SPL token address.
3. UI Configuration:
Refer to the "Quick Node: Set Up a Minting Site" tutorial for instructions on creating a UI for your Candy Machine. This UI will empower users to connect their Phantom wallets and mint NFTs using the SPL token as payment.

4. Adjust Minting Logic:
Within your SPL project's minting logic (as per Lesson Three), make the necessary modifications to mint NFTs to the Phantom wallet address or adapt the transfer function to deliver minted NFTs to your Phantom wallet.

5. Testing:
Thoroughly test the entire setup by transferring or minting your SPL token to a Phantom account. Utilize the UI to mint NFTs, ensuring a seamless process for users paying in the designated SPL tocken
