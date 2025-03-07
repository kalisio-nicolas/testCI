# [TAXORAD] (07-03-2025)

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
    1) "before all" hook for "login"

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
    2) "before all" hook for "login"

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
Creating runner directory structure
    3) "before all" hook for "login"


  0 passing (188ms)
  3 failing

  1) administrateur
       "before all" hook for "login":
     Error: Failed to launch the browser process! undefined
[436379:436379:0307/152148.626696:ERROR:ozone_platform_x11.cc(239)] Missing X server or $DISPLAY
[436379:436379:0307/152148.626732:ERROR:env.cc(255)] The platform failed to initialize.  Exiting.


TROUBLESHOOTING: https://pptr.dev/troubleshooting

      at ChildProcess.onClose (file:///home/noenic/alternance/irsn/taxorad-workspace/kdk/node_modules/@puppeteer/browsers/lib/esm/launch.js:250:24)
      at ChildProcess.emit (node:events:530:35)
      at ChildProcess._handle.onexit (node:internal/child_process:293:12)

  2) boss
       "before all" hook for "login":
     Error: Failed to launch the browser process! undefined
[436404:436404:0307/152148.688976:ERROR:ozone_platform_x11.cc(239)] Missing X server or $DISPLAY
[436404:436404:0307/152148.689042:ERROR:env.cc(255)] The platform failed to initialize.  Exiting.


TROUBLESHOOTING: https://pptr.dev/troubleshooting

      at ChildProcess.onClose (file:///home/noenic/alternance/irsn/taxorad-workspace/kdk/node_modules/@puppeteer/browsers/lib/esm/launch.js:250:24)
      at ChildProcess.emit (node:events:530:35)
      at ChildProcess._handle.onexit (node:internal/child_process:293:12)

  3) operateur
       "before all" hook for "login":
     Error: Failed to launch the browser process! undefined
[436430:436430:0307/152148.744121:ERROR:ozone_platform_x11.cc(239)] Missing X server or $DISPLAY
[436430:436430:0307/152148.744159:ERROR:env.cc(255)] The platform failed to initialize.  Exiting.


TROUBLESHOOTING: https://pptr.dev/troubleshooting

      at ChildProcess.onClose (file:///home/noenic/alternance/irsn/taxorad-workspace/kdk/node_modules/@puppeteer/browsers/lib/esm/launch.js:250:24)
      at ChildProcess.emit (node:events:530:35)
      at ChildProcess._handle.onexit (node:internal/child_process:293:12)



----------|---------|----------|---------|---------|-------------------
File      | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s 
----------|---------|----------|---------|---------|-------------------
All files |       0 |        0 |       0 |       0 |                   
----------|---------|----------|---------|---------|-------------------
error Command failed with exit code 3.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

</details>
