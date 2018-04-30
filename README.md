# eslint-config-goldhand
My preferred eslint preset

## Getting Started
Just install this and peer dependencies then extend `eslint-config-goldhand` from your `.eslintrc` file.

```
$ npm install -D eslint-config-goldhand
```

List the required peer dependencies by running:
```
$ npm info "eslint-config-config@latest" peerDependencies
```

Then just `npm install` each one with the correct `@<version>` suffix, eg:
```
$ npm install -D eslint-plugin-import@^2.11.0
```

Edit your `.eslintrc` file to look like:
```json
{ "extends": "eslint-config-goldhand" }
```
