# @langchain/typesafe

## 0.0.3

### Patch Changes

- [#12192](https://github.com/langchain-ai/langchainjs/pull/12192) [`9920d4b`](https://github.com/langchain-ai/langchainjs/commit/9920d4b33dee5bc0cfb33d859246edf8973c86eb) Thanks [@jkennedyvz](https://github.com/jkennedyvz)! - Require Zod 4.6.6 or newer for installed dependencies to exclude versions affected by GHSA-mrhx-c7xc-m3w5. Zod v3 schemas remain supported through the bundled `zod/v3` entry point.

## 0.0.2

### Patch Changes

- [#11670](https://github.com/langchain-ai/langchainjs/pull/11670) [`8837c7a`](https://github.com/langchain-ai/langchainjs/commit/8837c7ab174d657ba9f118c6722bf27f776f7c09) Thanks [@byhow](https://github.com/byhow)! - Add `@langchain/typesafe/middleware`, with `modelRouterMiddleware` for TypeSafe `Choice`-based model routing and `autoModeMiddleware` for blocking risky tool calls with a calibrated TypeSafe `Noul` probability.

## 0.0.1

### Patch Changes

- [#11666](https://github.com/langchain-ai/langchainjs/pull/11666) [`70c42ac`](https://github.com/langchain-ai/langchainjs/commit/70c42acb84b04cf88e7af16b8e1effcdeac6597d) Thanks [@byhow](https://github.com/byhow)! - Add the `@langchain/typesafe` integration package, including `TypeSafeClassifier` for typed classification, scoring, and confidence-aware decisions with TypeSafe's Jev model.
