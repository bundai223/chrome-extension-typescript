# chrome-extension-typescript

Typescript Chrome Extension Skeleton

## How to reproduce

```bash
npm init
npx tsc --init
npm install --save webextension-polyfill-ts # Chrome APIでPromiseを使えるpolyfill
npm install --save-dev webpack webpack-cli copy-webpack-plugin ts-node ts-loader @types/webpack @types/copy-webpack-plugin
```

## build

`npx webpack`
