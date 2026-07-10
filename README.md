# GUD Stable Token

![Gauss Gang](assets/gauss-gang.png)

Solidity implementation of the GUD stable-token component for the Gauss ecosystem. The project uses Hardhat for compilation, tests, and local development.

## Contents

- `contracts/` — token and supporting Solidity contracts
- `flattenedContracts/` — flattened sources for review or verification workflows
- `test/` — automated tests

## Development

```bash
npm install
npx hardhat compile
npx hardhat test
```

## Security and deployment

Treat this code as security-sensitive financial infrastructure. Keep deployment configuration outside the repository and obtain an appropriate review before production use.
