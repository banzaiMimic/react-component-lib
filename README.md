### development
- all component development done in src/lib
- local dev via src/index.js (yarn start)
- export all your components from src/lib/index.js for dist
```
yarn
yarn start
```

### publishing
- linux `yarn build`
- windows 10 `yarn buildWin`
- this will compile all modules in src/lib into /dist for npm package deploy