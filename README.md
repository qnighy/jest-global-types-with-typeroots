```
$ yarn
```

```
$ yarn tsc
yarn run v1.22.5
$ tsc
Done in 1.71s.
```

```
$ yarn tsc-tr
yarn run v1.22.5
$ tsc -p tsconfig.tr.json
src/index.test.ts:1:1 - error TS2593: Cannot find name 'test'. Do you need to install type definitions for a test runner? Try `npm i --save-dev @types/jest` or `npm i --save-dev @types/mocha` and then add `jest` or `mocha` to the types field in your tsconfig.

1 test("42", () => {
  ~~~~

src/index.test.ts:2:3 - error TS2304: Cannot find name 'expect'.

2   expect(42).toBe(42);
    ~~~~~~


Found 2 errors.

error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```