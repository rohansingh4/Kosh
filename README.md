# Kosh
## Kosh builds trust by removing possession. Your key is split across the decentralized fabric — no one owns it, yet only you can move your assets.

🌌 Kosh – The Keyless Blockchain Wallet

Kosh is a decentralized, keyless smart account wallet built for the next era of multi-chain adoption.
Designed for true security, simplicity, and scalability, Kosh eliminates traditional private key management by using threshold cryptography to sign transactions — making blockchain access seamless and safe for everyone.

🚀 Current Focus

First Chain: Hedera Hashgraph (MVP for Hackathon)
Next: Stellar, Solana, and EVM support (with easy network switching)
UI: Chromium Web Extension (Chrome, Brave, Edge)
🔑 Key Features

Keyless Authentication:
Powered by decentralized threshold signing — no private key is ever held by the user, wallet, or backend.
Secure PIN-Based Access:
Users authenticate using a simple 6-digit PIN. PIN verifies the session without exposing signing keys.
Multi-Chain Support (Upcoming):
Dynamic network switching between Hedera, Stellar, Solana, and EVM chains from a single wallet interface.
Balance Dashboard:
View native balances, tokens, and assets in real-time.
Fiat conversion integrated for better user experience.
Send & Receive Tokens:
Seamlessly transfer tokens across supported blockchains.
Stellar Trustline Management (Upcoming):
Automatically add Trustlines when users receive or want to hold new Stellar assets.
🛠️ How It Works

Threshold Signer (ICP-Canister Based):
Transaction signing is performed by a decentralized canister cluster.
Users initiate a transaction → signers coordinate → signature is threshold-generated → broadcast to the chain.
Transaction Release (Signer.rs Integration):
The wallet triggers the release function inside the threshold signer (Signer.rs) backend.
After user PIN authentication, the wallet securely requests a transaction release, signing and submitting the transaction without private key exposure.
Authentication:
A lightweight PIN vault manages session security.
Future upgrades: Biometric options, device binding.
📚 Tech Stack


Layer	Technology
Frontend	Chromium Web Extension (React / TypeScript)
Signer	Modified ICP Threshold Canisters (Ed25519/ECDSA)
Backend	Decentralized Signer Interaction Only
Chains	Hedera (MVP), Stellar (Upcoming), Solana, EVM Chains
APIs	Hedera Mirror Node, Stellar Horizon API, Chain RPCs
Auth	6-Digit PIN Code
🔮 Roadmap


Phase	Milestone
MVP	Hedera keyless wallet + Chrome extension + PIN auth
Phase 2	Stellar support + Trustlines
Phase 3	Solana + EVM multi-chain switching
Phase 4	Fiat on-ramp integrations
Phase 5	AI Transaction Agents (Risk scoring, auto-approvals)
Phase 6	Launch mobile app (iOS + Android)
📜 License

MIT License – Open source to empower decentralized access.

🤝 Contributing

We welcome contributors who believe in decentralization, security, and better UX in blockchain wallets!
Stay tuned for contribution guidelines after MVP release.

🧠 About the Name

"Kosh" means "treasury" or "repository" in Sanskrit — a trusted, secure place for your digital assets, built without the burden of traditional keys.

🔗 Follow the Journey

Kosh — Redefining Ownership. Without Keys.
Powered by Threshold Cryptography and Multi-Chain Vision.
