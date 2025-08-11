[README.md](https://github.com/user-attachments/files/21721589/README.md)
# BRICS PLUS STABLE (BPS)

Proyecto de moneda estable multicolar respaldada por reservas reales, gobernada por una DAO tricameral.

## Estructura
bps-project/
│
├── .gitignore
├── README.md
├── LICENSE
├── LICENSE-DOCUMENTOS.md
├── Anchor.toml
│
├── CODE/
│   ├── dapp-bps/
│   │   ├── Cargo.toml
│   │   └── src/
│   │       └── main.rs
│   ├── dex-bps/
│   │   ├── Cargo.toml
│   │   └── src/
│   │       └── main.rs
│   └── programs/
│       ├── dapp-bps/
│       │   ├── Cargo.toml
│       │   ├── Xargo.toml
│       │   └── src/
│       │       └── lib.rs
│       └── dex-bps/
│           ├── Cargo.toml
│           ├── Xargo.toml
│           └── src/
│               └── lib.rs
│
├── ANALYTICS/
│   ├── Cargo.toml
│   └── src/
│       └── main.rs
│
├── DOCUMENTOS/
│   ├── WhitePaper_BPS_ES.md
│   ├── WhitePaper_BPS_EN.md
│   ├── Acta_Aprobacion_CEO_2025.md
│   ├── Reglamento_DAO_Politica.md
│   ├── Reglamento_DAO_Civil.md
│   └── Estatutos_Fundacion_BPS.md
│
├── WEBSITE/
│   ├── index.html
│   ├── css/
│   ├── js/
│   │   ├── dapp.js
│   │   └── dex.js
│   └── wallet-adapter/
│
├── tests/
│   ├── dapp_bps.ts
│   └── dex_bps.ts
│
├── .anchor/
│   └── localnet/
│
└── wallets/
    ├── mint/
    │   └── mint-keypair.json
    ├── fundacion/
    │   └── fundacion-keypair.json
    ├── dao-politica/
    │   └── dao-politica-keypair.json
    ├── dao-civil/
    │   └── dao-civil-keypair.json
    ├── validator/
    │   └── identity.json
    └── ceo/
        └── ceo-keypair.json

## Tecnología
- Solana (Rust)
- Anchor Framework
- SPL Tokens
- Web3.js

## Licencias
- Código: AGPL-3.0
- Documentos: CC BY-NC-SA 4.0
