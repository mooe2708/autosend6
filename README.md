# **Bulk-transfer-tea By ETRx Crypto ( DWYOR !!! )**
Send bulk transfer for Tea sepolia testnet

Fitur :
- Autosend Token Kalian secara random seharian ke user yang sudah KYC di tea ( Source database ada di bagian paling bawah )
- Pengiriman token di set secara random dari jam 8 pagi sampai 9 malam ( ada jam operasinya dan random )
- Batas transaksi per hari 101 - 150 ( karna direkomendasikan 101 Transaksi saja perhari )
- Ada delay per transaksi agar transaksi terlihat lebih natural

_**YOK DIMULAI**_

# Claim Faucet kalian
Claim disini : https://faucet-assam.tea.xyz/#/


# Deploy Token
Deploy Disini : https://sepolia.tea.xyz/address/0x847d23084C474E7a0010Da5Fa869b40b321C8D7b?tab=write_contract

**Notes : Sesudah deploy, copy contract address token kalian**

for termux user android

# Install NPM , dotenv sama axios dulu di Linux
```
```
```
npm install dotenv
```
```
npm install axios
```

# Install Dependencies

```
npm install ethers
```

Step by Step menggunakan botnya :
- Pastikan kalian sudah menyelesaikan semua hal diatas
- Buka file .env di editor text vps kalian
- Cari bagian PRIVATE_KEY_KALIAN dan isi dengan private key kalian
- Cari bagian CONTRACT_ADDRESS dan paste contract address token kalian
- Cari bagian RPC_URL dan CHAIN_ID , pastikan sesuai dengan RPC dan Chain ID terbaru Tea Sepolia
- Save file .env nya
- Jalankan scriptnya pake command ini :
```
  node teatransfer.js
```



