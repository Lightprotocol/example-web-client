# Example Web Client

This project demonstrates how to use `@lightprotocol/stateless.js` to interact with the ZK Compression API on Solana.

## Running the Example

** You must have the Monorepo/CLI built and a running test-validator to run
this example. **

0. Get the Monorepo

The Monorepo lives at: https://github.com/Lightprotocol/light-protocol

```bash
git clone git@github.com:Lightprotocol/light-protocol.git
```

1. Build the Monorepo against the v.0.1.1 tag.

```bash
git fetch --tags &&
git checkout tags/v.0.1.1 &&
. ./scripts/devenv.sh &&
./scripts/install.sh &&
./scripts/build.sh
```

1. Start a light test-validator using the CLI

```bash
# in the monorepo root
cd cli &&
light test-validator
```

2. Return to this repo and start the app

```bash
# or yarn or pnpm
npm install &&
npm run dev
```

If a prompt appears asking you to select a `@lightprotocol/hasher.rs` version, select `0.1.1-alpha.1`.

The app will serve and mount the app at http://localhost:1234 and run the code defined in `page.tsx`.

The UI will show a `react-hydration-error` which you can safely ignore.
