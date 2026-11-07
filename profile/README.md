# KTON: liquid staking on TON

![KTON Banner](./image/banner.png)

## Overview

KTON is an audited, open-source liquid staking protocol on The Open Network (TON). Stake Gram (the coin of the TON network, formerly Toncoin) and receive KTON, a transferable token that keeps earning validator rewards. To get Gram back, redeem KTON through the pool. The team has run public TON staking pools since 2021; KTON V2 launched in 2025.

## Key Facts

- **Start from 1 Gram.** KTON is minted at the pool's rate; the rate rises as the pool earns.
- **Fees:** 16% of the staking rewards (the APY shown in the app is already net of it); no deposit fee.
- **Withdrawals:** free at the pool's next rotation (up to about 36 hours), or at once for 0.2% when the pool has enough unlent Gram. Redeem through the pool rather than selling on a DEX, where the price has been well below the pool's rate.
- **Governance:** pool settings and admin actions need 3 of 4 multisig signatures.
- **Audit:** TonBit, 2025 ([report](https://github.com/KTON-IO/liquid-staking-contract/blob/v2/KTON-Final-Audit-Report.pdf)).
- **KTON Premium (PKTON)** is a separate pool for vesting contracts.

## Repositories

| Repository | What it is |
|---|---|
| [liquid-staking-contract](https://github.com/KTON-IO/liquid-staking-contract) | The pool, minter and payout contracts |
| [KTON-SDK](https://github.com/KTON-IO/KTON-SDK) | TypeScript SDK, on npm as [`kton-sdk`](https://www.npmjs.com/package/kton-sdk) |
| [kton-skills](https://github.com/KTON-IO/kton-skills) | Agent skill for staking and unstaking KTON, signed in your own wallet |
| [vesting](https://github.com/KTON-IO/vesting) | The [vesting.kton.io](https://vesting.kton.io/) front end |
| [awesome-kton](https://github.com/KTON-IO/awesome-kton) | Curated list of KTON resources |

## Quick Links

- **App**: [app.kton.io](https://app.kton.io/)
- **Website**: [kton.io](https://kton.io/)
- **Documentation**: [docs.kton.io](https://docs.kton.io/)
- **KTON Premium**: [premium.kton.io](https://premium.kton.io/)
- **Telegram Mini App**: [@ktonio_bot](https://t.me/ktonio_bot)
- **Telegram**: [group](https://t.me/kton_group) · [channel](https://t.me/kton_channel)
- **X**: [@kton_io](https://x.com/kton_io)
- **DefiLlama**: [defillama.com/protocol/kton](https://defillama.com/protocol/kton)
- **CoinGecko**: [coingecko.com/en/coins/kton-staked-kton](https://www.coingecko.com/en/coins/kton-staked-kton)
