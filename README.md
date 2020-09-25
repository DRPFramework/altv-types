# altv-types
This repository contains types definitions for alt:V JavaScript modules.

# Installation
Client-side

```bash
# With npm
npm i -D @altvdrp/types-client @altvdrp/types-natives @altvdrp/types-webview
# With yarn
yarn add -D @altvdrp/types-client @altvdrp/types-natives @altvdrp/types-webview
```

Server-side

```bash
# With npm
npm i -D @altvdrp/types-server
# With yarn
yarn add -D @altvdrp/types-server
```

To make these types detectable, you've to add `typeRoots` property below to your project's `tsconfig.json`
```json
{
  "compilerOptions": {
    "typeRoots": [
      "./node_modules/@types",
      "./node_modules/@altv"
    ]
  }
}
```
