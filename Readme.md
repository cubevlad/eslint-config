# eslint config for react projects includes prettier rules as well

## installation

1. run command

```sh
# with npm
npm install @frknnice/eslint-config
# with yarn
yarn add @frknnice/eslint-config
```

2. create a .eslintrc file inside root dir and add this:

```js
{
    'extends': [
        '@frknnice/eslint-config'
    ]
}
```

3. add additional packages as dependencies if needed:

```sh
npm install --save-dev @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint prettier
eslint-config-airbnb eslint-config-prettier eslint-import-resolver-alias eslint-import-resolver-typescript
eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-jsx-expressions eslint-plugin-react eslint-plugin-react-hooks
```
