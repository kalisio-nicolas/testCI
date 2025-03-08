# [TAXORAD] (09-03-2025)

>   [!TIP]
> All tests have passed


<details>
<summary><h2>📜 Logs</h2></summary>

```shell
yarn run v1.22.22
$ cd test && npm run coverage

> taxorad@1.3.0 coverage
> c8 npm run mocha


> taxorad@1.3.0 mocha
> mocha test/**/*.test.mjs --timeout 30000



  administrateur
Runner created with the following options:
{
  baseUrl: 'http://localhost:9092',
  browser: {
    product: 'chrome',
    headless: false,
    devtools: false,
    defaultViewport: { width: 1024, height: 768 },
    args: [],
    slowMo: 2
  },
  dataDir: 'test/data/administrateur',
  runDir: 'test/run/chrome/administrateur',
  screenshots: {
    dir: 'test/run/chrome/administrateur/screenshots',
    screenrefsDir: 'test/data/administrateur/screenrefs',
    matchThreshold: 0.1,
    diffTolerance: 3,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
Creating runner directory structure
    ✔ login (10348ms)
    1) list tables
> List records for table Groupes
    2) list records per tables
[KDK] Click #fab failed.
[KDK] Type nocomp in #code-field failed.
[KDK] Type Nouveau compartiment in #label-field failed.
[KDK] Click #ok-button failed.
    3) create compartiment record
[KDK] Click #color-field failed.
[KDK] Click .q-color-picker .q-color-picker__cube:nth-child(16) failed.
[KDK] Click #color-field failed.
[KDK] Click #ok-button failed.
    4) edit compartiment record
[KDK] Click .q-dialog button:nth-child(2) failed.
    5) remove compartiment record
    ✔ check create version (1446ms)
    ✔ check left pane (789ms)
    ✔ check about box (1416ms)
    ✔ logout (3420ms)

  boss
Runner created with the following options:
{
  baseUrl: 'http://localhost:9092',
  browser: {
    product: 'chrome',
    headless: false,
    devtools: false,
    defaultViewport: { width: 1024, height: 768 },
    args: [],
    slowMo: 2
  },
  dataDir: 'test/data/boss',
  runDir: 'test/run/chrome/boss',
  screenshots: {
    dir: 'test/run/chrome/boss/screenshots',
    screenrefsDir: 'test/data/boss/screenrefs',
    matchThreshold: 0.1,
    diffTolerance: 3,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
Creating runner directory structure
    ✔ login (10224ms)
    6) list tables
> List records for table Groupes
    7) list records pet tables
[KDK] Click #fab failed.
[KDK] Type nocomp in #code-field failed.
[KDK] Type Nouveau compartiment in #label-field failed.
[KDK] Click #ok-button failed.
    8) create compartiment record
[KDK] Click #color-field failed.
[KDK] Click .q-color-picker .q-color-picker__cube:nth-child(16) failed.
[KDK] Click #color-field failed.
[KDK] Click #ok-button failed.
    9) edit compartiment record
[KDK] Click .q-dialog button:nth-child(2) failed.
    10) remove compartiment record
    ✔ check create version (1432ms)
    ✔ check left pane (771ms)
    ✔ check about box (1402ms)
    ✔ logout (3597ms)

  operateur
Runner created with the following options:
{
  baseUrl: 'http://localhost:9092',
  browser: {
    product: 'chrome',
    headless: false,
    devtools: false,
    defaultViewport: { width: 1024, height: 768 },
    args: [],
    slowMo: 2
  },
  dataDir: 'test/data/operateur',
  runDir: 'test/run/chrome/operateur',
  screenshots: {
    dir: 'test/run/chrome/operateur/screenshots',
    screenrefsDir: 'test/data/operateur/screenrefs',
    matchThreshold: 0.1,
    diffTolerance: 3,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
Creating runner directory structure
    ✔ login (10257ms)
    11) check tables activity
> List records for table Groupes
    12) check records activity
    ✔ check left pane (775ms)
    ✔ check about box (1483ms)
    ✔ logout (3680ms)


  14 passing (2m)
  12 failing

  1) administrateur
       list tables:

      AssertionError: expected +0 to equal 12
      + expected - actual

      -0
      +12
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:60:25)

  2) administrateur
       list records per tables:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:69:63)

  3) administrateur
       create compartiment record:

      AssertionError: expected +0 to equal 8
      + expected - actual

      -0
      +8
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:84:58)

  4) administrateur
       edit compartiment record:

      AssertionError: expected +0 to equal 8
      + expected - actual

      -0
      +8
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:93:58)

  5) administrateur
       remove compartiment record:

      AssertionError: expected +0 to equal 7
      + expected - actual

      -0
      +7
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:100:58)

  6) boss
       list tables:

      AssertionError: expected +0 to equal 12
      + expected - actual

      -0
      +12
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:60:25)

  7) boss
       list records pet tables:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:69:63)

  8) boss
       create compartiment record:

      AssertionError: expected +0 to equal 8
      + expected - actual

      -0
      +8
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:84:58)

  9) boss
       edit compartiment record:

      AssertionError: expected +0 to equal 8
      + expected - actual

      -0
      +8
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:93:58)

  10) boss
       remove compartiment record:

      AssertionError: expected +0 to equal 7
      + expected - actual

      -0
      +7
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:100:58)

  11) operateur
       check tables activity:

      AssertionError: expected +0 to equal 12
      + expected - actual

      -0
      +12
      
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/operateur.test.mjs:55:25)

  12) operateur
       check records activity:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/operateur.test.mjs:64:63)



----------|---------|----------|---------|---------|-------------------
File      | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
----------|---------|----------|---------|---------|-------------------
All files |       0 |        0 |       0 |       0 |                   
----------|---------|----------|---------|---------|-------------------
error Command failed with exit code 12.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

</details>
