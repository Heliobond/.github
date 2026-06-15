# Heliobond

**Own a piece of the energy transition, from one dollar.**

Heliobond is a transparent green-bond investment pool on [Stellar](https://stellar.org). Investors deposit USDC into a vault, receive shares in a pool of vetted renewable-energy projects, and an on-chain oracle scores each project for credit quality and green impact. Everything settles on-chain; anyone can verify it.

→ **Live demo:** [heliobond.vercel.app](https://heliobond.vercel.app)

## Repositories

| Repo | What it is |
|------|------------|
| [**contracts**](https://github.com/heliobond/contracts) | Soroban smart contracts (Rust) — the investment vault and project registry. The on-chain source of truth. |
| [**backend**](https://github.com/heliobond/backend) | Stellar indexer + REST API + the oracle that scores projects from IoT and satellite data. |
| [**frontend**](https://github.com/heliobond/frontend) | The investor app — Next.js, React, TypeScript. What you see at the demo. |

The three form a pipeline: contracts define the protocol, the backend indexes and enriches it, the frontend consumes both. Each repo builds and tests on its own.

## Contributing

We post scoped issues with acceptance criteria and file pointers so you can start without reverse-engineering the codebase. Look for the **good first issue** label in any repo, and read each repo's `CONTRIBUTING.md` first.

- New to the project? Start with a good-first-issue on the [frontend](https://github.com/heliobond/frontend/issues).
- Rust? The [contracts](https://github.com/heliobond/contracts/issues) need deploy tooling and tests.
- TypeScript and APIs? The [backend](https://github.com/heliobond/backend/issues) indexer and endpoints are wide open.

Built on Stellar. Licensed Apache-2.0.
