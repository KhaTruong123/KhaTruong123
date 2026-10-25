# Kha Truong (Kelvin)

I build stablecoin payments for the place where they meet real shops: the merchant QR codes people already scan every day in Southeast Asia and Latin America.

## What I am working on

- [emvco-qr-to-wallet-pay](https://github.com/KhaTruong123/emvco-qr-to-wallet-pay) reads merchant QR codes (VietQR, QRIS, PromptPay, QR Ph, Pix) and turns them into a CAIP-358 `wallet_pay` request a crypto wallet can act on. It is tested against 97 real payloads from public sources.
- [x402-vietqr](https://github.com/KhaTruong123/x402-vietqr) lets an AI agent pay a VietQR merchant in USDC over x402, with spend limits and single-use quotes. Stellar and Base testnet.
- [x402-stellar-smart-account-check](https://github.com/KhaTruong123/x402-stellar-smart-account-check) runs testnet checks on two open x402 fixes that let Stellar smart accounts with spending caps pay.
- [paymaster-usage-dashboard](https://github.com/KhaTruong123/paymaster-usage-dashboard) measures how often ERC-4337 paymasters pay gas for users, and in which token, on Ethereum and four L2s. Public data only, every number traces to a script.

## Before this

- Product manager at Hex Trust, a digital asset custodian (2023 to 2025).
- Technical business analyst at NAB, product roles at Kobiton and Starpunk.
- Started as a C# developer at ABB in the Czech Republic.

I write most of my code with an AI coding assistant and check the results myself: tests, testnet transactions and evidence files sit in each repo.
