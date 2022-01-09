# UI-Kit-Storybook [![Test worklow](https://github.com/devilinorange/ui-kit-storybook/actions/workflows/test.yml/badge.svg?branche=master)](https://github.com/devilinorange/ui-kit-storybook/actions) [![License](https://img.shields.io/badge/License-UNLICENSED-orange)](https://github.com/devilinorange/ui-kit-storybook/blob/master/LICENSE)

UI-Kit-Storybook is a project for experimenting with react, storybook and CI customization.

## Install

1. ```git clone https://github.com/devilinorange/ui-kit-storybook.git```
2. ```cd ./ui-kit-storybook```
3. ```npm install```

## Possible scripts

|Script                         |Description                              |
|-------------------------------|-----------------------------------------|
|```npm run storybook```        |Run storybook on localhost on port 6006  |
|```npm run build-storybook```  |Build storybook                          |
|```npm run format```           |Force format to codestyle                |
|```npm run lint```             |Test codestyle                           |
|```npm run build:components``` |Build only react components              |
|```npm run build:storybook```  |Build only storybook                     |
|```npm run build```            |Build all packages                       |
|```npm run clean:components``` |Clean only react component build folder  |
|```npm run clean:storybook```  |Clean only storybook build folder        |
|```npm run Clean```            |Clean all build folders of all packages  |

## Engines

```json
  {
    "node": "16.13.1",
    "npm": "8.1.2"
  }
```
