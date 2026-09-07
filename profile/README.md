# RefineID

Open-source software for electronic identification with Finnish FINEID cards.

RefineID provides native software for using Finnish electronic ID cards with modern operating systems and applications.

## Platforms

- **Core** — shared Rust implementation of FINEID card protocols and cryptographic operations
- **Android** — native Android implementation
- **Apple** — native macOS and iOS implementation
- **Java** — Java integration
- **Unix/Linux** — native implementation
- **Windows** — native smart-card middleware and Windows integration

The platform implementations share a common goal: making FINEID cards usable without proprietary middleware.

## What it supports

ReFineID is built around standard smart-card interfaces and the capabilities of FINEID cards, including:

- Authentication
- Electronic signatures
- Certificate discovery
- PIN management
- PACE and secure messaging
- RSA and ECDSA operations
- PC/SC smart-card readers
- Remote card use through your phone's NFC reader from a computer
