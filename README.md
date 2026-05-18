# W3 Payroll Splitter

Composable crypto payroll workflow prototype built with:
- TypeScript
- viem
- Base
- Aave v3

## Workflow

1. Listen for incoming USDC payroll transfers
2. Split funds using basis-point rules
3. Route allocations to wallets or yield protocols
4. Deposit yield slice automatically into Aave

## Modules

- listener.ts
- splitter.ts
- yieldRouter.ts
- config.ts

## Composability

Each module exposes typed interfaces and can be replaced independently without rewriting the rest of the workflow.
