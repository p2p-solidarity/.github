<a href="https://creds.id"><img src="./creds-banner.jpg" alt="creds.id — Cred you can verify. The verifiable link-in-bio." width="100%"></a>

<div align="center">

### We're Solid(ar)ity. We build **[creds.id](https://creds.id)** — the verifiable link-in-bio.

[![creds.id](https://img.shields.io/badge/creds.id-open_a_page-83537D?style=for-the-badge)](https://creds.id)
[![App Store](https://img.shields.io/badge/App_Store-iPhone-2F2F30?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/app/solid-ar-ity/id6752410250)
[![Google Play](https://img.shields.io/badge/Google_Play-Android-2F2F30?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=gg.solidarity.app)
[![X](https://img.shields.io/badge/@creds__id-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/creds_id)

</div>

## Anyone can make a link page. creds proves it's yours.

Claim `creds.id/@you`, add your links, share one page. The whole page is **signed by your own key** and **checked in the visitor's browser** — no install, no account — so anyone can confirm on the spot that the page and the accounts on it really belong to you.

- 🔏 **Signed end to end** — change one character and the signature no longer matches.
- 🔗 **Bound both ways** — your `@name` points to your account and the account points back. Only then does a link get a check; one-sided claims are marked *Declared*, never "verified".
- 🧪 **zkTLS social proofs** — prove you control an X or LinkedIn account from a real TLS session, without handing anyone your login. *(landing in creds 2.0)*
- 🛂 **Passport ZK** — tap your e-passport's NFC chip and prove *"over 18"* or *"citizen of …"* with a zero-knowledge proof. Nothing else leaves the phone.
- 🔑 **Passkeys, no passwords** — sign up with Apple or Google; your root key syncs between app and web as ciphertext the server can't open.
- ⚡ **Nostr-native** — every page comes with a `name@creds.id` NIP-05 identity.

> **Company-dies-still-works.** Your identity is a key on your device and your page verifies itself. If we vanished tomorrow, every creds page would still check out.

## Repositories

| | |
| --- | --- |
| 📱 **[creds-app](https://github.com/p2p-solidarity/creds-app)** | The iOS & Android app — verified profile, digital business card, NFC passport ZK, Nostr & Bluesky identity. Expo + React Native + Nitro Modules. |
| 🛰️ **[creds-api](https://github.com/p2p-solidarity/creds-api)** | The small, mostly-blind backend on Cloudflare Workers — passkey-wrapped vault sync, `name@creds.id` directory, encrypted inbox. Holds ciphertext, not keys. |
| 🛂 **[passport-noir](https://github.com/p2p-solidarity/passport-noir)** | Noir circuits for ICAO 9303 e-passports — RSA-SHA256 + data-group hash chain, selective disclosure, OpenAC linking. Swift Package with mopro bindings. |
| 🗺️ **[unmapped](https://github.com/p2p-solidarity/unmapped)** | From the lab: an endless, local-first open world an LLM writes as you explore, with P2P continents over WebRTC. |

<sub>Earlier work — Solid(ar)ity 1.x, WAMO ID, DID/DIDComm demos — lives on as `legacy-*` repos and at [docs.solidarity.gg](https://docs.solidarity.gg).</sub>

## Built with

![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Noir](https://img.shields.io/badge/Noir-ZK-1A1A1A)
![TLSNotary](https://img.shields.io/badge/TLSNotary-zkTLS-4B5563)
![Nostr](https://img.shields.io/badge/Nostr-8E44AD?logo=nostr&logoColor=white)
![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?logo=bluesky&logoColor=white)
![WebAuthn](https://img.shields.io/badge/Passkeys-WebAuthn_PRF-3423A6?logo=webauthn&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)

<div align="center">

**[creds.id](https://creds.id)** · **[solidarity.gg](https://solidarity.gg)** · gm@solidarity.gg

</div>
