# eslint-config-nnimetz-base

Eslint test

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-config-nnimetz-base`:

```
$ npm install eslint-config-nnimetz-base --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-config-nnimetz-base` globally.

## Usage

Add `eslint-config-nnimetz-base` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-config-` prefix:

```json
{
    "plugins": [
        "eslint-config-nnimetz-base"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "eslint-config-nnimetz-base/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here
