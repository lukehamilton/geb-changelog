# RAI Protocol Changes

## May 2021

### 17th- 21thof May
- Deploy the RAI/ETH Uniswap V2 saviour at `0xA9402De5ce3F1E03Be28871b914F77A4dd5e4364` version [47c6f0d](https://github.com/reflexer-labs/geb-safe-saviours/blob/47c6f0d5e219e5b19985795d8d8d408b1f645022/src/saviours/NativeUnderlyingUniswapV2SafeSaviour.sol)
- Deploy the Uniswap v2 saviour Liquidity manager at `0x5D447CbE791E2F4c11d82f1F3E901DEc76f61763` version [47c6f0d](https://github.com/reflexer-labs/geb-safe-saviours/blob/47c6f0d5e219e5b19985795d8d8d408b1f645022/src/integrations/uniswap/liquidity-managers/UniswapV2LiquidityManager.sol)
- Deploy saviour proxy action at `0x8bcb98529ACf08580F23e35912566143E3f9B370` version [75436cc](https://github.com/reflexer-labs/geb-proxy-actions/blob/75436cc05be5c8ed79f3cbd440cf796ca5e36ce6/src/GebProxySaviourActions.sol)
- Whitelist new saviour `0xA9402De5ce3F1E03Be28871b914F77A4dd5e4364` in liquidation engine
- Add new saviour `0xA9402De5ce3F1E03Be28871b914F77A4dd5e4364` to saviour registry

### 10th - 16th of May
- Deploy new MEDIANIZER_RAI at `0xB7E06D980b17f168CE1b57189F8aa34D0254FEe2` version [52d8881](https://github.com/reflexer-labs/geb-uniswap-median/blob/52d888128261cff39d5420999cb11ba195d562f0/src/UniswapConsecutiveSlotsPriceFeedMedianizer.sol)
- Deploy new MEDIANIZER_RAI_REWARDS_RELAYER: `0xe8063b122bef35d6723e33dbb3446092877c6855` version [470fc8c](https://github.com/reflexer-labs/geb-treasury-reimbursement/blob/470fc8cf01f9764e354f589ada98f15b32708c0c/src/relayer/IncreasingRewardRelayer.sol)
- Deploy new DEBT_POPPER_REWARDS: `0xe1d5181F0DD039aA4f695d4939d682C4cF874086` version [299e84b](https://github.com/reflexer-labs/geb-debt-popper-rewards/blob/299e84b472525bdd24c5d0d6896a9732f6025554/src/DebtPopperRewards.sol)
- Deploy new MEDIANIZER_ETH_REWARDS_RELAYER: `0xdD2e7750ebF07BB8Be147e712D5f8deDEE052fde` version [470fc8c](https://github.com/reflexer-labs/geb-treasury-reimbursement/blob/470fc8cf01f9764e354f589ada98f15b32708c0c/src/relayer/IncreasingRewardRelayer.sol)
