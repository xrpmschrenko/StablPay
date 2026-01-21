# StablPay

StablPay is a debit-initiated payment rail that enables businesses to accept customer payments via debit card while settling to the merchant in stablecoins (e.g., USDC), targeting high-volume B2B and platform payment flows.

## What StablPay Solves
- Card processing fees (often ~2–4%) that scale with revenue
- Settlement delays that restrict cash flow
- Chargeback exposure and admin overhead
- Stripe-style payment link dependency for high-ticket invoices
- Cross-border payment friction and FX costs

## High-Level Flow
1. Buyer completes payment via a StablPay link (debit card).
2. StablePay routes the payment through a debit-acceptance layer.
3. Merchant receives settlement in stablecoin (e.g., USDC) to their wallet/treasury.
4. Merchant can hold, convert, or pay vendors using stablecoin rails.

## Target Use Cases
- High-ticket B2B vendors and service providers
- Marketplaces and platforms handling vendor payouts
- SaaS and “Stripe-heavy” businesses using payment links for invoices
- Crypto-native businesses that prefer stablecoin settlement

## Status
Concept and initial assets are under active development.

## Author / Origin
Created by Mark Schrenko. This repository contains project materials and documentation related to the StablPay concept and build-out.
