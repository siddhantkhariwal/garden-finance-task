**Garden-Finance-Task on testnet**

Key Features
- IMPROVED UI/UXFeatures an improved user interface for a better overall experience.
- Multi-Chain Environment: Leverage a robust environment for seamless multi-chain interactions.
- Swap Functionality: Easily execute swaps from WBTC to BTC.
- Transaction Tracking: Monitor and display the most recent transactions.
- Garden SDK Utilization: Integrates the Garden SDK to perform swaps efficiently.

**Garden-Finance-Task on localnet**

For localnet in store.tsx -> orderbook replace url value with - http://localhost:8080
- Ex -  const orderbook = await Orderbook.init({
        url: "http://localhost:8080",
        signer: signer,
        opts: {
          // eslint-disable-next-line @typescript-eslint/no-explicit-any
          domain: (window as any).location.host,
          store: localStorage,
        },
      });


STEPS - 
1. Install Merry

curl https://get.merry.dev | bash

2. Start Merry

merry go

3. Fund Your EVM Address

merry faucet --to <EVM Address>

4. Install Dependencies 

npm install / bun install

5. Start the development server

npm run dev/ bun run dev

Project will look like this - 
![Screenshot](public/Screenshot%202024-07-25%20at%207.44.52%20PM.png)
