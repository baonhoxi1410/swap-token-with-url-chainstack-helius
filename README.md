



Download the latest Raydium mainnet.json (it's a ~500 MB file):
wget https://api.raydium.io/v2/sdk/liquidity/mainnet.json



chạy ts-node src/trimMainnet.ts để tạo ra file trimmed_mainnet.json sẽ nhanh hơn lấy thẳng vào mainnet.json bị nặng lâu



thêm vào file .env
RPC_URL=YOUR_RPC_URL
(https://mainnet.helius-rpc.com/?api-key=d4b119f1-783d-426a-954b-3578f35a03a3) helius
(https://solana-mainnet.core.chainstack.com/0a8169787b22dc1793e46d976488b17e) chainstack

WALLET_PRIVATE_KEY=YOUR_PRIVATE_KEY



chạy lệnh yarn swap

