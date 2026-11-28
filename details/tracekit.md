## Overview

Tracekit is an MIT-licensed signer that decides each agent tool call before it runs (allow, deny, or wait for a person) and records the call, the decision and the result.

## Features

- Decides each agent tool call before it runs (allow, deny, or wait for a person)
- Records call, decision and result as Ed25519 signatures over RFC 8785 canonical JSON
- RFC 6962 Merkle log
- C2SP checkpoints for witnesses to cosign
- Each run exports as a .tkb bundle
- Independent Python and TypeScript verifiers check offline against pinned keys

## Pricing

Open source under the MIT license. Repository: https://github.com/Cygnux-Labs/Tracekit