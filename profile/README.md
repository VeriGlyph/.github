![VeriGlyph: Verifiable, On-Chain Registration Certificates](https://github.com/VeriGlyph/media/blob/8ace91d004c913c5b13b4e5aaa45aab125653524/header.png)

# VeriGlyph: Verifiable, On-Chain Registration Certificates

VeriGlyph is a suite of open-source tooling to support the generation, publication, and verification of on-chain
registration certificates published to the Cardano blockchain. 

Currently, only support for CIP-88 Token Registration Certificates exists but the intent is to support other standards
as they emerge and are developed within the ecosystem.

## Components

### [Nexus](https://github.com/VeriGlyph/nexus)

VeriGlyph: Nexus is the hub for generating, managing, and publishing your registration certificates to the blockchain.

### [Sentinel](https://github.com/VeriGlyph/sentinel)

VeriGlyph: Sentinel is the chain indexer and validator to observe, validate, and record published certificates and store
their contained data for future use.