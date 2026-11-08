# XentFi — Stablecoin Infrastructure for Global Payments

**One API for wallets, checkout, fiat on/off-ramps, agent payments, treasury operations and liquidity.**

[Website](https://app.xentfi.com) · [Developer Docs](https://docs.xentfi.com) · [API Reference](https://docs.xentfi.com/api-reference) · [Dashboard](https://dash.xentfi.com) · [GitHub](https://github.com/xentfi)

## Overview

XentFi is a stablecoin infrastructure platform built in Africa for African payment corridors, with an architecture designed to expand into global markets. It gives fintechs, payment companies, platforms and developers a unified integration layer for building stablecoin-powered financial products without having to assemble and maintain separate blockchain, wallet and payment integrations.

XentFi is designed around a single API and operating layer spanning:

- **Wallet-as-a-Service (WaaS):** create and manage master wallets and customer deposit addresses.
- **Checkout and payment links:** accept digital-asset payments through hosted checkout flows.
- **On-ramps and off-ramps:** connect fiat payment flows with stablecoin settlement.
- **Agent infrastructure:** provision and manage agents, agent wallets and agent payment activity.
- **Treasury and settlement automation:** configure rules to consolidate and distribute funds.
- **Transfers and swaps:** move assets across supported networks and execute supported swaps.
- **Order-book and liquidity services:** provide access to trading and liquidity workflows as part of the broader XentFi platform.

The goal is to make stablecoin infrastructure usable as a practical payment and treasury layer—not just a way to hold digital assets.

## Why XentFi

Businesses building across African and emerging-market payment corridors often need to connect multiple providers, blockchain networks, wallets, compliance processes and settlement systems. Each additional integration increases engineering and operational overhead.

XentFi abstracts much of this complexity behind a consistent API, dashboard, webhook and wallet model. Teams can build customer-facing products and backend financial workflows on the same infrastructure, then extend those workflows to additional networks and corridors.

**Market approach:** Africa-first, with planned and ongoing expansion toward corridors including the United States, Brazil and Mexico. Availability of individual fiat routes depends on supported providers, local requirements and production enablement.

## Stellar integration

XentFi is live on Stellar mainnet, with Stellar on-ramp and off-ramp flows integrated into its stablecoin payment infrastructure.

This connects Stellar-based stablecoin settlement to real-world payment use cases: moving value into digital dollars, using stablecoins in payment workflows, and converting back toward local fiat rails. Stellar is part of XentFi's production network strategy—not a standalone proof-of-concept integration.

The integration is intended to make Stellar available through the same broader XentFi developer experience used for wallets, payments and treasury operations.


## Traction

- **$10M+ in cumulative transaction volume** across XentFi's supported infrastructure.
- **Mainnet operations:** XentFi is live on mainnet.
- **Stellar:** mainnet integration with both on-ramp and off-ramp flows.
- **Multi-chain infrastructure:** the documentation describes support across major networks including Ethereum, Base, Polygon, Arbitrum, Optimism, BNB Chain and Solana.


## Developer resources

| Resource | Link |
|---|---|
| Main website | https://app.xentfi.com |
| Documentation | https://docs.xentfi.com |
| Quickstart | https://docs.xentfi.com/quickstart |
| API reference | https://docs.xentfi.com/api-reference |
| Authentication | https://docs.xentfi.com/api-reference/authentication |
| API errors | https://docs.xentfi.com/api-reference/errors |
| Development environment | https://docs.xentfi.com/development |
| Sample projects | https://docs.xentfi.com/projects |
| Release notes | https://docs.xentfi.com/release-notes/changelog |
| Dashboard | https://dash.xentfi.com |
| GitHub | https://github.com/xentfi |
| Support | mailto:support@xentfi.com |

### Product documentation

- [Master wallets](https://docs.xentfi.com/essentials/master-wallets)
- [Customer deposit addresses](https://docs.xentfi.com/essentials/addresses)
- [Payment links and checkout](https://docs.xentfi.com/essentials/payment-links)
- [Automated settlement](https://docs.xentfi.com/essentials/auto-settlement)
- [Transfers and swaps](https://docs.xentfi.com/essentials/transfers-swaps)
- [AML and compliance](https://docs.xentfi.com/essentials/aml-compliance)
- [Webhooks](https://docs.xentfi.com/essentials/webhooks)
- [Security](https://docs.xentfi.com/essentials/security)
- [Asset recovery](https://docs.xentfi.com/essentials/asset-recovery)

### SDKs and packages

Public developer packages:

- **Agent / MCP SDK:** [`@xentfi/mcp-sdk`](https://www.npmjs.com/package/@xentfi/mcp-sdk) — `npm install @xentfi/mcp-sdk`. Adds policy-governed XentFi wallet and payment tools to MCP-compatible agent runtimes. [Source repository](https://github.com/xentfi/xentfi-mcp-server).
- **x402 payment facilitator:** [`@xentfi/x402-facilitator`](https://www.npmjs.com/package/@xentfi/x402-facilitator) — `npm install @xentfi/x402-facilitator`. TypeScript package for XentFi's x402 payment facilitator.

The API documentation also contains SDK setup examples. Refer to the [developer documentation](https://docs.xentfi.com/development) for the currently documented language options and integration instructions.


## Getting started

1. Create an account through the [XentFi dashboard](https://dash.xentfi.com).
2. Generate sandbox API credentials.
3. Follow the [Quickstart](https://docs.xentfi.com/quickstart) to authenticate and make your first API request.
4. Build and test with the SDKs or REST API.
5. Configure webhooks, validate your integration in the supported test environment, and request production access when ready.

The API uses organization credentials in request headers. Refer to the [authentication guide](https://docs.xentfi.com/api-reference/authentication) for the current credential and header requirements. Never commit API keys or secrets to source control.

## Built for Africa, designed for global corridors

XentFi's initial focus is solving payment and settlement infrastructure challenges across African markets. Its multi-chain and API-first architecture is designed to support expansion into additional corridors—including the US, Brazil and Mexico—through local payment integrations, liquidity partners and regulatory-compliant operating models.

This approach positions XentFi as shared infrastructure for fintechs and businesses that need to move between local payment systems and global stablecoin networks.

## Contact

- Website: https://app.xentfi.com
- Documentation: https://docs.xentfi.com
- Developer support: dev@xentfi.com
- General support: support@xentfi.com
- X: https://x.com/xentfi
- GitHub: https://github.com/xentfi
- Linkedin: https://linkedin.com/company/xentfi

---

