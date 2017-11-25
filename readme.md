# Lerna test bug

Just run

```
yarn install
```

and

```
yarn test
```

You should have the following output:

```
lerna info version 2.5.1
lerna info versioning independent

> library@1.0.0 test <rootDir>/lerna-test-bug/packages/library
> echo 'Error: no test specified'

Error: no test specified
lerna success run Ran npm script 'test' in packages:
lerna success - library

```
