# Crypto Recovery Phrase: Your Path Back to Your Crypto with WalletGen

**Lost your crypto recovery phrase?** **WalletGen** is a powerful, open-source tool designed to help you potentially find and recover access to your **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets**. This is more than just a wallet generator; it's a high-speed **crypto recovery phrase** tool built to help you get back your digital assets.

<!--
Meta description:
WalletGen helps you recover your crypto recovery phrase. Open-source tool for Bitcoin, Ethereum, and EVM chains. Brute-force seed recovery, wallet generation, balance checks. Get your crypto back now!
-->

## Quick Navigation
- [How It Works: Understanding WalletGen's Core Functionality](#how-it-works)
- [Why Choose WalletGen for Crypto Recovery Phrase Retrieval?](#why-walletgen)
- [Features: Key Advantages for Crypto Recovery](#features)
- [Download WalletGen: Begin Your Recovery Journey](#how-to-start)
- [Boost Your Search: Database Downloads and Optimization](#download-and-use-database-for-more-speed)
- [What Happens When a Wallet is Found? The Next Steps](#the-program-found-a-wallet--whats-next)
- [Recovering Your Bitcoin: Detailed Guide](#recovery-your-bitcoin-wallet)
- [My Finds: Real Results and Success Stories](#my-finds)
- [FAQ: Answers to Your Crypto Recovery Phrase Questions](#-frequently-asked-questions-faq)
- [Building WalletGen: Project Compilation Guide](#building-the-project)
- [Support the Project: Donate and Contribute](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="crypto recovery phrase" title="WalletGen wallet generator" height="460" src="/image/near.webp" />
</p>

⚠️ **Important Note**: WalletGen is designed for research and educational purposes. It should not be used for unauthorized access or malicious activities. Use it responsibly, and only on wallets that you own or have permission to access.

## How It Works

WalletGen utilizes industry-standard protocols such as [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for Bitcoin.  For EVM-based chains, it implements the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm.

The core function involves generating various potential wallet addresses, and then validating the balance of each one. This is done either via real-time balance checks through publicly accessible blockchain explorers, or by comparing the generated addresses against pre-existing databases of wallets that are known to have funds. WalletGen's C++ foundation provides for significantly faster processing speeds, a key advantage over Python-based options, and performance is primarily determined by your CPU and GPU.

## Why Choose WalletGen for Crypto Recovery Phrase Retrieval?

Why wait for a slow solution? **WalletGen** is engineered for speed and efficiency, especially when you need to find your crypto recovery phrase.  Written in C++ and optimized for multi-threaded CPU and GPU usage, it delivers up to **10x faster** performance compared to many alternatives. Whether you are working to recover lost wallets, validating private key ranges, or aiming to reclaim your own digital assets, WalletGen provides you with the speed and effectiveness needed for recovery.

## Features

-   **Cryptocurrency Wallet Generation**: WalletGen generates single wallets for Bitcoin, Ethereum, BNB, MATIC, and more.
-   **Balance Discovery with Brute-Force**: Use brute-force techniques to find existing wallets with a balance on the Bitcoin network and EVM chains.
-   **Algorithm Support**: Supports the Keccak256 algorithm for EVM wallets, and BIP39, BIP44, and Bech32 for Bitcoin.
-   **Database Integration for Speed**: Download databases to greatly improve search speed.
-   **High-Speed Operation**: WalletGen uses the power of your CPU and GPU to achieve optimal performance.
-   **Bitcoin Wallet Seed Phrase Recovery**: Recover your Bitcoin wallet with your mnemonic seed phrase.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/image/photo.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/image/item.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** employs a brute-force method to search for wallets with a balance.

### Bitcoin (BTC) Wallet Search:

*   Start by pressing key `3` in the menu, or run `start_search_btc.bat` to search Bitcoin wallets via the internet. Note: this method may take longer, because it checks balances via blockchain explorers in real-time.
*   For a faster approach, press key `6` to search using the database. This is much faster because it compares generated wallets against a database of known addresses and their balances.

### EVM Wallet Search (Ethereum, BNB, MATIC, etc.):

*   Press `5` or run `start_search_evm.bat` to search EVM wallets via the internet. Balances are checked in real-time with blockchain explorers.
*   Press `6` to search EVM wallets using the database. This is faster, using a known database.

### Performance Considerations:

*   Your hardware affects search speed, especially the graphics card (GPU). Running multiple instances (1 to 4) can help.

Databases improve search efficiency by eliminating the need for blockchain queries for every generated wallet.

## The Program Found a Wallet — What’s Next?

If WalletGen finds a wallet with a balance:
*   It will **Stop** immediately.
*   The wallet details will be **Displayed** in the console.
*   Data is **Saved** in the `found_wallets.txt` file.

### How to Access the Funds?

1.  Import the **mnemonic seed phrase** from the found wallet into a compatible crypto wallet (such as Metamask, Trust Wallet, or Electrum).
2.  You can then transfer the funds to your own wallet.

>  Consider donating a portion of the recovered balance as a thank you!

## Recovery Your Bitcoin Wallet

WalletGen can help you recover your Bitcoin wallet using the seed phrase. You can input the complete phrase or use wildcards to search for missing words.

### Process Description

#### Search for Missing Words:

If you have missing words, use an *. WalletGen searches all possible combinations to find your phrase.

#### Entering a Complete Seed Phrase:

If you have all 12 words, enter them. WalletGen then generates and checks addresses.

![recovery](/image/entity.webp)

### Important Recommendations

*   Seed phrases are always 12 words.
*   Use the * symbol only for missing words.
*   Searching for missing words takes time.
*   Upon recovery, data is saved.

## My Finds

![mywallet](/image/minimized.webp)

I've recovered two BTC wallets with balances. The first had 0.000032 BTC; the second, 0.0528 BTC (around $4800).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/image/shell.webp" />
</p>

### New Find 4/9/2025

After searching for a week, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my biggest find!

![image](/image/copy.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/image/show.webp)

## Building the Project

1.  Open the project file (`CryptoWalletGen.sln`) in Visual Studio or a compatible C++ compiler.
2.  Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
Download WalletGen on the [release download page](../../releases).

### ❓ Where can I download a database of known addresses?
Find the latest database on the [release page](../../releases).

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes, WalletGen can help recover lost Bitcoin wallets using brute-force seed generation and a known-address database.

### ❓ Is WalletGen a seed phrase generator?
Yes. WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No, you don't need an internet connection to search a database, as the balance information is already available.

### ❓ Can I find Ethereum wallets with balance?
Yes, WalletGen supports scanning for **Ethereum wallets with a balance** with brute-force and a database.

### ❓ Is WalletGen legal?
WalletGen is for **educational and research purposes only**. Use it *only* on wallets you own or are authorized to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are appreciated! If you have ideas, bugs, or want to contribute, submit a pull request.

## Donate

Consider donating a portion of the recovered balance as thanks.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)

Update:  11.06.2025 11:27:24 url is alive