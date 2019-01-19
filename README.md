This repo shows a difficult to catch issue where debug breakpoints will only trigger approximately 10% of the time. There appears to be no way to reproduce this reliably, I can only observe the behavior if I sit at my computer and run the debugger over and over again until it will randomly work.

Tested on Node 8 and Node 10.15

This guide was used to prepare this repo

```
https://github.com/Microsoft/vscode-recipes/tree/master/debugging-jest-tests
```