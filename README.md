# Lit Element Tester

A framework that makes unit testing your custom elements built with `Polymer/lit-element` a breeze. This is an alternative to Google Web Component Tester.

Built with [Mocha Headless Chrome](https://github.com/direct-adv-interfaces/mocha-headless-chrome).

# Installation

```shell
npm install lit-element-tester -g
```

You may alternatively install the package locally with `--save` option and use `npx` utility to run it.


# Highlights

- Development mode with Google Chrome
- Production mode that runs completely headless
- Source map support for debugging
- Code coverage
- HTML fixtures

# Note

Take note that Google Chrome is the only supported browser, and there is no plan to add support for other browsers.

# HTML test runner template

**lit-element-tester** requires you to provide an HTML test runner that will get loaded in Chrome for testing.

Use the following as a template for your test runner:
https://github.com/drochgenius/lit-element-tester/blob/master/test/runner.html

We expect this file to be located in a folder called **/test** at the top level of your project.

# Usage

Look at the man page.

```shell
lit-element-tester -h
```

# Run tests

```shell
lit-element-tester
```

# Develop tests

```shell
lit-element-tester -d
```