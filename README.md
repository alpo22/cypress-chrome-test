This just uses Create React App and the example tests created by Cypress.

Steps:
```
pnpm i
pnpm cypress open
chose `e2e testing`
chose a browser
chose `todo.cy.js`
after done, close cypress with `cmd + q`
```

Chrome:
```
it took 1:06 the first time
it took 0:33 the second time
then 0:05
ran maybe 4 or 5 more times and got down to 0:02
then it got really laggy and took 1:24
```
Firefox:
```
it took 0:04 the first time
it took 0:02 the next 10 times
```

Electron:
```
it took 0:03 the first time
it took 0:01 the next 10 times
```
