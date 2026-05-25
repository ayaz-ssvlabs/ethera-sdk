# 0.1.0 (2026-05-25)

### Features

- add `composeUniversalBridgeTransfer` recipe with CET, ERC20, and native asset support
- add `GasOverrides` to `createUserOp` for manual gas control
- Phase 3 advanced DX, structured errors, and docs consolidation
- bridge allowance policy and injectable bridge functions
- compose metadata, lifecycle callbacks, and preflight validation
- compose validation and paymaster endpoint checks
- add bridge transfer recipe and document bridge/private-key flows
- align Ethera API and harden smart account flows

### Bug Fixes

- derive AA chain set from `accountAbstractionContracts` keys, not wagmi chains
- correct stale `multiChainIds` default description and validator scope language in README
- correct error method labels, signing error boundary, and `multiChainIds` defaults/docs
- guard zero-amount bridge transfers, strengthen tests, document allowance caveats
- validate compose config and surface smart account errors
- remove redundant pnpm version from CI, rely on `packageManager` field

### Refactors

- remove redundant type casts across account-abstraction, user-op, and xt utilities
- remove `any`/`unknown` from `createAbiEncoder`, expand test suite
- simplification of control flags which did not bring any value

### Docs

- clarify `useMetaFactory=false` and `kernelFactory` interface requirement

### Chores

- bump axios, protobufjs, and rollup to patched versions (security)
- remove unused Vite polyfills and align build config
- build GitHub installs locally via `prepare` + removal of tracking build artifacts
- CI workflow improvements for artifact PRs
- update repo endpoint

# 0.0.2 (2026-04-16)

### Changes

- package naming and metadata alignment
- update README install/import examples to current package name
- fix README API examples to use current exported compose function names
- align npm metadata (name, description, repository, homepage, keywords)
- clean published tarball contents (keep markdown README only)

# 0.2.0 (2024-04-17)

### Features

- pre-release boilerplate ([f15717e](https://github.com/crper/rollup-typescript-lib-boilerplate/commit/f15717e592462317754f479414db0fa8676c76b6))
