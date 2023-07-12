# repro-markmap-missing-types

```sh
git clone https://github.com/hyperupcall/repro-markmap-missing-types
cd repro-markmap-missing-types
npm i
```

```sh
$ node --version
v20.3.0
```

```text
$ ./node_modules/.bin/tsc -p .
index.ts:1:29 - error TS7016: Could not find a declaration file for module 'markmap-lib'. '/tmp/tmp.5nuGfbTBcq/node_modules/markmap-lib/dist/index.js' implicitly has an 'any' type.
  Try `npm i --save-dev @types/markmap-lib` if it exists or add a new declaration (.d.ts) file containing `declare module 'markmap-lib';`

1 import { Transformer } from 'markmap-lib'
                              ~~~~~~~~~~~~~


Found 1 error in index.ts:1
```
