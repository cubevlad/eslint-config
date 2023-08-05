# eslint config for react projects includes prettier rules as well

## instalation

1. run command

```sh
# or you can use npm/pnpm
yarn add -D @cubevlad/eslint-config
```

2. install peer dependencies as devDependencies

```sh
yarn dlx install-peerdeps --dev @cubevlad/eslint-config
```

3. create a .eslintrc file inside root dir and add this:

```js
{
    'extends': [
        '@cubevlad/eslint-config'
    ]
}
```
