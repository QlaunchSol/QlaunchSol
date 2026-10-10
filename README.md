<p align="center">
  <a href="https://qlaunch.xyz"><img src="banner.jpg" alt="Qlaunch" width="100%"></a>
</p>

### Qlaunch: a post-quantum launchpad on Solana

Every coin launched on [qlaunch.xyz](https://qlaunch.xyz) carries a **hash-based signature by its launcher**,
pinned into the coin's own metadata. Solana wallets rest on ed25519, which a large enough quantum computer
breaks; the attestation rests on SHA-256 alone, so it keeps proving who launched a coin after that happens.

- **Post-quantum identity:** 256 one-time WOTS+ keys under one Merkle root, derived in your browser from your wallet
- **Signed launches:** mint, name, ticker, image and description, signed with a fresh key, launched on pump.fun
- **Verify anything yourself:** in the browser on every coin page, or offline with a single-file Python script
- **Open source:** MIT licensed, built and run on one small server

[**Launch a coin**](https://qlaunch.xyz/launch) · [How it works](https://qlaunch.xyz/docs) · [Source](https://github.com/QlaunchSol/qlaunch) · [@QlaunchSol](https://x.com/QlaunchSol)

<sub>An attestation identifies who launched a coin. It is not an endorsement: do your own research.</sub>
