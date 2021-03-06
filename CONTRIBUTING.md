# Contributing

New contributions are welcomed. Follow this guide if you want to make one.

## Make a pull request

Follow [Github guide](https://help.github.com/articles/creating-a-pull-request) to fork a repo
and create a pull request.

Generally, bug fixes should go to the [`stable`](https://github.com/bem/gemini/tree/stable) branch
and new features should go to [`master`](https://github.com/bem/gemini/tree/master).

## Commit messages

Commit messages should describe what have been changed and why. The first line should be wrapped
to 50 characters, the second one should be blank. All other lines should be wrapped to 72 characters.

[Example of a good commit message](https://github.com/bem/gemini/commit/1096ee26d79be6e580e90146dbe161fb5a662d80).

## Code style and static analysis

Before submitting pull request, make sure your code passes all code style and static analysis checks.
To do so, run:

```
npm run lint
```

## Tests

Make sure all tests are passing before submitting pull request:

```
npm test
```

If you are fixing the bug, add a test that fails without your patch and passes with it. If you are
adding a feature, write a test for it. To see test coverage report run:

```
npm test --coverage
```
