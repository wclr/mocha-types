# @types/mocha

> without globals

This is just official version `@types/mocha` package with [`globals`](https://github.com/mochajs/mocha/issues/956) stripped away.

# Install

Just add from github repo:

> yarn/pnpm add github:whitecolor/mocha-types

And enjoy.

```ts
import { describe, it, beforeEach, after } from "mocha";

describe("Some test", () => {
  it("should work", () => {});
});
```
