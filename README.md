## A shared set of code formatting rules to be used across Datawrapper projects.

To use this config, install it via NPM along with Prettier:

`npm install -D prettier@2 @datawrapper/prettier-config`

Then you can include it in your project's Prettier configuration, which most probably lives in its `package.json`:

```json
{
    "name": "my-cool-project",
    "version": "1.0.0",
    "dependencies": {},
    "prettier": "@datawrapper/prettier-config"
}
```
