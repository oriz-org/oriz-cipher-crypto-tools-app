# Oriz Cipher — Cryptography Tools

Encryption, decryption, hashing, and key-generation utilities for everyday cryptography work. Everything runs client-side in your browser via the WebCrypto API — no payloads ever hit a server.

**Live:** https://crypto.oriz.in

## Brand

**Cipher** is the encryption product in the Oriz family. The name signals what the app does: turn plaintext into ciphertext (and back), generate keys, derive hashes, sign and verify.

## Stack

- **Astro 6** — static-first site framework, islands architecture
- **React 19** — interactive islands for the tool UIs
- **Tailwind v4** — utility-first styling
- **WebCrypto API** — native browser cryptography (no third-party crypto libs in the hot path)

All crypto operations are performed locally in the user's browser. Nothing is uploaded.

## License

Source-available, all rights reserved. See [LICENSE](./LICENSE).
