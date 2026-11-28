## Overview

SealedRun is a recorder that writes each agent step as a hybrid Ed25519 + ML-DSA-65 signed record in a hash chain.

## Features

- Records agent steps (LLM, MCP and A2A calls through its proxy, plus SDK self-reports)
- Hybrid Ed25519 + ML-DSA-65 signed records
- Hash chain
- Signing key held by the recorder rather than the agent
- Run heads anchored in RFC 3161 time-stamp authority
- Evidence bundles verify offline in Python or TypeScript

## Pricing

Open source under the Apache-2.0 license. Repository: https://github.com/sealedrun/sealedrun