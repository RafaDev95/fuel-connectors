# @fuel-connectors/burner-wallet-connector

## 0.26.0

## 0.25.0

## 0.24.0

### Minor Changes

- [#167](https://github.com/FuelLabs/fuel-connectors/pull/167) [`ed5fb44`](https://github.com/FuelLabs/fuel-connectors/commit/ed5fb440b1b0739fbeb616156864d9ba6da3ac07) Thanks [@LeoCourbassier](https://github.com/LeoCourbassier)! - - Bumped packages version from `0.9.0` to `0.23.0` following react package's version

  - Updated react-next example to use `defaultConnectors` from @fuels/connectors package

- [#178](https://github.com/FuelLabs/fuel-connectors/pull/178) [`98df6e3`](https://github.com/FuelLabs/fuel-connectors/commit/98df6e304f67a8aa6f43eec9194d179ebfd42725) Thanks [@helciofranco](https://github.com/helciofranco)! - Add `Burner Wallet` recovery feature.

  > A dialog will now prompt the user to recover their previous Burner Wallet session.

- [#178](https://github.com/FuelLabs/fuel-connectors/pull/178) [`98df6e3`](https://github.com/FuelLabs/fuel-connectors/commit/98df6e304f67a8aa6f43eec9194d179ebfd42725) Thanks [@helciofranco](https://github.com/helciofranco)! - Fix `Burner Wallet` connection status issue getting stuck after some connect/disconnect (it was losing the connection status).

- [#145](https://github.com/FuelLabs/fuel-connectors/pull/145) [`533abbf`](https://github.com/FuelLabs/fuel-connectors/commit/533abbfd163ad377faf2239d768a15821f6f5611) Thanks [@rodrigobranas](https://github.com/rodrigobranas)! - Breaking Change: now methods that return address, like "getAccount", will return a b256 address instead of a bech32.

- [#173](https://github.com/FuelLabs/fuel-connectors/pull/173) [`f0739c4`](https://github.com/FuelLabs/fuel-connectors/commit/f0739c44b11c1a2e1662120c5ed2480e671c5571) Thanks [@LuizAsFight](https://github.com/LuizAsFight)! - Breaking change: BurnerWallet sendTransaction method no longer will wait for tx execution

### Patch Changes

- [#173](https://github.com/FuelLabs/fuel-connectors/pull/173) [`f0739c4`](https://github.com/FuelLabs/fuel-connectors/commit/f0739c44b11c1a2e1662120c5ed2480e671c5571) Thanks [@LuizAsFight](https://github.com/LuizAsFight)! - update fuels to 0.93.0

- [#147](https://github.com/FuelLabs/fuel-connectors/pull/147) [`7ce5702`](https://github.com/FuelLabs/fuel-connectors/commit/7ce5702e74a1bbbd7f50ec8b7c281c7b4e2b3480) Thanks [@mvares](https://github.com/mvares)! - feat: persist BurnerWallet provider in localStorage

## 0.9.1

## 0.9.0

### Minor Changes

- [#158](https://github.com/FuelLabs/fuel-connectors/pull/158) [`23afa71`](https://github.com/FuelLabs/fuel-connectors/commit/23afa71b01b799aa320ad56abbb8c2c896a5a156) Thanks [@LuizAsFight](https://github.com/LuizAsFight)! - feat: update to fuels 0.92.0

### Patch Changes

- [#156](https://github.com/FuelLabs/fuel-connectors/pull/156) [`481b5fe`](https://github.com/FuelLabs/fuel-connectors/commit/481b5fea5363f38daf0c054712395cfc7e2227e0) Thanks [@arthurgeron](https://github.com/arthurgeron)! - - [Add support for burner wallet config on default connectors](https://github.com/FuelLabs/fuel-connectors/commit/fb845c0cfdfccfda60637af8d405964e9efbdecb)

  - [Burner wallet storage not working on nodejs](https://github.com/FuelLabs/fuel-connectors/commit/bbf19a2f8b6faeafc5c99055fe2ce2beb2988400)
  - [Create in memory storage on burner wallet](https://github.com/FuelLabs/fuel-connectors/commit/242b24f84f4ac35dba9c1332cb46c80bac5f4766)

  Observation: Burner Wallet's Storage will not persist information between executions on Vercel or Node.js env.

## 0.8.1

## 0.8.0

## 0.7.0

### Patch Changes

- [#122](https://github.com/FuelLabs/fuel-connectors/pull/122) [`eee5a71`](https://github.com/FuelLabs/fuel-connectors/commit/eee5a71c30c61838bc9d811ddc6c814925c68d04) Thanks [@matt-user](https://github.com/matt-user)! - Can now set custom providers in the Burner wallet connector

## 0.6.0

## 0.5.1

## 0.5.0

### Minor Changes

- [#85](https://github.com/FuelLabs/fuel-connectors/pull/85) [`450ce37`](https://github.com/FuelLabs/fuel-connectors/commit/450ce37769592e611eaddd6af38b0030dc57cdb3) Thanks [@luizstacio](https://github.com/luizstacio)! - Update default network to testnet

- [#85](https://github.com/FuelLabs/fuel-connectors/pull/85) [`450ce37`](https://github.com/FuelLabs/fuel-connectors/commit/450ce37769592e611eaddd6af38b0030dc57cdb3) Thanks [@luizstacio](https://github.com/luizstacio)! - Update to fuels 0.88.1

## 0.4.0

## 0.3.0

### Minor Changes

- [#68](https://github.com/FuelLabs/fuel-connectors/pull/68) [`98c6b5d`](https://github.com/FuelLabs/fuel-connectors/commit/98c6b5d366128d763d601896a7b3b7d594ea6886) Thanks [@arthurgeron](https://github.com/arthurgeron)! - Upgrade fuels and fuel-ts dependencies to 0.83

### Patch Changes

- [#58](https://github.com/FuelLabs/fuel-connectors/pull/58) [`eafe351`](https://github.com/FuelLabs/fuel-connectors/commit/eafe35145160f3c7fb21ae5965d108ab7c64022e) Thanks [@pedropereiradev](https://github.com/pedropereiradev)! - Refactor burner wallet connector

- [#49](https://github.com/FuelLabs/fuel-connectors/pull/49) [`fe8fe45`](https://github.com/FuelLabs/fuel-connectors/commit/fe8fe45ee5b582d1379a9d61a2690a708ceaf69c) Thanks [@pedropereiradev](https://github.com/pedropereiradev)! - burner wallet connector implemented

## 0.3.0

### Minor Changes

- [#68](https://github.com/FuelLabs/fuel-connectors/pull/68) [`98c6b5d`](https://github.com/FuelLabs/fuel-connectors/commit/98c6b5d366128d763d601896a7b3b7d594ea6886) Thanks [@arthurgeron](https://github.com/arthurgeron)! - Upgrade fuels and fuel-ts dependencies to 0.83

### Patch Changes

- [#58](https://github.com/FuelLabs/fuel-connectors/pull/58) [`eafe351`](https://github.com/FuelLabs/fuel-connectors/commit/eafe35145160f3c7fb21ae5965d108ab7c64022e) Thanks [@pedropereiradev](https://github.com/pedropereiradev)! - Refactor burner wallet connector

- [#49](https://github.com/FuelLabs/fuel-connectors/pull/49) [`fe8fe45`](https://github.com/FuelLabs/fuel-connectors/commit/fe8fe45ee5b582d1379a9d61a2690a708ceaf69c) Thanks [@pedropereiradev](https://github.com/pedropereiradev)! - burner wallet connector implemented
