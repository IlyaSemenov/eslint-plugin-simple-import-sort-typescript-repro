## HOWTO

```
yarn
yarn eslint test.ts
```

Result:

```
TypeError: Expected `index` to be a number.
    at SourceCode.getLocFromIndex (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/util/source-code.js:436:19)
    at maybeReportSorting (/Users/semenov/tmp/ts-rule/node_modules/eslint-plugin-simple-import-sort/src/sort.js:62:27)
    at Program (/Users/semenov/tmp/ts-rule/node_modules/eslint-plugin-simple-import-sort/src/sort.js:20:11)
    at listeners.(anonymous function).forEach.listener (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/util/safe-emitter.js:45:58)
    at Array.forEach (<anonymous>)
    at Object.emit (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/util/safe-emitter.js:45:38)
    at NodeEventGenerator.applySelector (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/util/node-event-generator.js:251:26)
    at NodeEventGenerator.applySelectors (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/util/node-event-generator.js:280:22)
    at NodeEventGenerator.enterNode (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/util/node-event-generator.js:294:14)
    at CodePathAnalyzer.enterNode (/Users/semenov/tmp/ts-rule/node_modules/eslint/lib/code-path-analysis/code-path-analyzer.js:632:23)
```
