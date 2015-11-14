# @dominicbarnes/eslint-config-deku

> Adds ESLint configuration for use in the deku-based projects.

## Usage

In a `.eslintrc`, add the following:

```
{
  "extends": [
    "@dominicbarnes",
    "@dominicbarnes/browser"
    "@dominicbarnes/deku"
  ]
}
```

This assumes node@4.x, and adds the `ecmaFeatures` that are supported according to the
[ES6 documentation](https://nodejs.org/en/docs/es6).

This also intentionally leaves out `@dominicbarnes` as the base plugin, so it needs to be added
to any project's root `.eslintrc` manually.
