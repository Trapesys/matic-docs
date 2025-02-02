---
id: wallet-overview
title:  Wallet Overview
sidebar_label: Overview
description: "Wallet features."
keywords: 
  - docs
  - polygon
  - id
  - wallet
image: https://matic.network/banners/matic-network-16x9.png
---

import useBaseUrl from '@docusaurus/useBaseUrl';

A digital wallet is a software that can hold and manage user's Claims. Based on the principles of Self-Sovereign Identity (SSI) and cryptography, a wallet helps its Holder share data with others without exposing any other sensitive private information stored on it. Only the wallet holder has the right to decide which information to share with other entities and what needs to remain private. 

The Polygon ID Wallet is a *Privacy by Default* wallet that helps protect a user's identity (and other metadata) by using zero-knowledge protocols. The wallet interacts with an Issuer to fetch claims and with a Verifier for sharing zkProofs based on these claims.

The Polygon ID app will be a reference implementation that other web3 wallets will be able to use as a starting point for integrating the Wallet SDK into their apps so that they can become compatible with the Polygon ID ecosystem.

<div align="center">
<img src={useBaseUrl("img/polygonid/polygon-id-reference-app.png" )} alt="Polygon ID app as a reference implementation" width="500" align="center" />
</div>

## Features of the Polygon ID Wallet

The Polygon ID Wallet supports the following features:

- Privacy by design and Self-sovereignty: The user is in full control of his/her identity data and exchanges Claims with other identities without the need of an intermediary or centralized authority. 
- Open and Permissionless. 
- Fetching, storing, and managing claims.
- Generating cost-optimized zero-knowledge proofs for claim verification.
- Communication with Issuer and Verifier.
- Identity recovery using seed phrase.

<br></br>

Download links for the PolygonID Wallet App:

- For Android: <a href="https://play.google.com/store/apps/details?id=com.polygonid.wallet" target="_blank">Polygon ID on Google Play</a>
- For iOS: <a href="https://apps.apple.com/us/app/polygon-id/id1629870183" target="_blank">Polygon ID on the App Store</a>

<br></br>

:::note 
Our tutorials on ***Wallet SDK*** will be published soon. The SDK will allow you to integrate the identity wallet core functionalities into your own app.
:::






