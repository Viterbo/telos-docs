---
sidebar_position: 2
hide_table_of_contents: true
---

# Set Up a Wallet

## What is a Wallet?

A blockchain wallet (e-wallet, crypto wallet or signer) is a tool that you use to interact with a blockchain network. It is a digital wallet that allows users to store and manage their digital money (tokens or cryptocurrencies). A blockchain wallet allows the transfer of cryptocurrencies between users, and it has the ability to convert them back into a user’s local currency.

A wallet can either be a device or application that stores a collection of cryptographic keys and can be used to send, receive, and track ownership of cryptocurrencies. Wallets can take many forms. A wallet might be a directory or file in your computer's file system, a piece of paper, or a specialized device called a _hardware wallet_. There are also various smartphone apps and computer programs that provide a user-friendly way to create and manage wallets.

### Types of Wallets

Wallets can be categorized into two types: custodial and non-custodial wallets.

- **Custodial Wallets**: These are managed by a third-party company. They are like a storage facility where you keep your valuables. They require less responsibility from your end, but are dependent on the third party. For instance, if the storage facility was compromised, your assets could be at risk.
- **Non-Custodial Wallets**: These wallets are not managed by a third party. They are akin to a safe in your house where you store your valuables. They give you full control over your assets, but also demand extra care and responsibility from you.

Non-custodial wallets further include software and hardware wallets. Software wallets live on your computer or internet browser, making them convenient for quick transactions. Hardware wallets, on the other hand, are physical devices that offer secure storage for long-term, albeit less convenient for frequent transactions.

When interacting with the Telos blockchain, your choice of wallet software for safely storing and utilizing your tokens is one of the most critical decisions that you can make. Important factors include security, usability, and integrations for dApps and trading. Your wallet is your doorway into the Telos Blockchain network.

## Install a Wallet

:::tip
Make a dev wallet for development purposes. This will reduce risk in short and long term.
:::

Currently, some of the more commonly used wallets are the following

:::caution
Please note that this is not an endorsement of any of the following wallets
:::

* [Metamask](https://metamask.io)&#x20;
* [Wallet connect](https://walletconnect.com/)
  
## Add Telos EVM to Your Wallet 

There are multiple ways to add the Telos EVM Network to your wallet.

### Automatically on Teloscan

Head over to [Teloscan Explorer](https://teloscan.io)

- Click Sign In

<img
    src={require('/static/img/sign_in_teloscan.png').default}
    alt="Teloscan"
    width="90%"
    height="automatic"
/>

- Click connect with MetaMask. Follow the prompts to add the Telos EVM Network to your wallet

<img
    src={require('/static/img/Connect_Metamask.png').default}
    alt="TeloscanMetamask"
    width="90%"
    height="automatic"
/>

### Connect via Chainlist

Visit [Chainlist](https://chainlist.org/?search=Telos) click Connect Wallet

<img
    src={require('/static/img/chainlist.PNG').default}
    alt="Chainlist"
    width="80%"
    height="automatic"
/>

Once your wallet is connected, click Add to Metamask. Follow the prompts to add the Telos EVM to your wallet

<img
    src={require('/static/img/chainlist3.PNG').default}
    alt="ChainlistAdd"
    width="80%"
    height="automatic"
/>

### Manual Setup 

Open up Metamask, click the network type, and click Add Network

<img
    src={require('/static/img/metamask.PNG').default}
    alt="MetamaskManual"
    width="35%"
    height="automatic"
    style={{marginRight: '5em'}}
/>

<img
    src={require('/static/img/metamask1.PNG').default}
    alt="MetamaskManual"
    width="35%"
    height="automatic"
/>

Scroll down and click Add a network manually

<img
  src={require('/static/img/metamask2.PNG').default}
  alt="Example 2"
  width="75%"
  height="automatic"
/>

Input the Telos EVM Network information (mainnet and testnet info below) and click save

<img
  src={require('/static/img/metamask3.PNG').default}
  alt="Example 2"
  width="60%"
  height="automatic"
/>

#### **Telos Mainnet Info:**

* **Network Name**: Telos Mainnet 
* **New RPC URL**: [https://mainnet.telos.net/evm](https://mainnet.telos.net/evm)
* **ChainID**: `40`
* **Symbol**: `TLOS`
* **Explorer**: [https://www.teloscan.io/](https://www.teloscan.io/)

#### **Telos Testnet Settings:**

* **Network Name**: Telos Testnet
* **New RPC URL**: [https://testnet.telos.net/evm](https://testnet.telos.net/evm)
* **ChainID**: `41`
* **Symbol**: `TLOS`
* **Explorer**: [https://testnet.teloscan.io](https://testnet.teloscan.io/)

## Telos Websockets

* **Testnet : wss://testnet.telos.net/evm**

* **Mainnet: wss://mainnet.telos.net/evm**

