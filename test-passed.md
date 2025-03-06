
# [TAXORAD] END-TO-END TESTS


>  [!TIP]   
>  All visual regression tests passed successfully.  






<details>
  <summary><h2>📜 Logs</h2></summary>

  ```bash
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
    diffTolerance: 0,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
    ✔ login (10759ms)
    ✔ list tables (1367ms)
> List records for table Groupes
    1) list records per tables
    ✔ create compartiment record (7141ms)
    2) edit compartiment record
    ✔ remove compartiment record (6018ms)
    ✔ check create version (1467ms)
    ✔ check left pane (767ms)
    ✔ check about box (1432ms)
    3) logout

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
    diffTolerance: 0,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
    ✔ login (10659ms)
    ✔ list tables (1364ms)
> List records for table Groupes
    4) list records pet tables
    ✔ create compartiment record (7154ms)
    5) edit compartiment record
    ✔ remove compartiment record (5876ms)
    ✔ check create version (1476ms)
    ✔ check left pane (766ms)
    ✔ check about box (1500ms)
    6) logout

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
    diffTolerance: 0,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
    ✔ login (10470ms)
    ✔ check tables activity (1339ms)
> List records for table Groupes
> List records for table Laboratoires
> List records for table Préleveurs
> List records for table Producteurs
    7) check records activity
    ✔ check left pane (778ms)
    ✔ check about box (1693ms)
    8) logout


  18 passing (2m)
  8 failing

  1) administrateur
       list records per tables:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:73:21)

  2) administrateur
       edit compartiment record:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:94:59)

  3) administrateur
       logout:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/administrateur.test.mjs:126:59)

  4) boss
       list records pet tables:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:73:21)

  5) boss
       edit compartiment record:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:94:59)

  6) boss
       logout:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/boss.test.mjs:126:59)

  7) operateur
       check records activity:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/operateur.test.mjs:68:21)

  8) operateur
       logout:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/operateur.test.mjs:88:62)



----------|---------|----------|---------|---------|-------------------
File      | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
----------|---------|----------|---------|---------|-------------------
All files |       0 |        0 |       0 |       0 |                   
----------|---------|----------|---------|---------|-------------------
error Command failed with exit code 8.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.

  ```

</details>
