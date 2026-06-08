# terraform-iac-drift-register

Board-readable Kinetic Gain proof repo for **Terraform** signal coverage.

## Signal lane

- Vendor / platform: Terraform
- Domain: Infrastructure as Code
- Executive question: Where is this system creating exposure, waste, or decision latency?
- Proof posture: synthetic fixture, deterministic CLI, static report, and CI gate.

## Why this exists

IaC drift, module ownership, policy evidence, and environment change pressure.

This repo is intentionally small and explicit. It gives the portfolio atlas a named, inspectable proof artifact for Terraform without needing another hosted subdomain or exposing live customer data.

## Local run

`ash
npm install
npm test
npm run build
npm run demo
`

## Security posture

- No secrets, tokens, customer records, or live API calls.
- Fixture data is synthetic and stored in ixtures/sample.json.
- Output is deterministic and safe for public portfolio inspection.
