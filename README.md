# README

Welcome to the `coins-data` repository. This repository contains data and images used to build the coin pages on https://komodoplatform.com . The data is organized by language and the images are categorized based on their usage on the webpage.

## Repository Structure

```
├── data
│   ├── en (English data)
│   │   ├── BTC.json
│   │   └── ETH.json
│   └── ru (Russian data)
│       ├── BTC.json
│       └── ETH.json
├── images
│   ├── hero (Hero images for each coin)
│   │   ├── BTC.png
│   │   └── ETH.png
│   └── socialCard (Images displayed by social sites when the coin page's url is shared)
│       ├── BTC.png
│       └── ETH.png
```

## Data Example

```json
{
  "ticker": "BTC",
  "name": "Bitcoin",
  "slug": "bitcoin",
  "title": "Komodo Wallet — Bitcoin Wallet and DEX",
  "metaDescription": "Komodo Wallet is a non-custodial Bitcoin wallet and decentralized exchange rolled into one app. HODL and trade Bitcoin on one app.",
  "description": "The Bitcoin protocol launched on January 3, 2009, by an anonymous person, or group of people, using the alias Satoshi Nakamoto. Bitcoin is the world's first blockchain network, and its native currency — BTC — is the world's first cryptocurrency to gain widespread utility.<br/>According to Satoshi Nakamoto, the purpose of Bitcoin is to provide \"online payments to be sent directly from one party to another without going through a financial institution.\"",
  "blogUrl": ""
}
```

## Image Examples

### Hero Image

![BTC Hero Image](./images/hero/BTC.png)

### Social Card Image

![BTC social card Image](./images/socialCard/BTC.png)
