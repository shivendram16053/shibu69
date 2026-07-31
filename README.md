# Shivendra Mishra
Full-stack engineer building on Solana, Rust, and the web. I ship on-chain systems and developer tools, and I care most about correctness, code that holds up when real money is on the line. Based in India.

**Recent:** built Epoch, a non-custodial on-chain protocol on Solana. I built the core Anchor program (funds, vaults, settlement), a Rust backend and indexer, a real-time WebSocket layer, and the Next.js front end. Selections stay encrypted until lock via Arcium MPC, and all funds are controlled by program PDAs with conservation checks enforced on-chain. Live on mainnet, settled real user funds with no fund loss. Did a total of >3k$ volume on mainnet.

**Now:** going deeper on systems and low-level Rust and learning about AI/ML.

## Code

- [async-runtime](https://github.com/shibu0x/async-runtime). A minimal async runtime written from scratch in Rust, no dependencies beyond libc. Hand-built `Future`/`Waker` from a raw `RawWakerVTable`, a `kqueue` reactor with raw `unsafe` FFI to the kernel, timer futures, and an async TCP echo server. Blocks in `kevent` while idle, so it uses 0.0% CPU where a busy-poll loop burns a full core. Built to understand how async actually works at the syscall boundary.
- [veiled](https://github.com/shibu0x/veiled). Local-first terminal password manager in Rust. Argon2id key derivation, XChaCha20-Poly1305 authenticated encryption, explicit memory zeroization, no network dependency. Published on crates.io.
- [rsocket](https://github.com/shibu0x/rsocket). The WebSocket protocol implemented from raw TCP in Rust. Frame parsing and HTTP upgrade handling, built to understand the wire byte by byte.
- [order-matching-engine](https://github.com/shibu0x/order-matching-assingment). Matching engine in Rust: Redis-backed order queue, in-memory book with price-time priority, partial fills, real-time fills over WebSocket. Designed to avoid double-matching across API instances.
- [solx](https://github.com/shibu0x/solana-transaction-analyzer). Compute-unit profiler for Solana mainnet transactions. Groups execution by instruction and flags CU hotspots.

  
Merged contributions to Solana ecosystem repos: [Solana Foundation Explorer](https://github.com/solana-foundation/explorer/pull/640), [Surfpool](https://github.com/solana-foundation/surfpool/pull/418), and [wallet-ui](https://github.com/wallet-ui/wallet-ui/pull/341).

## Writing
- ["I Thought Encryption Was Enough. It Wasn't."](https://medium.com/@shibu0x/i-thought-encryption-was-enough-it-wasnt-99aa3ce4f5bc) on Medium.

  
## Contact
[shivendramishra.sm93@gmail.com](mailto:shivendramishra.sm93@gmail.com) · [shivendra.cc](https://shivendra.cc) · [X](https://x.com/shibu0x) · [LinkedIn](https://linkedin.com/in/shibu0x)

Looking for: full-stack, Solana, or system engineering roles.
