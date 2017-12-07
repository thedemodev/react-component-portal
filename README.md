# react-component-portal [![build status](https://travis-ci.org/trendmicro-frontend/react-component-portal.svg?branch=master)](https://travis-ci.org/trendmicro-frontend/react-component-portal) [![Coverage Status](https://coveralls.io/repos/github/trendmicro-frontend/react-component-portal/badge.svg?branch=master)](https://coveralls.io/github/trendmicro-frontend/react-component-portal?branch=master)

[![NPM](https://nodei.co/npm/@trendmicro/react-component-portal.png?downloads=true&stars=true)](https://nodei.co/npm/@trendmicro/react-component-portal/)

React Component

Demo: https://trendmicro-frontend.github.io/react-component-portal

## Installation

1. Install the latest version of [react](https://github.com/facebook/react) and [react-component-portal](https://github.com/trendmicro-frontend/react-component-portal):

  ```
  npm install --save react @trendmicro/react-component-portal
  ```

2. At this point you can import `@trendmicro/react-component-portal` and its styles in your application as follows:

  ```js
  import Component from '@trendmicro/react-component-portal';

  // Be sure to include styles at some point, probably during your bootstraping
  import '@trendmicro/react-component-portal/dist/react-component-portal.css';
  ```

## Usage

```js
<Component
    className="component"
>
    GitHub
</Component>
```


## API

### Properties

**Noun** or **Adjective + Noun** is recommended for defining a property in any types: boolean, number, string, etc. For examples:

Name | Type | Default | Description
:--- | :--- | :------ | :----------
id | string\|number | |
title | node | | Title content.
activeKey | any | | Marks the Component with a matching eventKey as active.
activePage | number | 1 |
placement | one of:<br>'top',<br>'right',<br>'bottom',<br>'left' | 'right' | Sets the direction the Component is positioned towards.

**Verb** or **Verb + Noun** is recommended for defining a property in boolean or function type. For examples:

Name | Type | Default | Description
:--- | :--- | :------ | :----------
show | boolean | true | When `true` The component will show itself.
justified | boolean | false | Whether to take the full width of the parent.
pullLeft | boolean | false | Float the Component to the left.
enforceFocus | boolean | false | When `true` The component will prevent focus from leaving it while open.
mountOnEnter | boolean | false | Wait until the first "enter" transition to mount tabs (add them to the DOM).
getDimensionValue | function | | Function that returns the height or width of the animating DOM node.

## License

MIT
