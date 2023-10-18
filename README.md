# Dawn AI user guide
Dawn AI is a crypto personal assistant who can answer your questions about Ethereum, send transactions, interact with protocols and read information from the chain.

You can interact with it pressing one of the icons, such as "Lend", or just typing out a command or question. Dawn supports several chains: Optimism, Mainnet, Base, Arbitrum, Polygon, Zora.

## What Dawn AI can help you with

### Find out what's happening on-chain
#### Balances and net worth
- what is my eth balance?
- what is the dai balance of tomwaite.eth?

#### NFTs
- what is the most valuable NFT of koide.eth?
- how many NFTs does vitalik.eth have?
- what NFTs do I own?

#### Portfolio
- what is the net worth of tomwaite.eth?
- what is the price of aave?
- what are the borrow rates on aave?
- what tokens do I have?

#### Trending
- what tokens are trending?
- what NFTs are trending?
- what is the latest news in crypto?
- what are the top yields in crypto?

### Sending transactions and interacting on-chain
Dawn will give you a simulation output of what a proposed transaction will do on-chain if you were to sign it. Make sure to review to check it looks good! Once you've sent a transaction, you'll get an "Open Etherscan" link where you can see that the magic really worked!

### Sending assets
- send $5 of eth to koide.eth
- send 0.2 aave to 0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045

### Swaps
- swap 1 dai for usdc
- swap $10 of aave for weth

Swaps are routed in the most efficient path possible using 1inch.

### Loans
- what loans do I have?
- lend 10 USDC
- withdraw 5 USDC
- lend $100 of eth

Loans are created via Aave. 

### Switch chain
Want to switch chain from the default of Optimism? Tell Dawn AI!

- switch chain to base

### Bridge
- bridge $5 of eth to base
- bridge 20.5 dai to mainnet


## Easter eggs
I wonder what an AI agents favourite food is, its favourite hobby, what is its favourite wallet? Has AI figured out the meaning to life?

## Limitations and future development
To interact with Ethereum, or find out about what's happening on-chain, Dawn AI has to have a so-called "tool" built and made available to it. These tools are small pieces of software that tell the AI agent how to call an API, how to query some data, how to interact with a smart contract etc. Dawn can't interact with a protocol that it does not yet have a tool for. It currently can only do one activity per prompt - complex multi-step commands like "bridge $100 to base and then mint a pudgy penguins NFT" won't work.

Is there a protocol you want supported, or an action you want to take that Dawn can't currently do? Let us know!
