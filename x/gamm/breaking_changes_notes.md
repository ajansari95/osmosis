# List of every known client breaking change in current AMM refactor

## Queries

* PoolAssetsQuery
  * ???
* QuerySpotPrice
  * The `withswapfee` param is now removed. If this was needed for anything, please flag it. Its mainly removed due to not having a clear use, and a better query can probably be crafted for.
  * Rename TokenInDenom to QuoteAssetDenom
  * Rename TokenOutDenom to BaseAssetDenom

## Messages

* Rename JoinPool -> JoinPoolNoSwap
* JoinPoolSwapExternAmountIn
  * Replace sdk.Coin w/ sdk.Coins

## Events

## Gas numbers
