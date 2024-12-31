# Deploy a Contract with Ethers.js + Hardhat
Alchemy tutorial link: https://university.alchemy.com/course/ethereum/md/617ac022c7cf0100041ddf8e
</br> My work: https://sepolia.etherscan.io/address/0x565673Ae78660036e3fd408c0c2C98eB6ee65e7A

</br> 🚀 Update:
- mitigate from Göerli to Sepolia
- modify dependencies and `deploy.js` for latest hardhat and ethers

</br> 🔄 Workflow:
- `npm install`
- `touch .env` and record your alchemy api url and private key
- `npx hardhat compile`
- `npx hardhat run scripts/deploy.js --network sepolia`
