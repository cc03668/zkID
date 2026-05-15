# zkID Specifications

This directory hosts protocol specifications maintained alongside the zkID
reference implementation.

| # | Spec | Status | Summary |
| - | --- | --- | --- |
| 1 | `OPENAC` | _in review_ | Reserved for the OpenAC core protocol — under separate review. |
| 2 | [ZK-PROOF-OF-PERSONHOOD](./2-zk-proof-of-personhood/README.md) | raw | ZK-based one-time "verified person" status for online forums, with a deterministic nullifier. |
| 3 | [ZK-AGE-VERIFICATION](./3-zk-age-verification/README.md) | raw | Wallet-based age verification, profiled on top of OpenAC. Initial scope: Driver License for alcohol-purchase gating. |

## Change Process

Specs in this directory are governed by the
[1/COSS](https://github.com/privacy-ethereum/zkspecs/tree/main/specs/1)
change-control process. Status promotion (`raw` → `draft` → ...) follows the
COSS lifecycle.

## Editorial History

These specs were initially incubated in `privacy-ethereum/zkspecs` and moved
to this repository so they sit alongside the implementations they describe:

- `1/OPENAC` — to be added under a separate PR; previously drafted as `zkspecs#23` (and earlier `zkspecs#21`).
- `2/ZK-PROOF-OF-PERSONHOOD` — merged at `zkspecs` `specs/5` as `ZK-HUMAN-VERIFICATION`; updates carried over from `zkspecs#20`. Renamed during the move (the protocol concept is proof-of-personhood, not human verification).
- `3/ZK-AGE-VERIFICATION` — previously drafted as `zkspecs#19` (`ZK-AGE-ELIGIBILITY`). Renamed during the move (the protocol concept is age verification, not eligibility).
