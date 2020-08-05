# mdi-react-es [![npm package](https://img.shields.io/npm/v/mdi-react-es.svg?style=flat-square)](https://npmjs.org/package/mdi-react-es)
[Material Design Icons](https://materialdesignicons.com) for React packaged as single components

## Introduction

This repo is forked from [mdi-react](https://github.com/levrik/mdi-react), but with modern ES module syntax.

## Installation

```bash
npm install mdi-react-es
# or if you use Yarn
yarn add mdi-react-es
```

*The version number of `mdi-react-es` is in sync with the original font.*

## Usage

Just search for an icon on [materialdesignicons.com](https://materialdesignicons.com) and look for its name.  
The name translates to PascalCase followed by the suffix `Icon` in `mdi-react-es`.

For example the icons named `alert` and `alert-circle`:

```javascript
import AlertIcon from 'mdi-react-es/AlertIcon';
import AlertCircleIcon from 'mdi-react-es/AlertCircleIcon';

const MyComponent = () => {
  return (
    <div>
      <AlertIcon />
      <AlertCircleIcon className="some-class" />
    </div>
  );
};
```

The icons get a class named `mdi-icon` attached for styling. You can also attach own additional classes with the `className` property.
