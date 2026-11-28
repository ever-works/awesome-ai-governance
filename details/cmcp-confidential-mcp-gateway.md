## Overview

cMCP is a Confidential MCP Gateway that checks tool calls against Cedar policy inside a TEE.

## Features

- Gateway between agent and MCP tools
- Cedar policy checks inside TEE
- Policy bundle recorded in chip's signed report before code runs
- Signing key never leaves protected area
- Software mode available (no hardware protection)
- Signed receipt (GatewayClaim) per tool call
- Supports TPM, AMD SEV-SNP, Intel TDX attestation
- Developer preview

## Deployment

Self-hosted

## License

Not specified