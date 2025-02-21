<!--
changelogUtils.file is auto-generated using the monorepo-scripts package. Don't edit directly.
Edit the package's CHANGELOG.json file only.
-->

CHANGELOG

## v6.2.1 - _March 24, 2021_

    * Dependencies updated

## v6.2.0 - _January 5, 2021_

    * Add `DowncastErrorCodes.ValueTooLargeToDowncastToUint128` (#16)

## v6.1.1 - _December 2, 2020_

    * Dependencies updated

## v6.1.0 - _October 29, 2020_

    * Restore revert error definitions :-( (#4)

## v6.0.0 - _October 29, 2020_

    * Dropped revert error definitions (#3)

## v5.6.4 - _October 28, 2020_

    * Dependencies updated

## v5.6.3 - _October 21, 2020_

    * Dependencies updated

## v5.6.2 - _October 21, 2020_

    * Dependencies updated

## v5.6.1 - _October 20, 2020_

    * Dependencies updated

## v5.6.0 - _October 20, 2020_

    * Added support for nested rich revert decoding (#2668)
    * Add EP flavor of `IllegalReentrancyError`. (#2657)
    * Added LiquidityProviderFeature errors (#2691)
    * Added abi encoder support for uint80 lol (#2728)

## v5.5.1 - _July 15, 2020_

    * Dependencies updated

## v5.5.0 - _June 24, 2020_

    * Add `ZeroExRevertErrors` (#2540)
    * Print full revert error in stack traces. (#2540)
    * `ZeroExRevertErrors.Migrate` -> `ZeroExRevertErrors.Ownable` (#2564)
    * `instanceof Array` => `Array.isArray` (#2567)
    * Add more `ZeroExRevertErrors` (#2545)
    * Add more `ZeroExRevertErrors` (#2576)
    * Update `ZeroExRevertErrors` (#2597)
    * Add more revert errors to `ZeroExRevertErrors` (#2610)

## v5.4.1 - _February 25, 2020_

    * Fix extra space in `provider.send` signature (#2428)

## v5.4.0 - _February 8, 2020_

    * Add `toTokenUnitAmount` and `fromTokenUnitAmount` (#2462)
    * Add `hexUtils.isHex` (#2462)
    * Accept `Buffer` type in `hexUtils.toHex()` (#2462)

## v5.3.0 - _February 6, 2020_

    * Added Broker, MixinWethUtils revert errors (#2455)
    * Moved LibAssetDataTransfer revert errors into their own file (#2455)

## v5.2.0 - _January 22, 2020_

    * Allow for strict decoding of return values. (#2433)

## v5.1.2 - _January 6, 2020_

    * Dependencies updated

## v5.1.1 - _December 17, 2019_

    * Dependencies updated

## v5.1.0 - _December 9, 2019_

    * Added hex_utils (#2373)

## v5.0.0 - _December 2, 2019_

    * Re-export all `RevertErrors` (#2362)
    * Removed exports AuthorizableRevertErrors, LibAddressArrayRevertErrors, LibBytesRevertErrors, OwnableRevertErrors, ReentrancyGuardRevertErrors and SafeMathRevertErrors (#2321)
    * Decode `Parity` revert errors (#2341)
    * Update BigNumber version to ~9.0.0 (#2342)
    * Consolidated FixedMathRevertErrors (#2255)
    * Changed provider_utils.providerUtils.getChainIdAsync() to invoke RPC method eth_chainId rather than net_version (#2270)
    * Allow for array types in `RevertError`s. (#2075)
    * Have Ganache `Error` -> `RevertError` coercion fail if it can't look up the selector. (#2109)
    * Add `LibFixedMath` `RevertError` types. (#2109)
    * Add `RawRevertError` `RevertError` type. (#2109)
    * Make `RevertError.decode()` optionally return a `RawRevertError` if the selector is unknown. (#2109)
    * Rename `length` field of `AuthorizableRevertErrors.IndexOutOfBoundsError` type to `len`. (#2109)

## v4.6.0-beta.3 - _December 2, 2019_

    * Re-export all `RevertErrors` (#2362)

## v4.6.0-beta.2 - _November 17, 2019_

    * Removed exports AuthorizableRevertErrors, LibAddressArrayRevertErrors, LibBytesRevertErrors, OwnableRevertErrors, ReentrancyGuardRevertErrors and SafeMathRevertErrors (#2321)
    * Decode `Parity` revert errors (#2341)
    * Update BigNumber version to ~9.0.0 (#2342)

## v4.6.0-beta.1 - _November 7, 2019_

    * Consolidated FixedMathRevertErrors (#2255)
    * Changed provider_utils.providerUtils.getChainIdAsync() to invoke RPC method eth_chainId rather than net_version (#2270)

## v4.6.0-beta.0 - _October 3, 2019_

    * Allow for array types in `RevertError`s. (#2075)
    * Have Ganache `Error` -> `RevertError` coercion fail if it can't look up the selector. (#2109)
    * Add `LibFixedMath` `RevertError` types. (#2109)
    * Add `RawRevertError` `RevertError` type. (#2109)
    * Make `RevertError.decode()` optionally return a `RawRevertError` if the selector is unknown. (#2109)
    * Rename `length` field of `AuthorizableRevertErrors.IndexOutOfBoundsError` type to `len`. (#2109)

## v4.5.2 - _September 17, 2019_

    * Dependencies updated

## v4.5.1 - _September 3, 2019_

    * Dependencies updated

## v4.5.0 - _August 8, 2019_

    * Add `SafeMathRevertErrors.SafeMathErrorCodes.Uint256DivisionByZero` (#2031)
    * Updated to include `strictDecode` for decoding method arguments (#2018)
    * Throw exception when trying to decode beyond boundaries of calldata (#2018)

## v4.4.2 - _July 31, 2019_

    * Dependencies updated

## v4.4.1 - _July 24, 2019_

    * Dependencies updated

## v4.4.0 - _July 13, 2019_

    * Add function deleteNestedProperty (#1842)
    * Add `getChainIdAsync()` to `providerUtils` (#1742)
    * More robust normalization of `uint256` types in `sign_typed_data_utils` (#1742)
    * Add `RevertError`, `StringRevertError`, `AnyRevertError` types and associated utilities (#1761)
    * Update `RevertError` construction to produce a readable `Error` message (#1819)
    * Add `Error` -> `RevertError` functions (#1819)
    * Add `toStringTag` symbol to `RevertError` (#1885)

## v4.3.3 - _May 10, 2019_

    * Fixed spelling error in ABI Encoder error message (#1808)

## v4.3.2 - _Invalid date_

    * Support for ABI encoding multibyte strings (fixes issue #1723) (#1806)

## v4.3.1 - _April 11, 2019_

    * Dependencies updated

## v4.3.0 - _March 21, 2019_

    * Added `startProviderEngine` to `providerUtils`. Preventing excess block polling (#1695)

## v4.2.3 - _March 20, 2019_

    * Dependencies updated

## v4.2.2 - _March 1, 2019_

    * Fix issue where process is not defined in browser context (#1660)

## v4.2.1 - _February 26, 2019_

    * Dependencies updated

## v4.2.0 - _February 25, 2019_

    * Export providerUtils which helps standardize all supported provider interfaces into the ZeroExProvider interface (#1627)
    * Add `logUtils.table` and `logUtils.header` (#1638)

## v4.1.0 - _February 9, 2019_

    * Added method decoding to AbiDecoder (#1569)

## v4.0.4 - _Invalid date_

    * Cleaner signature parsing (#1592)

## v4.0.3 - _February 7, 2019_

    * Dependencies updated

## v4.0.2 - _February 6, 2019_

    * ABI Decode NULL for all data types (#1587)

## v4.0.1 - _February 5, 2019_

    * ABI Decode NULL as False (#1582)

## v4.0.0 - _Invalid date_

    * Upgrade the bignumber.js to v8.0.2 (#1517)

## v3.0.1 - _January 15, 2019_

    * Dependencies updated

## v3.0.0 - _January 11, 2019_

    * Make `promisify` resolve when the callback error is undefined. (#1501)

## v2.1.1 - _January 9, 2019_

    * Add `should` prefix to names of properties in EncodingRules and DecodingRules (#1363)

## v2.1.0 - _Invalid date_

    * Add `logWithTime` to `logUtils` (#1461)

## v2.0.8 - _December 13, 2018_

    * Dependencies updated

## v2.0.7 - _December 11, 2018_

    * Optimized ABI Encoder/Decoder. Generates compressed calldata to save gas. Generates human-readable calldata to aid development.

## v2.0.6 - _November 21, 2018_

    * Dependencies updated

## v2.0.5 - _November 14, 2018_

    * Dependencies updated

## v2.0.4 - _November 9, 2018_

    * Dependencies updated

## v2.0.3 - _October 18, 2018_

    * Dependencies updated

## v2.0.2 - _October 4, 2018_

    * Dependencies updated

## v2.0.1 - _October 2, 2018_

    * Dependencies updated

## v2.0.0 - _September 28, 2018_

    * Make abi_decoder compatible with ethers ^4.0.0 (#1069)

## v1.0.11 - _September 25, 2018_

    * Dependencies updated

## v1.0.10 - _September 25, 2018_

    * Dependencies updated

## v1.0.9 - _September 21, 2018_

    * Dependencies updated

## v1.0.8 - _September 5, 2018_

    * Dependencies updated

## v1.0.7 - _August 27, 2018_

    * Dependencies updated

## v1.0.6 - _August 24, 2018_

    * Dependencies updated

## v1.0.5 - _August 14, 2018_

    * Increased BigNumber decimal precision from 20 to 78 (#807)
    * Store different ABIs for events with same function signature and different amount of indexed arguments (#933)

## v1.0.4 - _July 26, 2018_

    * Dependencies updated

## v1.0.3 - _July 26, 2018_

    * Dependencies updated

## v1.0.2 - _July 26, 2018_

    * Dependencies updated

## v1.0.1 - _July 23, 2018_

    * Add `AbortController` polyfill to `fetchAsync` (#903)

## v1.0.0 - _July 19, 2018_

    * Add `fetchAsync` which adds a default timeout to all requests (#874)

## v0.7.3 - _July 18, 2018_

    * Dependencies updated

## v0.7.2 - _July 9, 2018_

    * Added errorUtils.spawnSwitchErr
    * Add logUtils.warn (#589)
    * Fixes uncaught Error in abi_decoder (#763)

## v0.7.1 - _June 19, 2018_

    * Dependencies updated

## v0.7.0 - _May 31, 2018_

    * Incorrect publish that was unpublished

## v0.6.2 - _May 22, 2018_

    * Dependencies updated

## v0.6.1 - _May 4, 2018_

    * Dependencies updated

## v0.6.0 - _May 4, 2018_

    * Update ethers-contracts to ethers.js (#540)

## v0.5.2 - _April 18, 2018_

    * Export NULL_BYTES constant (#500)

## v0.5.1 - _April 11, 2018_

    * Dependencies updated

## v0.5.0 - _April 2, 2018_

    * Make `AbiDecoder.addABI` public (#485)

## v0.4.4 - _April 2, 2018_

    * Dependencies updated

## v0.4.3 - _March 17, 2018_

    * Add `@types/node` to dependencies since `intervalUtils` has the `NodeJS` type as part of its public interface.

## v0.4.2 - _March 17, 2018_

    * Consolidate all `console.log` calls into `logUtils` in the `@0xproject/utils` package (#452)

## v0.4.0 - _March 3, 2018_

    * Use `ethers-contracts` as a backend to decode event args (#413)
    * Move web3 types from devDep to dep since required when using this package (#429)

## v0.3.2 - _February 8, 2018_

    * Fix publishing issue where .npmignore was not properly excluding undesired content (#389)

## v0.3.0 - _February 4, 2018_

    * Fix a bug related to event signature collisions (argument indexes aren't included in event signatures) in the abi_decoder. The decoder used to throw on unknown events with identical signatures as a known event (except indexes). (#366)

## v0.2.0 - _January 16, 2018_

    * Add `onError` parameter to `intervalUtils.setAsyncExcludingInterval` (#312)
    * Add `intervalUtils.setInterval` (#312)
