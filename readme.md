# Innerface

Innerface is a library of generic UI atoms and components.

It consists of modular SASS styles and vanilla TypeScript, designed to be minimal, themable, and embeddable.


## Install

```sh
yarn add innerface
```


## Use

Styles

```scss

// Define variables

$prefix: "i-"; // Leave empty for global
$base-font-size: 14px;

@import "innerface/base";

// Import components

@import "innerface/components/slider";
```

Scripts

```ts
import innerface from 'innerface'
import slider from 'innerface/slider'

innerFace.use(slider)
```


## Develop this library

Install dependencies

```sh
yarn
```

Develop: Watch files; Recompile, type check and test on changes

```sh
yarn dev
```

Build

```sh
yarn build
```

Publish to NPM

```sh
npm run release
```
