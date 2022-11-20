# [fweb3.xyz](https://fweb3.xyz)

## Update Nov-2022

### There were some security issues with our initial prototype. This project started as a hackathon in feb 2022 and many lessons were learned. All of us were learning when this game was created (kinda the whole point of the game) and since lots of code has been updated. Bots began spamming our faucet system and had to be shut down for improvements. These improvements are underway and a post will go out to the entire community with the roadmap very soon. We hope to have v2 launched in time for next febuary and another hackathon! Thanks to everyone for their patience in the discord and everywhere.

![Statements](https://img.shields.io/badge/statements-87.5%25-yellow.svg?style=flat&logo=jest)
![Branches](https://img.shields.io/badge/branches-60%25-red.svg?style=flat&logo=jest)
![Functions](https://img.shields.io/badge/functions-100%25-brightgreen.svg?style=flat&logo=jest)
![Lines](https://img.shields.io/badge/lines-87.5%25-yellow.svg?style=flat&logo=jest)

Contributions are more than welcome.

---

## Game Contracts

All of our contracts are open and available!
You will find all of them [here](https://github.com/fweb3/contracts)

- Fweb3 Token [0x4a14ac36667b574b08443a15093e417db909d7a3](https://polygonscan.com/address/0x4a14ac36667b574b08443a15093e417db909d7a3)
- Fweb3 Trophy NFT [0x2a0493dee4f4b5e4b595326f0e73645f6f493923](https://polygonscan.com/address/0x2a0493dee4f4b5e4b595326f0e73645f6f493923)

## Local Development

```bash
# Install dependencies
yarn install

# Copy .env.example to .env.local and fill out vars
cp .env.example .env.local

# Run dev server
yarn dev

# Testing...
yarn test

# watch mode
yarn test:watch

# cypress (start app first)
yarn e2e

# cypress standalone
yarn e2e:run

# Linting
yarn lint

# Formatting
yarn prettier
```

## Debugging with devtools

Supports using either the VS Code debugger or Chrome DevTools.
See official Next.js docs: https://nextjs.org/docs/advanced-features/debugging
You can use `http://localhost:3000?wallet=<address>` to test using a specific wallet address

## Depolyment

Deployment is handled automatically to vercel on a merge to master.
All checks must pass before a merge can occur. Preview deploys are created on opening a PR.

## Tooling & Documentation

- [Typescript](https://www.typescriptlang.org/docs)
- [Nextjs](https://nextjs.org/docs)
- [Vercel](https://vercel.com/docs?redirected=1)
- [PolygonScan](https://polygonscan.com/apis)
- [Cypress](https://cypress.io)
- [Jest](https://jestjs.io/docs/getting-started)
- [Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

## Join our [discord](https://discord.gg/SztqpYpY) for more information.
