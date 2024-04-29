# Example Web Client

This project demonstrates how to use `@lightprotocol/stateless.js` in a browser environment to interact with the ZK Compression API.

## Running the Example

**You need to have the CLI installed to run this example. For installation instructions, see [here](https://github.com/Lightprotocol/light-protocol/tree/js-0.2.1-release/cli#readme).**

1. Start a light test-validator using the CLI

```bash
light test-validator
```

2. Start the app

```bash
# or yarn or pnpm
npm install &&
npm run dev
```

If a prompt appears asking you to select a `@lightprotocol/hasher.rs` version, select `0.1.1-alpha.1`.

The app will serve and mount the app at http://localhost:1234 and run the code defined in `page.tsx`.

The UI will show a `react-hydration-error` which you can safely ignore.
