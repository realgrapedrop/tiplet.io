# Tiplet Tester Guide

Thanks for helping test Tiplet! This walks you through trying it end to end on the **XRP Ledger
Testnet**, so **no real money is involved** — the coins are free test tokens.

It takes about 10–15 minutes. You'll create a wallet, switch it to the test network, grab some
free test funds, and send your first tip.

**Need help at any step?** DM **[@realgrapedrop](https://x.com/realgrapedrop)** on X.

---

## 1. Install Xaman and create a wallet

Tiplet works with the **Xaman** wallet (formerly XUMM).

1. Install **Xaman** from the [App Store](https://apps.apple.com/app/xaman/id1492302343) or
   [Google Play](https://play.google.com/store/apps/details?id=com.xrpllabs.xumm).
2. Open it and create a new account. **Write down your secret recovery numbers and keep them
   safe** — even on testnet, get in the habit.

## 2. Switch Xaman to Testnet

By default Xaman is on Mainnet (real money). Point it at the test network:

1. In Xaman, go to **Settings → Advanced**.
2. Turn on **Developer mode** (or **Advanced mode**) if it isn't already.
3. Open **Node** and choose a **Testnet** node (anything under the Testnet section).

Your wallet is now on Testnet. You can switch back to Mainnet the same way later.

## 3. Find your wallet address

You'll need your address (it starts with **`r`**) to receive test funds and tips.

- On the Xaman home screen, tap your account. Your **`r...` address** is shown there, with a
  button to copy or share it.

## 4. Get free test XRP

This activates your wallet.

1. Go to the **[Bithomp Testnet faucet](https://test.bithomp.com/faucet)**.
2. Paste your **`r...` address**.
3. Set **Currency** to **XRP**. Leave **Destination tag** empty.
4. Submit. You'll get up to 100 test XRP (you can come back once a day for more).

That's enough to start tipping in XRP. If you want to tip in **RLUSD** too, do step 5.

## 5. (Optional) Get test RLUSD

RLUSD is a dollar-pegged stablecoin. To hold it, your wallet first needs an **RLUSD trustline**
(a one-time opt-in). **Do this before requesting RLUSD** — otherwise the faucet payment will
bounce.

1. **Add the RLUSD trustline.** DM **[@realgrapedrop](https://x.com/realgrapedrop)** and you'll
   get a one-tap link that adds it in Xaman — just open it and sign.
2. Once the trustline is set, go back to the **[Bithomp faucet](https://test.bithomp.com/faucet)**,
   paste your address, set **Currency** to **RLUSD**, and submit.

## 6. Open Tiplet and send a tip

1. On your phone, open **[testnet.tiplet.io](https://testnet.tiplet.io)**.
2. Tap **Connect wallet** and approve the connection in Xaman.
3. Fill in the tip:
   - **Send to:** a recipient's `r...` address. **Not your own** — you can't tip yourself. Need
     someone to tip? DM **[@realgrapedrop](https://x.com/realgrapedrop)** for a demo address, or
     use a friend's testnet address.
   - **Amount:** pick XRP or RLUSD and an amount.
   - **Note:** a short thank-you. This seeds your collectible's art.
   - Pick an art **style** and **category**.
4. Tap **Review**, then confirm. Xaman will pop up a request — **sign it**.
5. Watch the success screen reveal your **Tiplet Collectible**. Open **History** to see it, and
   tap **View Bithomp** to see the minted NFT on the explorer.

That's the whole flow. 🎉

## 7. (Optional) Open Tiplet inside Xaman

Tiplet can also run as an **xApp** directly inside Xaman. While it's in testing, I have to add
your device before you can open it:

1. In Xaman, go to **Settings → Advanced** and find your **Device Identifier** — copy it.
2. DM your Device Identifier to **[@realgrapedrop](https://x.com/realgrapedrop)** on X.
3. Once you're added, you'll be able to open Tiplet from inside Xaman.

(You don't need this to test — the web app at **[testnet.tiplet.io](https://testnet.tiplet.io)**
works for everyone. The xApp is just a nicer in-wallet experience.)

---

## Troubleshooting

- **"Submission failed — temREDUNDANT" / "you can't tip your own wallet."** You entered your own
  address as the recipient. Use a different address.
- **RLUSD tip fails, or faucet RLUSD never arrives.** The RLUSD trustline isn't set yet (step 5),
  or the recipient doesn't have one. Set the trustline first, or send **XRP** instead — any
  activated wallet can receive XRP.
- **Nothing happens / wrong network.** Make sure Xaman is on a **Testnet** node (step 2).
- **Wallet won't connect.** Refresh **[testnet.tiplet.io](https://testnet.tiplet.io)** and try
  Connect again.

Still stuck? DM **[@realgrapedrop](https://x.com/realgrapedrop)** on X — happy to help.
