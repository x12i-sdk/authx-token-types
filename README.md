# @x12i/authx-token-types usage example

Shared TypeScript contracts and Zod schemas for AuthX Token Infrastructure.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `1.0.1`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Shared TypeScript contracts and Zod schemas for AuthX Token Infrastructure.
- A producer and consumer of authx-token data need to share the published type or validation contract before exchanging payloads.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/authx-token-types)
- [Implementation monorepo](https://github.com/x12i/authx-token-types)
- [Reviewed package source](https://github.com/x12i/authx-token-types/tree/37935fdbcb3552ed964a2b9939f6714f82939e88/.)

The current source snapshot has a different manifest version from the pinned npm dependency. This example is validated against the installed npm release.

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
