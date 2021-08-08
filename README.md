# decentralised-banking
A simulated decentralised banking system using blockchain. 

Since decentralised finance, also know as DeFi, is taking off, I'hv decided to make my own very decentralised bank. DeFi uses cryptocurrency (namely Bitcoin and Ethereum) and blockhain technology to manage financial transactions. DeFi aims to democratize finance by replacing centralized institutions with peer-to-peer relationships. In this simulated DeFi bank, you'll be able to interact with the decentralised bank, capable of handling traditional financial transactions. Just one of the many things that DeFi are capable with nowadays. 
These traditional financial transaction functions include:
- Deposit Ethereum and earn interests
- Withdrawal of Ethereum deposit plus interest
- Borrowing a native token currency called 'Decentralised Bank Currency' or 'DBC' using Ethereum as collateral
- Paying off your initial loan receiving back your collateral net fees.


# Dependencies

You will need need a couple of things before you can interact with the decentralised bank. These include:
- Node.js https://nodejs.org/en/download/
- Truffle https://www.trufflesuite.com/truffle (follow instructions using terminal)
- Ganache https://www.trufflesuite.com/ganache
- Metmask https://metamask.io/download

# Opening the Project

- Start Ganache and Quickstart a workspace. Ganache ables us to interact with the blockchain and run the simulation. If you want to know more about Ganache, visit their website, here: https://www.trufflesuite.com/ganache.
- Open Terminal of your choice. Check if you have properly downloaded the Node.js by tpying "node -v". Check if tou have properly downloaded truffle by typing "truffle version"
- Open the project up. If you're cloning the project tpye in "git clone https://github.com/chengwhk/decentralised-banking.git". If you're downloading the project into a zip file, you will need to open the project up manually in terminal.
- Type "npm install" into terminal to download additional files for project. 
- Run the project by typing "npm run start" into terminal. This should open a localhost website.
- You will now need to connect metamask to the network. Read here if unsure: https://metamask.zendesk.com/hc/en-us/articles/360043227612-How-to-add-custom-Network-RPC-and-or-Block-Explorer. Network Name: Ganache, New RPC URL: (listed at the top of Ganache under RPC Server), chain ID: (isted at the top of Ganache under Network ID), Symbol: DBC, and Block Explorer URL can be left empty.
- And you're done! You should be able to interact with the decentralised bank through the website and play around with its functions.

<img width="1440" alt="Screen Shot 2021-08-08 at 8 32 50 pm" src="https://user-images.githubusercontent.com/87778179/128629403-29aa59f9-4c4a-4184-8559-d01e50cb28dd.png">


