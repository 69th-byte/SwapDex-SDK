SwapDex SDK
code style: prettier Actions Status npm version npm bundle size (scoped version)

In-depth documentation on this SDK is available at swapdex.net.

Running tests
To run the tests, follow these steps. You must have at least node v10 and yarn installed.

First clone the repository:

git clone https://github.com/69th-byte/swapdex-sdk.git
Move into the uniswap-sdk working directory

cd swapdex-sdk/
Install dependencies

yarn install
Run tests

yarn test
You should see output like the following:

yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.