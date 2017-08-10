# eslint-plugin-additional-return-rules

Prevent using return;

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-additional-return-rules`:

```
$ npm install eslint-plugin-additional-return-rules --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-additional-return-rules` globally.

## Usage

Add `additional-return-rules` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "additional-return-rules"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "additional-return-rules/return-no-semi": 2
    }
}
```

## Supported Rules

* return-no-semi





