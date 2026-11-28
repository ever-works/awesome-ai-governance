## Overview

Etch provides a signed, offline-verifiable audit chain for AI agent decisions with portable per-agent identity across MCP client tools.

## Features

- Signed, offline-verifiable audit chain for AI agent decisions
- Portable per-agent identity across MCP client tools
- Hybrid Ed25519 + FIPS 205 SLH-DSA-SHA2-128f signing over Merkle-chained epochs
- Chain-integrity and signature verification offline
- Open-source reference verifier (world-model-mcp on PyPI, MIT)
- Hosted service extends with Sigstore Rekor + Bitcoin OpenTimestamps anchoring
- Key rotation, delegation grants and revocations
- Memory-per-identity across MCP client tools

## Pricing

Open-source reference verifier under MIT license. Hosted service under BSL 1.1 license. Repository: https://github.com/etch-systems/world-model-mcp