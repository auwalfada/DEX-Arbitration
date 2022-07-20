# DEX-Arbitration

Build using the following commands:

git clone https://github.com/auwalfada/DEX-Arbitration.git
cd DEX-Arbitrage
mv .env-example.txt .env
npm install
npx hardhat run --network aurora .\scripts\deploy.js




Then add the arbContract deployment address to config/aurora.json edit the base assets and move the funds across to the the arbContract address.



Then to execute run:-



npx hardhat run --network aurora .\scripts\deploy.js


Finally to recover any funds use the script.



npx hardhat run --network aurora .\scripts\recover.js
