# How to use

```bash
git clone https://github.com/alvaroraminelli/onchainkit-playground.git

cd onchainkit-playground

yarn
yarn dev --force

// build onchain locally and copy it to the playground
yarn build && rm -rf <path>/playground/node_modules/@coinbase/onchainkit && cp -r <path>/onchainkit <path>/playground/node_modules/@coinbase
```
