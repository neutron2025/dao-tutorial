mkdir My-Projects

cd My-Projects
npx @startertemp/nextjs-hardhat DAO-Tutorial

cd backend
创建文件 FakeNFTMarketplace.sol

npx hardhat compile

创建 CryptoDevsDAO.sol

创建 .env文件
配置两个参数
QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"

PRIVATE_KEY="add-the-private-key-here"

修改 backend/scripts/deploy.js

在backend目录下创建文件 constants.js

修改配置文件 hardhat.config.js

npx hardhat compile
部署 npx hardhat run scripts/deploy.js
-----
cd frontend
npm run dev
在目录 my-app/public/cryptodevs 下面存放0.svg
修改 frontend/styles/Home.modules.css

在frontend 下面创建 constants.js
配置参数 
export const CRYPTODEVS_DAO_CONTRACT_ADDRESS = "";
export const CRYPTODEVS_NFT_CONTRACT_ADDRESS = "";

export const CRYPTODEVS_DAO_ABI = [];
export const CRYPTODEVS_NFT_ABI = [];

配置 frontend/pages/index.js

运行npm run dev



Whitelist Contract Address: 0x9Fe8Db6A9998493377A20505661a99953D9Bae24

Crypto Devs Contract Address: 0x4E1Ee20d8286B9998EBBDd8dcfa0085515fcD3CA

Crypto Devs Token Contract Address: 0x81c871F0081Bac42F5E8bB1F445C05aF49CD913F

FakeNFTMarketplace deployed to:  0xbFc480b89F05b4f227e1EC8a45A446bB2241cDCB
CryptoDevsDAO deployed to:  0xdc24bEA2AB82223C17a91D3BC0da9896F57C98bD


Exchange Contract Address: 0x9b1e6332Ab1c26ab35B64B4a3f9052963A451327
