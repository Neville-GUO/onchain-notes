# Orbinum (ORB)

> **State**: points only — allocation size published, conversion mechanism published
> **Last verified**: 2026-10-23

## What it is

A privacy-focused L1 that pairs ZK shielded pools with EVM compatibility. The pitch is standard Solidity tooling with shielded state as a first-class feature.

## Token status

No token has launched. A community allocation has been published in writing: **20,000,000 ORB** for the Genesis Community season, distributed proportionally against earned credits.

This is one of the clearer setups available: the pool size is fixed, the distribution is proportional, and the snapshot rule is stated. The conversion *rate* is still unknown because it depends on total credits at snapshot.

## Rules as written

- Credits earned during Season 1 convert proportionally into a share of the 20M ORB pool
- **Snapshot is taken exactly 14 days before mainnet** — not on a calendar date announced in advance
- Credits earned after the snapshot do not count
- Unlock: full at distribution (no vesting cliff on the community portion)

Daily loop:

1. Shield a balance
2. Transfer within the shielded pool
3. Unshield
4. Disclosure quest

Plus a streak: consecutive weeks add +50, each additional week +25, capped at 500.

## Deadlines

| Date | Event |
|---|---|
| ~Q4 2026 | Mainnet target; snapshot lands 14 days before |
| Ongoing | Weekly streak must be maintained or it resets |

## Notes

The 14-day-before-mainnet snapshot rule is unusual and it matters: **there is no announced date to work backwards from**. A campaign can end the moment mainnet date is announced, with two weeks' notice. Anyone treating this as "I'll push at the end" will lose the tail of their activity.

Google login became mandatory in October 2026. Accounts registered with a wallet only needed to perform a wallet sync afterwards — an easy thing to miss and an easy thing to never check again.

## Risk notes

- Founder identities are not publicly verified. This is the main transparency deduction.
- Credit conversion is proportional, so an influx of participants dilutes everyone. Late-stage farming has a worse rate than early farming by construction.
- The public sale terms published in October 2026 implied a fully diluted valuation around $25M, which is useful context for sizing the community pool in real terms.

## Sources

- Official project documentation and public sale terms
- Season 1 rules as published by the project
