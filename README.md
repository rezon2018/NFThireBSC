# NFT tokens renting platform

##  Description

dApps allows NFT's token holders to temporarily lease their tokens and gain interest from it.
On the other hand, it allows renting the same NFT's by paying for use plus collateral.

Current stage: **beta**.

## 🏹 Deployed client dApps on Netlify
- Binance Smart Chain: [https://dreamy-bell-874b39.netlify.app/](https://dreamy-bell-874b39.netlify.app/)

## 🏠 Smart Contract addresses across Binance Smart Chain networks

- Binance smart chain testnet [0x0263BbFDff5F04C8323681205B3a608d5359Ff66](https://testnet.bscscan.com/address/0x0263BbFDff5F04C8323681205B3a608d5359Ff66)

```
Note: Smart Contract calls are proxied to main Smart Contract so calls destination is the Proxy Smart Contract itself.
```

## ✅ To do
- [ ] Client dApp: show lent data
- [ ] Client dApp: show borrowed data
- [ ] Client dApp borrower: call DAI approve method
- [ ] Client dApp borrower: call borrow method
- [ ] Client dApp lender: call ERC-721 approve method
- [ ] Client dApp lender: call ERC-721 lend set method
- [ ] Set duration for lendings
- [ ] Deploy Smart Contract to mainnet
- [ ] Verify Smart Contract in mainnet Etherscan
- [ ] Put lenders addresses with lent tokens somwehere outside of smart contract (UX improvement) – (note: solved with thegraph.com)
- [ ] Show message when collateral was already taken on expired lend
- [ ] Show success or error messages on each transaction
- [ ] Email reminders for borrower or lender
- [ ] Allow edit lend




