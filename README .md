# Ethereum vs Solana vs TON Comparison

Practical module assignment comparing the three networks across key metrics.

## Comparison

| Metric                  | Ethereum                                      | Solana                                              | TON                                              |
|-------------------------|-----------------------------------------------|-----------------------------------------------------|--------------------------------------------------|
| **Consensus Mechanism** | Proof of Stake (Gasper)                      | Proof of History + Tower BFT (Alpenglow/Votor incoming) | Proof of Stake (Catchain 2.0)                   |
| **TPS**                 | ~20–30 real L1 TPS (much higher via L2s)     | Theoretical 65,000+; real non-vote often 1,000–3,000+ | Theoretical 100,000+ (stress-tested); scales via dynamic sharding |
| **Average Gas Fee**     | Currently very low (~0.1–0.2 gwei; simple transfers often under $0.05) | Extremely low (typically under $0.001)             | Extremely low (basic transfers ~$0.0005 or less) |
| **Programming Language**| Solidity, Vyper                              | Rust (primary), C, Anchor framework                | FunC, Tact, Tolk (Tolk preferred for new projects) |

## Notes

- **Ethereum** prioritizes security and decentralization. Most user activity has moved to Layer 2s for lower fees and higher throughput.
- **Solana** uses parallel execution (Sealevel) and is optimized for high throughput and low fees. An upgrade (Alpenglow) is activating to further improve finality.
- **TON** uses an actor model with asynchronous messaging and dynamic sharding, designed to scale with large user bases (notably Telegram integration).

---

Assignment submission for Raven Network / Flock practical module.