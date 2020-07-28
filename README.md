# @types/mocha

> without globals

This is just official version of `@types/mocha` package with [`globals`](https://github.com/mochajs/mocha/issues/956) stripped away.

# Install

Just install/add it from the github repo (instead of `@types/mocha` from NPM):

> yarn/pnpm add github:whitecolor/mocha-types

And enjoy.

```ts
import { describe, it, beforeEach, after } from "mocha";

// without explicit import typescript will show errors
describe("Some test", () => {
  it("should work", () => {});
});
```
