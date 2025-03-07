# [TAXORAD] (07-03-2025)

>   [!CAUTION]
>   **2** tests have failed
>   - [operateur/logout-screen](#operateurlogout-screen)
>   - [operateur/producteurs-view](#operateurproducteurs-view)

<details>
<summary><h2>🔍 Inspect</h2></summary>

### operateur/logout-screen

<p align="center">
  <img src="https://s3.gra.cloud.ovh.net/dev/e2e-tests/taxorad/07-03-2025/operateur/logout-screen.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3f1c4c5f9fbc4edb92cc05cbedce9a20%2F20250307%2FGRA%2Fs3%2Faws4_request&X-Amz-Date=20250307T142704Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=3cb6a466c5fcc879073a4d970433567e26cb1fe46433bd2ccfa3f093a239adee" width="49%"/>
  <img src="https://s3.gra.cloud.ovh.net/dev/e2e-tests/taxorad/07-03-2025/operateur/diff.logout-screen.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3f1c4c5f9fbc4edb92cc05cbedce9a20%2F20250307%2FGRA%2Fs3%2Faws4_request&X-Amz-Date=20250307T142704Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=a1d160d346a3f6b34f72ddabccc61826c7a8b5901c7ac583786b7ff41a643f62" width="49%"/>
</p>

### operateur/producteurs-view

<p align="center">
  <img src="https://s3.gra.cloud.ovh.net/dev/e2e-tests/taxorad/07-03-2025/operateur/producteurs-view.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3f1c4c5f9fbc4edb92cc05cbedce9a20%2F20250307%2FGRA%2Fs3%2Faws4_request&X-Amz-Date=20250307T142706Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=966eb939c3fcd415f53a8f258754103d946165761125b09fa718a885e580dd97" width="49%"/>
  <img src="https://s3.gra.cloud.ovh.net/dev/e2e-tests/taxorad/07-03-2025/operateur/diff.producteurs-view.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=3f1c4c5f9fbc4edb92cc05cbedce9a20%2F20250307%2FGRA%2Fs3%2Faws4_request&X-Amz-Date=20250307T142705Z&X-Amz-Expires=604800&X-Amz-SignedHeaders=host&X-Amz-Signature=f971fb0cd422c4453e6a132c974324bd1f5be0669bb6e87c01a5874345851e95" width="49%"/>
</p>

</details>

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
    ✔ login (10208ms)
    ✔ list tables (1371ms)
> List records for table Groupes
> List records for table Laboratoires
> List records for table Préleveurs
> List records for table Producteurs
> List records for table Appareils de mesure
> List records for table Equipements de prélèvement
> List records for table Méthodes
> List records for table Compartiments
> List records for table Espèces
> List records for table Natures
> List records for table Radionucléides
> List records for table Unités
    ✔ list records per tables (78248ms)
    ✔ create compartiment record (7165ms)
    ✔ edit compartiment record (4635ms)
    ✔ remove compartiment record (5816ms)
    ✔ check create version (1403ms)
    ✔ check left pane (763ms)
    ✔ check about box (1479ms)
    ✔ logout (3644ms)

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
    ✔ login (10048ms)
    ✔ list tables (1328ms)
> List records for table Groupes
> List records for table Laboratoires
> List records for table Préleveurs
> List records for table Producteurs
> List records for table Appareils de mesure
> List records for table Equipements de prélèvement
> List records for table Méthodes
> List records for table Compartiments
> List records for table Espèces
> List records for table Natures
> List records for table Radionucléides
> List records for table Unités
    ✔ list records pet tables (54044ms)
    ✔ create compartiment record (7029ms)
    ✔ edit compartiment record (4583ms)
    ✔ remove compartiment record (5738ms)
    ✔ check create version (1418ms)
    ✔ check left pane (764ms)
    ✔ check about box (1469ms)
    ✔ logout (3375ms)

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
    ✔ login (10263ms)
    ✔ check tables activity (1322ms)
> List records for table Groupes
> List records for table Laboratoires
> List records for table Préleveurs
> List records for table Producteurs
    1) check records activity
    ✔ check left pane (770ms)
    ✔ check about box (1451ms)
    2) logout


  24 passing (4m)
  2 failing

  1) operateur
       check records activity:

      AssertionError: expected false to be true
      + expected - actual

      -false
      +true
      
      at Proxy.<anonymous> (node_modules/chai-lint/index.js:35:42)
      at Proxy.methodWrapper (node_modules/chai/lib/chai/utils/addMethod.js:57:25)
      at Context.<anonymous> (file:///home/noenic/alternance/irsn/taxorad-workspace/taxorad/test/operateur.test.mjs:68:21)

  2) operateur
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
error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

</details>
