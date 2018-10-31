# babel-test

Example where babel-loader and node require works but not Babel Registry

If you run `npm run node` you get:
```
Schema is function Schema(obj, options) { ... }
```

If you run `npm run dist` the webpack build you get:
```
Schema is function Schema(obj, options) { ... }
```

But if you run `npm run register` you get:
```
Schema is undefined
```
