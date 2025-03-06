
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
    diffTolerance: 3,
    writeDiffs: true
  },
  mode: 'run',
  geolocation: { accuracy: 500 },
  appName: 'taxorad',
  lang: 'fr-FR'
}
Creating runner directory structure
    ✔ login (10333ms)
    ✔ list tables (1417ms)
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
    ✔ list records per tables (78321ms)
    ✔ create compartiment record (7070ms)
    ✔ edit compartiment record (4584ms)
    ✔ remove compartiment record (5810ms)
    ✔ check create version (1426ms)
    ✔ check left pane (775ms)
    ✔ check about box (1478ms)
    ✔ logout (3445ms)

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
    ✔ login (9564ms)
    ✔ list tables (1336ms)
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
    ✔ list records pet tables (54076ms)
    ✔ create compartiment record (7136ms)
    ✔ edit compartiment record (4581ms)
    ✔ remove compartiment record (5765ms)
    ✔ check create version (1428ms)
    ✔ check left pane (764ms)
    ✔ check about box (1413ms)
    ✔ logout (3455ms)

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
    ✔ login (9766ms)
    ✔ check tables activity (1369ms)
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
    ✔ check records activity (53658ms)
    ✔ check left pane (780ms)
    ✔ check about box (1441ms)
    ✔ logout (3375ms)


  26 passing (5m)

----------|---------|----------|---------|---------|-------------------
File      | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
----------|---------|----------|---------|---------|-------------------
All files |       0 |        0 |       0 |       0 |                   
----------|---------|----------|---------|---------|-------------------
Done in 286.56s.

  ```

</details>
