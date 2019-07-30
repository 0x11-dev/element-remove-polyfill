# Element.remove Polyfill for IE11/IE10/IE9 and lower IE

![npm](https://img.shields.io/npm/v/element-remove-polyfill) ![npm](https://img.shields.io/npm/dw/element-remove-polyfill)

## Install

**NPM**

```
npm install element-remove-polyfill
```

**YARN**

```
yarn install element-remove-polyfill
```

## How it works

There is no `remove` in `Element.prototype` on lower version IE. IE10/IE11 will throw exception:

```
Object doesn't support property or method 'remove'
```

```
Error 对象不支持“remove”属性或方法
```

We polyfill it by add `remove` to the prototype.
