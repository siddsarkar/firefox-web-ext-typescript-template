# Usage Instructions

## Develop

- clone the repository

```sh
git clone https://github.com/siddsarkar/firefox-web-ext-typescript-template.git
```

- install dependencies

```sh
yarn install
```

- start development

```sh
yarn dev
```

> Note: during dev typescript comiplation and web-ext reloading are done simultaneously, so just keep coding `:)`

## Build

- run

```sh
yarn build
```

- this generates `.zip` file of your ext to be uploaded to AMO

## Runtime Outputs

### Web-ext lint output

```sh
yarn run v1.22.10
$ web-ext lint --source-dir=./extension-dist/
Applying config file: .\package.json
Validation Summary:

errors          0
notices         0
warnings        0

Done in 23.33s.
```

### TypeScript compilation output

```sh
yarn run v1.22.10
$ tsc
Done in 1.51s.
```
